<template>
  <select :class="classAttrib"> 
      <template v-if="displayType === 'short'">
        <option v-for="(currency, key) in $store.getters.getCurrencies" :key="key"  
          :selected="preSelected === key"
        >
            {{ key }}
        </option>
      </template>
      <template v-else-if="displayType === 'long'">
        <option v-for="(currency, key) in $store.getters.getCurrencies" :key="key"  
          :selected="preSelected === currency"
        >
            {{ currency }}
        </option>
      </template>
  </select>
</template> 
<script>
export default {
  props: {
    classAttrib: {
      type: String,
      default: '',
    },
    preSelected: {
      type: String,
      default: 'Nigerian Naira'
    },
    displayType: {
      type: String,
      default: 'long'
    }
  },
  data() {
    return {
      text: null,
      editting: null,
      creating: null
    };
  },
  
};
</script>

 
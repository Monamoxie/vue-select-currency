# vueselect-currency
Easy to use and highly customizable

## Package installation
```
npm install --save vue-select-currency
```

### Package set up
* Import package into root file (main js)
  
```
import VueSelectCurrency from 'vue-select-currency'
Vue.use(VueSelectCurrency)
```

### Usage 
In component, use as
```
<VueSelectCurrency></VueSelectCurrency>
```

### Props Data
| Props | Type | Required |
| classAttrib | String | optional |
| preSelected | String | optional |
| displayType | String | optional 'long' or 'short' |

### Props Usage Example
To customize using props
```
<VueSelectCurrency :classAttrib="'form-control extra-class1 extra-class2'" :preSelected="'Nigerian Naira'" :displayType="'long'"></VueSelectCurrency>
```
 

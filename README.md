<p align="center"><img src="assets/logo.png"></p>

# vue-select-currency
An easy to use and highly customizable select plugin with a list of the currencies of over 150 nations in the world.  

## Package installation
```
npm install --save vue-select-currency
```

### Package set up
* Import package into root file
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
|-------------|--------|----------|
| classAttrib | String | optional |
| preSelected | String | optional |
| displayType | String | optional ['long', 'short'] |

### Props Usage Example
To customize using props
```
<VueSelectCurrency :classAttrib="'form-control extra-class1 extra-class2'" :preSelected="'Nigerian Naira'" :displayType="'long'"></VueSelectCurrency>
```

### Latest Version
v 0.1.1
 

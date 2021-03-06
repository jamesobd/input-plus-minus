See the original code here: [vue-number-input-spinner](https://github.com/krystalcampioni/vue-number-input-spinner/)

---


# input-plus-minus
A Vue number input component designed with Bootstrap.  The component has plus and minus buttons to increment and decrement the number.

## Installation

* Install the package via NPM:

* `npm install vue-number-input-spinner`

* Load it in your project:

```javascript
import NumberInputSpinner from 'vue-number-input-spinner'

export default {
  components: {
    NumberInputSpinner,
  },
}
```

#### Usage example:
```html
<NumberInputSpinner
  :min="0"
  :max="10"
  :step="2"
  :inputClass="your-css-class"
  :buttonClass="your-other-css-class"
  :integerOnly="true"
  v-model="yourVModel"
/>
```

# Vue Svg Spinner

> Only support Vue 2.0.

Custom Vue spinner SVG component only one spinner

[Live demo](https://vue-custom-spinner.netlify.app)

## Installation

### NPM

```bash
 npm install --save  vue-custom-spinner
```

### CommonJS

```js
var VueCustomSpinner = require('vue-custom-spinner');

new Vue({
  components: {
    'v-spinner': VueCustomSpinner,
    'spinner': VueCustomSpinner, // or
     ....
    // any name would you like to name to use  the component
  }
})
```

### ES6

```js
import VueCustomSpinner from 'vue-custom-spinner';

new Vue({
  components: {
    VueCustomSpinner,
  },
});
```

Or:

```js
Vue.component('v-spinner', require('vue-custom-spinner'));
```

### Browser globals

The `dist` folder contains `vue-custom-spinner.umd.js` and `vue-custom-spinner.umd.min.js`

```html
<script src="path/to/vue.js"></script>
<script src="path/to/vue-custom-spinner/dist/vue-custom-spinner.umd.js"></script>
// or
<script src="path/to/vue-custom-spinner"></script>
<script>
  var app = new Vue({
    el: '#app',
    components: {
      VueCustomSpinner,
    },
  });
</script>
```

## Usage

```html
<spinner :size="'sm'" width="2" />
```

You can customize the width and size with setting the props. All props have default value. You can control the spinner show/hidden with setting the loading prop.

## Props

| props | default | Type            |                                                                     |
| ----- | ------- | --------------- | ------------------------------------------------------------------- |
| size  | sm      | string          | Available sizes ['sm' , 'md' , 'lg' , 'xl'] you can set your custom |
| width | 3       | string - number | -                                                                   |

> want to see more features? [Contact me](https://own-portfolio-tree.vercel.app)


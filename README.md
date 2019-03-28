Getting started examples for Vue.js (see https://vuejs.org/v2/guide/#Getting-Started) bundled using locally installed *parcel* and *yarn*.

Install dependencies using:
```
yarn install
```

Start using:
```
yarn dev
```

Note:

The *alias* entry in *package.json* is needed to select the desired vue build that include the compiler and allows imports.
```
"alias": {
    "vue": "./node_modules/vue/dist/vue.esm.js"
  }
```

Also, the *script* tag that triggers parcel to build the js needs to go at the bottom ie. after the html that declares the *div* ids.
```
<script src="./src/index.js"></script>
``` 

Testing


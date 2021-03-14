
 __React__ does not Support __registering Global Components__ out of the box. 

In __Vue__ this can be achieved by registering the component like so

``` j
      Vue.component('my-component-name', { /* ... */ })
```
But this can also be achieved in __React__ with [Web Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components)

we will be using [react-web-component](https://www.npmjs.com/package/react-web-component) library which allows us to create web component with little or no stress

> add this package to your __React App__
``` js 
      npm install react-web-component     
``` 
After installing this package

> Create a React Components

![react-component](https://github.com/vwedesam/images/blob/main/Useful-Js-Node.js-Tips-Script/react/Screenshot-react-components.png)


> at this point we will use __react-web-component__ library to make our __component Global__

![global component](https://github.com/vwedesam/images/blob/main/Useful-Js-Node.js-Tips-Script/react/Screenshot%20react-web-component.png)

### usage

![component usage](https://github.com/vwedesam/images/blob/main/Useful-Js-Node.js-Tips-Script/react/Screenshot%20react-web-component-in-html.png)






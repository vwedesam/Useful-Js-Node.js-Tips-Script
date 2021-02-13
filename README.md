# Useful-Js-Node.js-Tips-Script


### #Catch Axios Network Error 
``` Js
  axios.request(options)
  .then(res=> consol.log(res )
  .catch(error => {
      if(!error.status){
          // catch Network Error
          //
          }
    })

```

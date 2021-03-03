
### Catch Network Error 

 >The __Error Response__ From __.catch(err=> )__ Block returns an empty __status__ if a Network Error occurs

``` Js
  axios.request(url, options)
  .then(res=> consol.log(res ) )
  .catch(error => {
      if(!error.status){
          // catch Network Error
          //
          }
    })

```

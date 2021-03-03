## dynamic href in html

-#
```js

        <template>
          <a v-bind:href="'/'+post_id+'/edit'"> Edit Post</a>
        </template>
       
       <script>
             export default {
                 data() {
                      return {
                        post_id: 3,
                     }
                 }
              } 
       </script>

```

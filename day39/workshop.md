# workshop 39

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
      <!-- 도움되는 콘솔 경고를 포함한 개발 버전 -->
      
  <script src="https://unpkg.com/axios/dist/axios.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
  <title>Document</title>
</head>
<body>
  <div id="app">
  <button v-on:click="getPost">ㄱㄱ</button><br>
  <li v-for="data in datas">
    <b>{{data.title}}</b> - {{data.body}}
  </li>
  </div>
  <script>
    const app = new Vue({
      el: '#app',
      data: {
        datas: [],
      },
      methods: {
        getPost: function() {
          const API_URL = 'https://jsonplaceholder.typicode.com/posts'
          const datas = axios.get(API_URL)
          .then(response => {
            console.log(response)
            this.datas = response.data

          })
          .catch(error =>{
            console.error(error)
          })
        }
      }
    })
  </script>
</body>
</html>
```


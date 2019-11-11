# workshop 39

```html
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <script src="https://unpkg.com/axios/dist/axios.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
  <title>Document</title>
  <style>
    img {
      width: 300px;
      height: 300px;
    }
  </style>
</head>
<body>
  <div id="app">
    <select v-model="number" >
      <option v-for="num in [1,2,3,4,5,6,7,8,9]" :value="num">{{num}}</option>


    </select>
    <button @click="getDogImage">get {{number}} Dogs! </button>
    <div v-for="url in dogImage">
    <img :src="url" alt="멍멍"  />
    </div>
  </div>

  <script>
    const app = new Vue({
      el: "#app",
      data: {
        dogImage: [],
        number: 1,

      },
      methods: {
        getDogImage: async function() {
          const API_URL = `https://dog.ceo/api/breeds/image/random/${this.number}`
          const response = await axios.get(API_URL)
          this.dogImage = response.data.message
        },
      
      },
      created: function() {
        this.getDogImage()
      }
    })
  </script>
</body>
</html>

```


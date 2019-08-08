## 워크샵

```html
<!DOCTYPE html>
<html lang="ko">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
    integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
  <style>
    body {
      height: 3000px;
    }

    .container {
      margin-top: 75px;
    }

    #foot {
      height: 50px;
      font-size: 120%;
    }

    #foot-text {
      position: relative;
      right: 50px;
      top: 10px;
    }

    #id1 {
      font-size: 130%;
      position: relative;
      top:10px;
    }
  </style>

</head>

<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-dark fixed-top">
    <a class="navbar-brand text-white" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link text-white" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-secondary" href="#">Git</a>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Python</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Form -->
  <div class="container pt-1">
    <form>
      <div class="form-group">
        <label for="exampleInputEmail1">Email address</label>
        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp"
          placeholder="Enter email">
        <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
      </div>
      <div class="form-group">
        <label for="exampleInputPassword1">Password</label>
        <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
      </div>
      <div class="form-group">
        <label for="exampleInputPassword Confirmation1">Password Confirmation</label>
        <input type="password" class="form-control" id="exampleInputPassword Confirmation1"
          placeholder="Password Confirmation">
      </div>
      <button type="submit" class="btn btn-primary">Submit</button>
    </form>
    <div class="row">
      <div class="col-4">
        <div class="card" style="width: 18rem;">
          <img src="images/고양이.gif" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">고양이</h5>
            <p class="card-text">고양이는 귀엽다</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div class="card" style="width: 18rem;">
          <img src="images/고양이.gif" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">고양이</h5>
            <p class="card-text">고양이는 귀엽다</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div class="card">
          <img src="images/고양이.gif" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">고양이</h5>
            <p class="card-text">고양이는 귀엽다</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
    </div>
    <div id="foot" class="fixed-bottom bg-light text-secondary text-right">
      <p id="foot-text">[본 문서의 저작권은 (주)멀티캠퍼스의 소유이므로 무단 전재나 재배포를 금합니다.]</p>
    </div>
    <div class="fixed-bottom text-left">
      <p id="id1">1</p>
    </div>
  </div>


  <!-- Bootstrap Javascript -->
  <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
    integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
    crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"
    integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"
    crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"
    integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
    crossorigin="anonymous"></script>
</body>

</html>
```


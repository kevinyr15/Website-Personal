<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

body {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: skyblue;
}

.container {
    width: 100%;
    display: flex;
    max-width: 850px;
    background: #fff;
    border-radius: 15px;
    box-shadow: 0 10px 15px rgba(0, 0, 0, 0.1);
}

.login {
    width: 400px;
}

form {
    width: 250px;
    margin: 60px auto;
}

h1 {
    margin: 20px;
    text-align: center;
    font-weight: bolder;
    text-transform: uppercase;
}

hr {
    border-top: 2px solid skyblue;
}

p {
    text-align: center;
    margin: 10px;
}

.right img {
    width: 450px;
    height: 100%;
    border-top-right-radius: 15px;
    border-bottom-right-radius: 15px;
}

form label {
  display: block;
  font-size: 16px;
  font-weight: 600;
  padding: 5px;
}

input {
  width: 100%;
  margin: 2px;
  border: none;
  outline: 8px;
  border-radius: 5px;
  border: 1px solid gray;
}

button {
  border: none;
  outline: none;
  padding: 8px;
  width: 252px;
  color: #fff;
  font-size: 16px;
  cursor: pointer;
  margin-top: 20px;
  border-radius: 5px;
  background: skyblue;
}

button:hover {
  background: blue;
}

@media {max-width: 880px;} {
  .container {
    width: 100%;
    max-width: 750px;
    margin-left: 20px;
    margin-right: 20px;
  }
  
  form {
    width: 300px;
    margin: 20px auto;
  }
  
  .login {
    width: 400px;
    padding: 20px;
  }
  
  button {
    width: 100%;
  }
  
  .right img {
    width: 100%;
    height: 100%;
  }
}

    </style>
</head>
<body>
    <div class="container">
        <div href="https://www.instagram.com/smpn12arutselatan?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==" class="login">
            <form action="">
                <h1>Login</h1>
                <hr>
                <p>SMPN 12 ARUT SELATAN</p>
                <Label for="">Email</Label>
                <input type="text" placeholder="example@gmail.com">
                <label for="">Password</label>
                <input type="password" placeholder="Password">
                <button>Login</button>
                <p>
                    <a href="#">Forgot Password</a>
                </p>
            </form>
        </div>
        <div class="right">
            <img src="image.png" alt="">
        </div>
    </div>
</body>
</html>

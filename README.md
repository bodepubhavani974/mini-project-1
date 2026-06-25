# mini-project-1
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Login Page</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;

    /* Background Pattern */
    background:
    repeating-linear-gradient(
        -45deg,
        #f8f8f8 0px,
        #f8f8f8 18px,
        #f2f2f2 18px,
        #f2f2f2 36px
    );
}

.login-box{
    width:700px;
    padding:50px;
    background:white;
    border:1px solid #d9d9d9;
    border-radius:8px;
    box-shadow:0 8px 30px rgba(0,0,0,0.08);
}

h1{
    font-size:90px;
    margin-bottom:20px;
}

input{
    width:100%;
    height:70px;
    margin-bottom:25px;
    padding:0 25px;
    font-size:24px;
    border:2px solid #d8d8d8;
}

.password{
    border:3px solid #000;
}

button{
    width:100%;
    height:70px;
    border:none;
    border-radius:6px;
    font-size:28px;
    color:white;
    cursor:pointer;
    background:linear-gradient(to right,#0d2f8b,#123da8);
}
</style>
</head>
<body>

<div class="login-box">
    <h1>Login</h1>

    <input type="email" placeholder="bhavanibodepu2@gmail.com">

    <input class="password" type="password" placeholder="Password">

    <button>Login</button>
</div>

</body>
</html>

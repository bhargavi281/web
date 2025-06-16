# web
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Html Website</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        * {
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
body
 {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: url('bg.jpeg') no-repeat;
    background-size: cover;
    background-position: center;
    background-image: url("https://img.freepik.com/free-photo/ursa-major-ursa-minor-constellations_23-2150028878.jpg?t=st=1735102622~exp=1735106222~hmac=256cdffe4fa24c97e28bc27de4fb4704b44d65321c3e81242b9c336377c9a4bf&w=1060");
}
header {
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    padding: 20px 100px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 99;
}

.logo {
    font-size: 2rem;
    color: white;
    user-select: none;
}

.navigation a {
    position: relative;
    font-size: 1.1rem;
    color: white;
    text-decoration: none;
    font-weight: 500;
    margin-left: 40px;
}

.navigation a::after {
    content: '';
    position: absolute;
    width: 100%;
    left: 0;
    height: 3px;
    background: #d87708;
    border-radius: 5px;
    bottom: -6px;
    transform: scaleX(0);
    transition: transform .5s;
}

.navigation a:hover::after {
    transform: scaleX(1);
}


.navigation .btn-login-popup {
    width: 130px;
    height: 50px;
    border: 2px solid white;
    background: transparent;
    outline: none;
    border-radius: 6px;
    cursor: pointer;
    font-size: 1.1rem;
    color: white;
    font-weight: 500;
    margin-left: 40px;
    transform: .5s;
}

.navigation .btn-login-popup:hover {
    background-color: white;
    color:#d87708;
}

/* Section 2 -> Login Form CSS */

.warpper {
    position: relative;
    width: 400px;
    height: 440px;
    background: #ffffff36;
    border: 2px solid rgba(255, 255, 255, .5);
    backdrop-filter: blur(5px);
    border-radius: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
    transition: height .2s ease ;
}

.warpper .form-box {
    width: 100%;
    padding: 40px;
}

.form-box h2 {
    font-size: 2rem ;
    color: orange;
    text-align: center;
}

.input-box {
    position: relative;
    width: 100% ;
    height: 50px;
    border-bottom: 2px solid orange;
    margin: 30px 0 ;
}

.input-box label {
    position: absolute;
    top: 50%;
    left: 5px;
    transform: translateY(-50%);
    font-size: 1em;
    font-weight: 500;
    pointer-events: none;
    transform: .5s;
}

.input-box input:focus~label,
.input-box input:valid~label {
    top: -3px;
}

.input-box input {
    width: 100% ;
    height: 100%;
    background: transparent;
    border: none;
    outline: none;
    font-size: 1em;
    color: white;
    font-weight: 300;
    padding: 0 35px 0 5px;
}

.remember-forgot {
    font-size: 1rem;
    font-weight: 300;
    display: flex;
    justify-content: space-between;
    text-align: center;
}

.remember-forgot label input {
    accent-color: black;
    margin-right: 3px;
}

.remember-forgot a {
    text-decoration: none;
    color: black;
}

.remember-forgot a:hover {

    text-decoration: underline;
}

.btn {
    width: 100%;
    height: 35px;
    top: 17px;
    background: orange;
    border: none;
    outline: none;
    border-radius: 6px;
    cursor: pointer;
    color: white;
    position: relative;
}

.login-regester {
    font-size: 1rem;
    color: black;
    text-align: center;
    font-weight: 500;
    margin: 25px 0 10px;
}

.login-regester p a {
    color: black;
    text-decoration: none;
    font-weight: 300;
}

.login-regester p a:hover {
    text-decoration: underline;
}
    </style>
</head>
<body>
    
    <header>
        <h2 class="logo">Logo</h2>
        <nav class="navigation">
           <a href="#">Home</a>
           <a href="#">About</a>
           <a href="#">Service</a>
           <a href="#">Contact</a>
           <a href="#">Location finder</a>
           <button class="btn-login-popup">Login</button>
        </nav>
    </header>

    <div class="warpper">
        <div class="form-box login">
            <h2>Register</h2>
            <form action="">
                <div class="input-box">
                  <span class="icon"></span>
                  <input type="text/css"  required>
                  <label>username</label>
                </div>
                <div class="input-box">
                    <span class="icon"></span>
                    <input type="email"  required>
                    <label>Email</label>
                  </div>
                <div class="input-box">
                    <span class="icon"></span>
                    <input type="Password" required>
                    <label >Password</label>
                  </div>
                  <div class="remember-forgot">
                    <label><input type="checkbox">Remember me</label>
                    <a href="">Forgot Password ?</a>
                  </div>
                  <button type="submit" class="btn" onclick="login()"><a href="login with registration.html">register</a></button>
                  <div>
                    <script language="javascript">
                        function login()
                        {
                            window.alert("registration successfully");
                        }
                    </script>
                  </div>
                  <div class="login-regester">
                    <p>Don't have account ?<a href="" class="register-link">Register</a></p>
                  </div>
            </form>
        </div>
    </div>
</body>
</html>

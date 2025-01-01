<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagram Login</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fafafa;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .login-container {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 350px;
        }
        .logo {
            display: block;
            margin: 0 auto 20px;
            width: 175px;
        }
        .input-field {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .login-btn {
            background-color: #0095f6;
            color: white;
            border: none;
            padding: 10px;
            width: 100%;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        .login-btn:hover {
            background-color: #007bb5;
        }
        .forgot-password {
            text-align: center;
            margin-top: 10px;
        }
        .forgot-password a {
            color: #0095f6;
            text-decoration: none;
        }
        .separator {
            text-align: center;
            margin: 15px 0;
        }
        .separator span {
            color: #ccc;
        }
        .signup-link {
            text-align: center;
        }
        .signup-link a {
            color: #0095f6;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <div class="login-container">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/Instagram_icon.png/800px-Instagram_icon.png" alt="Instagram Logo" class="logo">
        <form action="" method="POST">
            <input type="text" class="input-field" placeholder="Username or email" required>
            <input type="password" class="input-field" placeholder="Password" required>
            <button type="submit" class="login-btn">Log In</button>
        </form>

        <div class="forgot-password">
            <a href="#">Forgot password?</a>
        </div>

        <div class="separator">
            <span>OR</span>
        </div>

        <div class="signup-link">
            Don't have an account? <a href="#">Sign up</a>
        </div>
    </div>

</body>
</html>




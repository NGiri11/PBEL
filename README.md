<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Login Page</title>
    <link rel="stylesheet" href="/CSS/style2.css">
</head>
<body>
    <div class="login-container">
        <h2>Login</h2>
        <form action="#" method="post">
            <label for="username">Username</label>
            <input type="text" id="username" name="username" required placeholder="Username">

            <label for="password">Password</label>
            <input type="password" id="password" name="password" required placeholder="Password">
             <div class="rme">
                <div>
                   <label for="remember">Remember me</label>
                   <input type="checkbox" id="remember" name="remember">
                   </div>
                   <span><a href="#">Forget Password</a></span>
                </div>
            <button type="submit">Login</button>
        </form>
    </div>
</body>
</html>

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



body {
    font-family: Arial, sans-serif;
    background-color: #f1f1f1;
    display: flex;
    height: 100vh;
    justify-content: center;
    align-items: center;
    background-image: url(https://images.pexels.com/photos/27796917/pexels-photo-27796917.jpeg);
    background-size: cover;
}

.login-container {
    padding: 2rem;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    width: 300px;
    background-color: rgba(255, 255, 255, 0.18);
}

.login-container h2 {
    text-align: center;
    margin-bottom: 1rem;
}

.login-container label {
    display: block;
    margin: 10px 0 5px;
}

.login-container input {
    width: 100%;
    padding: 8px;
    box-sizing: border-box;
}

.login-container button {
    width: 100%;
    padding: 10px;
    background-color: #4CAF50;
    color: white;
    border: none;
    margin-top: 15px;
    cursor: pointer;
    border-radius: 4px;
    transition: background-color 0.5s ease-in-out;
}

.login-container button:hover {
    background-color: #45a049;
    transition: background-color 0.5s ease-in-out;
}

.rme{
    display: flex;
    justify-content: space-between;
    align-items: center;
}

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Login Page</title>
  <style>
    /* Add some style to the page */
    body {
      font-family: Arial, sans-serif;
      background-color: #F2F2F2;
    }
    h1 {
      text-align: center;
      margin-top: 49px;
    }
    form {
      width: 300px;
      margin: 0 auto;
      background-color: white;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.2);
    }
    input[type=text], input[type=password] {
      width: 100%;
      padding: 10px;
      margin: 5px 0 20px 0;
      border: none;
      border-radius: 3px;
      background-color: #f1f1f1;
    }
    input[type=submit] {
      background-color: #4CAF50;
      color: white;
      padding: 12px 20px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      width: 100%;
    }
    input[type=submit]:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <h1>Login Page</h1>
  <form action="login.php" method="post">
    <label for="username">Username</label>
    <input type="text" id="username" name="username" placeholder="Enter your username" required>
    
    <label for="password">Password</label>
    <input type="password" id="password" name="password" placeholder="Enter your password" required>
    
    <input type="submit" value="Login">
  </form>
</body>
</html>

# New-project
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login Page</title>
  <link rel="stylesheet" href="harsh.css">
</head>
<body>
  <div class="login-container">
    <form class="login-form">
      <label for="firstName">First Name:</label>
      <input type="text" id="firstName" name="firstName" required>

      <label for="lastName">Last Name:</label>
      <input type="text" id="lastName" name="lastName" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

      <label for="query">Describe your query:</label>
      <textarea id="query" name="query" required></textarea>

      <button type="submit">Login</button>
    </form>
  </div>
</body>
</html>

#css file
body {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
  margin: 0;
  background-image: "C:\Users\ashis\OneDrive\Documents\vs code\photo.jpg";
  background-color: #f5f5f5;
}

.login-container {
  border: 2px solid transparent;
  border-image: linear-gradient(45deg, red, green, blue) 1;
  border-image-slice: 1;
  padding: 20px;
  border-radius: 10px;
  transition: border 0.5s ease-in-out;
}

.login-form {
  display: flex;
  flex-direction: column;
}

label {
  margin-bottom: 5px;
}

input, textarea {
  margin-bottom: 15px;
  padding: 8px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

button {
  padding: 10px;
  background-color: #3498db;
  color: #fff;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

button:hover {
  background-color: #2980b9;
}

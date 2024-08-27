<!DOCTYPE html>
<html>
<head>
      <title>HTML Login Form</title>
      <link rel="stylesheet" href="style.css">
</head>
<body>
      <div class="main">
            <h3>login page </h3>
            <form action="">
                  <label for="first">
                        Username:
                  </label>
                  <input type="text" 
                         id="first" 
                         name="first" 
                         placeholder="Enter your Username" required>
<div>
                  <label for="password">
                        Password:
                  </label>
                  <input type="password"
                         id="password" 
                         name="password"
                         placeholder="Enter your Password" required>
                        </div>
                  <div class="wrap">
                        <button type="submit"
                                onclick="solve()">
                              Submit 
                        </button>
                        <div class="wrap">
                            <button type="reset"
                                    onclick="solve()">
                                  reset 
                            </button>
                  </div>
            </form>
            <p>Not registered?
                  <a href="#"
                     style="text-decoration: none;">
                        Create an account
                  </a>
            </p>
      </div>
</body>
</html>

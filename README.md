welcome to my website
idex.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ssegawa Daniel - Personal Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Ssegawa Daniel</h1>
        <p>Bachelor of Information Systems and Technology</p>
        <p>UTAMU University</p>
    </header>
    <section>
        <h2>About Me</h2>
        <p>I studied my primary at Bulwadda Primary School, secondary at Greenhill SS Masaka, and now pursuing a degree in Information Systems and Technology at UTAMU University.</p>
    </section>
    <section>
        <h2>Services</h2>
        <ul>
            <li>Computer-related services</li>
            <li>Software</li>
            <li>Hardware</li>
        </ul>
    </section>
    <section>
        <h2>Contact</h2>
        <p>Phone: 0757888223 or 0777129790</p>
        <p>Email: ssegawadaniel70@gmail.com</p>
        <p>Socials: <a href="https://facebook.com/SsegawaDaniel">Facebook</a> | <a href="https://tiktok.com/@SsegawaDaniel">TikTok</a></p>
    </section>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Registration Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background-color: #f0f0f0;
    }
    .registration-form {
      background-color: #fff;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      width: 300px;
    }
    .registration-form h2 {
      text-align: center;
    }
    .registration-form label {
      font-weight: bold;
    }
    .registration-form input[type="text"],
    .registration-form input[type="email"],
    .registration-form input[type="date"],
    .registration-form input[type="password"],
    .registration-form button {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .registration-form button {
      background-color: #4CAF50;
      color: white;
      border: none;
      cursor: pointer;
    }
    .registration-form button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>

<div class="registration-form">
  <h2>Register Here</h2>
  <form action="#">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>

    <label for="dob">Date of Birth:</label>
    <input type="date" id="dob" name="dob" required>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>

    <label for="password">Password:</label>
    <input type="password" id="password" name="password" required>

    <button type="submit">Register</button>
  </form>
</div>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .form-container {
            width: 300px;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 10px;
            box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.1);
        }
        .form-container h2 {
            text-align: center;
        }
        .form-container label {
            margin: 10px 0 5px;
            display: block;
            font-weight: bold;
        }
        .form-container input[type="text"],
        .form-container input[type="date"],
        .form-container input[type="email"],
        .form-container input[type="password"] {
            width: 1

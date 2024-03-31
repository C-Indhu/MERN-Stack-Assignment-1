<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Form with Validation</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 50%;
            margin: 50px auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .input-group {
            margin-bottom: 20px;
        }
        label {
            display: block;
            margin-bottom: 5px;
        }
        input[type="text"],
        input[type="email"],
        input[type="password"] {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            transition: border-color 0.3s ease;
        }
        input[type="text"]:focus,
        input[type="email"]:focus,
        input[type="password"]:focus {
            outline: none;
            border-color: #3498db;
        }
        .error-message {
            color: #e74c3c;
            font-size: 14px;
            display: none;
        }
        .error {
            border-color: #e74c3c !important;
        }
        button {
            padding: 10px 20px;
            background-color: #3498db;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #2980b9;
        }
    </style>
</head>
<body>
<div class="container">
    <h2>Registration Form</h2>
    <form id="registration-form" action="#" method="post">
        <div class="input-group">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username">
            <div class="error-message" id="username-error">Username is required.</div>
        </div>
        <div class="input-group">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email">
            <div class="error-message" id="email-error">Email is invalid.</div>
        </div>
        <div class="input-group">
            <label for="password">Password:</label>
            <input type="password" id="password" name="password">
            <div class="error-message" id="password-error">Password must be at least 6 characters.</div>
        </div>
        <button type="submit">Submit</button>
    </form>
</div>
<script>
    const form = document.getElementById('registration-form');
    const usernameInput = document.getElementById('username');
    const emailInput = document.getElementById('email');
    const passwordInput = document.getElementById('password');
    form.addEventListener('submit', function (event) {
        event.preventDefault();
        if (validateForm()) {
            alert('Form submitted successfully!');
            form.reset();
        }
    });
    function validateForm() {
        let isValid = true;
        if (usernameInput.value.trim() === '') {
            setError(usernameInput, 'Username is required.');
            isValid = false;
        } else {
            setSuccess(usernameInput);
        }
        if (!validateEmail(emailInput.value)) {
            setError(emailInput, 'Email is invalid.');
            isValid = false;
        } else {
            setSuccess(emailInput);
        }
        if (passwordInput.value.length < 6) {
            setError(passwordInput, 'Password must be at least 6 characters.');
            isValid = false;
        } else {
            setSuccess(passwordInput);
        }
        return isValid;
    }
    function setError(input, message) {
        const errorElement = input.nextElementSibling;
        errorElement.innerText = message;
        errorElement.style.display = 'block';
        input.classList.add('error');
    }
    function setSuccess(input) {
        const errorElement = input.nextElementSibling;
        errorElement.style.display = 'none';
        input.classList.remove('error');
    }
    function validateEmail(email) {
        const re = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
        return re.test(email);
    }
</script>
</body>
</html>
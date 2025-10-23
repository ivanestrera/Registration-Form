
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #00d9ff; 
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            padding: 20px; 
        }
        .form-container {
            background-color: #ffffff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgb(0, 81, 255);
            width: 90%;
            max-width: 400px; 
        }
        h2 {
            text-align: center;
            color: #ff0015;
        }
        label {
            display: block;
            margin-bottom: 5px;
            color: #000000;
        }
        input[type="text"], input[type="email"], input[type="password"], input[type="tel"], input[type="date"], select, textarea {
            width: 100%;
            padding: 8px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
        button {
            width: 100%;
            padding: 10px;
            background-color: #4CAF50;
            color: rgb(255, 255, 255);
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0400ff;
        }
        @media (max-width: 600px) {
            .form-container {
                padding: 15px;
            }
            body {
                padding: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="form-container">
        <h2>Registration Form</h2>
        <form id="registrationForm" action="#" method="post">
            <label for="firstName">First Name:</label>
            <input type="text" id="firstName" name="firstName" required>
            <label for="lastName">Last Name:</label>
            <input type="text" id="lastname" name="lastName" required>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
            <label for="phone">Phone Number:</label>
            <input type="tel" id="phone" name="phone">
            <label for="birthdate">Birthdate:</label>
            <input type="date" id="birthdate" name="birthdate">
            <label for="gender">Gender:</label>
            <select id="gender" name="gender">
                <option value="">Select Gender</option>
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
                <option value="prefer-not-to-say">Prefer not to say</option>
            </select>
            <label for="address">Address:</label>
            <textarea id="address" name="address" rows="3"></textarea>
            <button type="submit">Register</button>
        </form>
    </div>
    <script>
        document.getElementById('registrationForm').addEventListener('submit', function(event) {
            event.preventDefault(); 
            alert('KLINTOYYYYYY!'); 
    </script>
</body>
</html>

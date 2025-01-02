<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
</head>
<body>
    <h2>Registration Form</h2>
    <form action="#" method="post">
        <label for="fname">First Name:</label><br>
        <input type="text" id="fname" name="fname" required><br><br>

        <label for="lname">Last Name:</label><br>
        <input type="text" id="lname" name="lname" required><br><br>

        <label for="email">Email Address:</label><br>
        <input type="email" id="email" name="email" required><br><br>

        <label for="password">Password:</label><br>
        <input type="password" id="password" name="password" required><br><br>

        <label for="gender">Gender:</label><br>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label><br>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label><br><br>

        <label for="dob">Date of Birth:</label><br>
        <input type="date" id="dob" name="dob" required><br><br>

        <label for="country">Country:</label><br>
        <select id="country" name="country">
            <option value="usa">USA</option>
            <option value="canada">Canada</option>
            <option value="uk">UK</option>
            <option value="australia">Australia</option>
        </select><br><br>

        <input type="submit" value="Register">
    </form>
</body>
</html>


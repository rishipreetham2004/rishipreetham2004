<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Page</title>
    <style>
        .button {
            border-radius: 4px;
        }

        .mot {
            padding: 10px;
        }
    </style>
</head>

<body>
    <div>
        <h2>Registration Page</h2>
        <p>Please fill out the following form to register:</p>
        <form action="#" method="POST">
            <div>
                <label for="username">Username:</label><br>
                <input type="text" id="username" name="username" required minlength="3" maxlength="20">
            </div>
            <div>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" required>
            </div>
            <div>
                <label for="password">Password:</label><br>
                <input type="password" id="password" name="password" required minlength="6">
            </div>
            <div>
                <label for="age">Age:</label><br>
                <input type="number" id="age" name="age" min="18" max="100" required>
            </div>
            <div>
                <label for="gender">Gender:</label><br>
                <input type="radio" id="male" name="gender" value="male" class="mot"> Male
                <input type="radio" id="female" name="gender" value="female"> Female
            </div>
            <div>
                <button type="submit" class="btn btn-primary button">Register</button>
            </div>
        </form>
    </div>
</body>

</html>

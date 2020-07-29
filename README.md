<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>RegisterPage</title>
</head>
<body>
    <center>
        <form action = "/myWeb/Register" method = "get">
            <table border="2">
                <tr>
                    <td>UserName</td>
                    <td><input type="text" name="Name"></td>
                </tr>
                <tr>
                    <td>UserPsw</td>
                    <td><input type="password" name="PassWord"></td>
                </tr>
                <tr>
                    <td>UserGender</td>
                    <td>
                        <input type="radio" name="Gender" value="男">男
                        <input type="radio" name="Gender" value="女">女
                    </td>
                </tr>
                <tr>
                    <td>UserEmail</td>
                    <td><input type="text" name="Email"></td>
                </tr>
                <tr>
                    <td><input type="submit" name="register"></td>
                    <td><input type="reset"></td>
                </tr>
            </table>
        </form>
    </center>
</body>
</html>

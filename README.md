# addmission.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Addmission form</h1>
    <form height="50%" width="60%">
        First name:<input type="text" name="fname" placeholder="enter the first name"><br><br>
        <!-- here the placeholder is the attribute of the input tag where it specifies the hint to user to enter the input-->
        Last name:<input type="text" name="lname" placeholder="enter the last name"><br><br>
        Password:<input type="password" name="pass" placeholder="set the password"><br><br>
        Confirm Password:<input type="password" name="cp" placeholder="confirm the password"><br><br>
        DOB:<input type="date" name="date"><br><br>
        Email id:<input type="email" name="email" placeholder="enter your email adddress"><br><br>
        Gender:<input type="radio" name="male" value="male">male
        <input type="radio" name="male" value="male">Female:<input type="radio" name="male" value="male">other<br><br>
        Hobbies:<input type="checkbox" value="Cricket" name="ch1">Cricket
        <input type="checkbox" value="dance" name="ch2">dance
        <input type="checkbox" value="Sing" name="ch3">Sing
        <input type="checkbox" value="read" name="ch4">Read<br><br>
        Attach photo here:<input type="file"><br><br>
        Qualification<select name="qual">
            <option value="10th">10th</option>
            <option value="12th">12th</option>
            <option value="Graduate">Graduate</option>
            <option value="undergraduation">undergraduation</option>

        </select><br><br>
        Give link of your last year's project:<input type="url"><br><br>
        <input type="submit" value="submit" name="submit">
        <input type="reset" value="reset" name="reset">

        
    </form>
</body>
</html>

 


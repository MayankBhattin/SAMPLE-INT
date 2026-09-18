<!-- THIS IS A REGISTRATION FORM FOR A BCA STUDENT !-->


<!DOCTYPE html>
<html>
<head>
    <title>Registration Form for BCA STUDENT</title>
</head>
<body>

<h2>Registration Form for BCA STUDENT </h2>

<form action="submit.php" method="post" target="_blank" name="Myform">

    <label>Name</label>
    <input type="text" name="username" placeholder="Enter name" required maxlength="20">
    <br><br>

    <label>Email</label>
    <input type="email" name="email" placeholder="Enter email">
    <br><br>

    <label>Password</label>
    <input type="password" name="password" required minlength="8">
    <br><br>

    <label>DOB</label>
    <input type="date" name="dob">
    <br><br>

    <label>Gender</label>
    <input type="radio" name="Gen" value="M"> Male
    <input type="radio" name="Gen" value="F"> Female
    <br><br>

    <label>Hobbies:</label>
    <input type="checkbox" name="H" value="Sports"> Sports
    <input type="checkbox" name="H" value="Reading"> Reading
    <input type="checkbox" name="H" value="Coding"> Coding
    <input type="checkbox" name="H" value="Singing"> Singing
    <br><br>

    <label>Semester:</label>
    <select name="Semester" multiple size="2">
        <option value="1 st sem">1st sem</option>
        <option value="2nd">2nd sem</option>
    </select>
    <br><br>


    <label>Address</label><br>
    <textarea name="Address" rows="2" cols="20" placeholder="Enter address"></textarea>
    <br><br>

    <input type="submit" value="Submit">
    <input type="reset" value="Reset">

</form>

</body>
</html>

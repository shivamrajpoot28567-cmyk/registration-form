<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Registration Form</title>
</head>
<body>

<h2>Registration Form</h2>

<form>

  
    <label>First Name:</label>
    <input type="text" placeholder="Enter First Name">
    <br><br>

   
    <label>Last Name:</label>
    <input type="text" placeholder="Enter Last Name">
    <br><br>

 
    <label>Email:</label>
    <input type="email" placeholder="Enter Email">
    <br><br>

  
    <label>Mobile:</label>
    <input type="tel" placeholder="Enter Mobile Number">
    <br><br>

    
    <label>Password:</label>
    <input type="password" placeholder="Enter Password">
    <br><br>

    
    <label>Date of Birth:</label>
    <input type="date">
    <br><br>

    <label>Gender:</label>
    <input type="radio" name="gender"> Male
    <input type="radio" name="gender"> Female
    <input type="radio" name="gender"> Other
    <br><br>

   
    <label>Course:</label>
    <select>
        <option>--Select Course--</option>
        <option>BCA</option>
        <option>B.Tech</option>
        <option>MCA</option>
    </select>
    <br><br>

    
    <label>Skills:</label>
    <input type="checkbox"> HTML
    <input type="checkbox"> CSS
    <input type="checkbox"> JavaScript
    <input type="checkbox"> Python
    <br><br>

  
    <label>Address:</label><br>
    <textarea rows="4" cols="30" placeholder="Enter Address"></textarea>
    <br><br>

  
    <label>Upload Photo:</label>
    <input type="file">
    <br><br>

   
    <input type="submit" value="Submit Form">
    <input type="reset" value="Reset">

</form>

</body>
</html>

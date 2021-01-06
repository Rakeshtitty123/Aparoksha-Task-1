# WebD-Task-1
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width-device-width,inital-scale-1.0";>
    <meta name="description" content="Html introduction".>
    <title> Form Tag</title>
</head>
<body>
 <h1>Student 
  Registration Form</h1>
  
  <form>
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname"><br>
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname"><br>
    <br>
    <label for="birthday">DOB:</label><br>
    <input type="date" id="birthday" name="birthday"><br>
    <br>
    <br>
    <label for="fname">Father's name:</label><br>
    <input type="text" id="fname" name="fname"><br>
    <br>
    <br>
    <label for="document">Document: </label>  
    <br>
    <input type="radio" id="document" name="document" value="Aadhar"/>Aadhar<br>
    <input type="radio" id="document" name="document" value="Driving License"/>Driving License <br/>  
    <input type="radio" id="document" name="document" value="Other"/>Other<br>
    <br>
    <br>
    <label for="gender">Gender</label>
    <select id="select">
    <option value="male">Male</option>
    <option value="female">Female</option>
    <option value="other">Other</option>
    </select>
    <br><br>
    <div>
    <label for="description">Description:</label><br>
    <textarea id="w3review" name="description" rows="4" cols="50">
    </textarea>
    <br>
    <br>
    <input type="checkbox" id="Confirm" name="Confirm">
    <label for="confirm">Confirm </label><br> 
    
    <input type="submit" value="Submit">
    </form>
</body>

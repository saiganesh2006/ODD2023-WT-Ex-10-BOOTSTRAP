## Ex-10-BOOTSTRAP

## OBJECTIVE-10(a):
## AIM:
To Create a Responsive feedback form for a virtual workshop on Constructing Modern Websites built with Bootstrap.

## Step-1:
Open your HTML file and include the Bootstrap CSS file.

## Step-2:
Create a Bootstrap Container.

## Step-3:
Apply Bootstrap Form Classes in the program.

## Step-4:
Add Bootstrap Styles to Submit Button in the program.

## Step-5:
Close the program and Display the Output.

## CODE:
```html
<html>
<head>
<h1>Workshop on Constructing Modern Websites</h1>
<link rel="stylesheet" href="style.css">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <div class="container">
        <form action="#" method="post">
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" required>
        <br>

          <label for="email">Email:</label>
          <input type="email" id="email" name="email" required>
    <br>
          <label for="rating">How would you rate the workshop?</label>
          <select id="rating" name="rating" required>
            <option value="excellent">Excellent</option>
            <option value="good">Good</option>
            <option value="average">Average</option>
            <option value="poor">Poor</option>
          </select>
    <br>
          <label for="comments">Comments:</label>
          <textarea id="comments" name="comments" rows="1"></textarea>
    <br>
            <button type="submit" class="btn btn-primary">Submit</button>
        </form>
    </div>
</body>
</html>
```

## OUTPUT 10(a):
![Screenshot 2023-12-29 201114](https://github.com/saiganesh2006/ODD2023-WT-Ex-10-BOOTSTRAP/assets/145742342/c82b1f9e-3eed-4104-8b2f-bc08ae14510d)

## RESULT:
Succesfully created a responsive feedback form for a virtual workshop on constructing modern websites built with Bootstrap.

## OBJECTIVE-10(b):
## AIM:
To Create a Responsive student registration form for ABC Engineering College built with Bootstrap.

## Step-1:
Open your HTML file and include the Bootstrap CSS file.

## Step-2:
Create a Bootstrap Container.

## Step-3:
Apply Bootstrap Form Classes in the program.

## Step-4:
Add Bootstrap Styles to Submit Button in the program.

## Step-5:
Close the program and Display the Output.

## CODE:
```html
<html>
<head>
<h1>College Registration Form</h1>
<link rel="stylesheet" href="style.css">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
<div class="container">
<div class="content">
<form action="#">
<div class="user-details">
<div class="input-box">
<span class="details">First Name:</span>
<input type="text" placeholder="Enter your 1st name" required>
</div>
<div class="input-box">
<span class="details">Last Name:</span>
<input type="text" placeholder="Enter your last name" required>
</div>
<div class="input-box">
<span class="details">Email:</span>
<input type="text" placeholder="Enter your email" required>
</div>
<div class="input-box">
<span class="details">Phone Number:</span>
<input type="text" placeholder="Enter your number" required>
</div>

<label for="rating">Gender :</label>
          <select id="rating" name="rating" required>
            <option value="excellent">Male</option>
            <option value="good">Female</option>
            <option value="average">Not To Say</option>
          </select>
</label>
</div>
</div>
<div class="button">
<input type="submit" value="Register">
</div>
</form>
</div>
</div>
</body>
</html>
```
## OUTPUT 10(b):
![image](https://github.com/saiganesh2006/ODD2023-WT-Ex-10-BOOTSTRAP/assets/145742342/80ddb7ca-e68d-45f2-b55d-d9142d46a4ae)

## RESULT:
Succesfully Created a Responsive student registration form for ABC Engineering College built with Bootstrap.

## OBJECTIVE-10(C):
## AIM:
To Develop a program to structure vertical form layouts which handle form validation in bootstrap.

## Step-1:
Open your HTML file and include the Bootstrap CSS file.

## Step-2:
Create a Bootstrap Container.

## Step-3:
Apply Bootstrap Form Classes in the program.

## Step-4:
Add Bootstrap Styles to Submit Button in the program.

## Step-5:
Close the program and Display the Output.

## CODE:
```html
<html>
<head>
<h1>Validation Form</h1>
<form>
    <div class="form-group">
    <div class="col-md-6">
    <label for="valid01" class="form-label">Username:</label>
    <input type="text" class="form-control" id="valid01" required>
    <div class="invalid-feedback">
    </div>
    </div>
    <br>
    <div class="col-md-3">
    <label for="valid02" class="form-label">Password:</label>
    <input type="text" class="form-control" id="valid02" required>
    <div class="invalid-feedback">
    </div>
    </div>
    <br>
    <div class="col-md-3">
    <label for="valid03" class="form-label">Department:</label>
    <select class="form-select" id="valid04" required>
    <option>Choose anyone Department</option>
    <option>AIML</option>
    <option>AIDS</option>
    <option>IOT</option>
    </select>
    <div class="invalid-feedback">
    </div>
    </div>
    <br>
    <div class="col-md-9">
    <label for="valid04" class="form-label">Mobile Number:</label>
    <input type="text" class="form-control" id="valid04" required>
    <div class="valid-feedback">
    </div>
    </div>
    <br>
    <div class="col-md-9">
    <label for="valid06" class="form-label">E-Mail ID:</label>
    <input type="text" class="form-control" id="valid06" required>
    <div class="valid-feedback"> 
    </div>
    </div>
    <br>
    <button type="button" class="btn btn-success"> Submit </button>
</head>
</html>  
```

## OUTPUT 10(c):
![image](https://github.com/saiganesh2006/ODD2023-WT-Ex-10-BOOTSTRAP/assets/145742342/4019c941-bd3b-4201-b3c7-5e192871915f)

## RESULT:
Succesfully Developed the program to structure vertical form layouts which handle form validation in bootstrap.

## OBJECTIVE-10(d):
## AIM:
To Create a basic email login form in Bootstrap with validation function.

## Step-1:
Open your HTML file and include the Bootstrap CSS file.

## Step-2:
Create a Bootstrap Container.

## Step-3:
Apply Bootstrap Form Classes in the program.

## Step-4:
Add Bootstrap Styles to Submit Button in the program.

## Step-5:
Close the program and Display the Output.

## CODE:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <title>Email Login Form</title>
</head>
<body>

<div class="container mt-5">
  <div class="row justify-content-center">
    <div class="col-md-6">
      <div class="card">
        <div class="card-header">
          <h4>Email Login</h4>
        </div>
        <div class="card-body">
          <form action="#" method="post">
            <div class="form-group">
              <label for="email">Email:</label>
              <input type="email" class="form-control" id="email" name="email" placeholder="Enter your email" required>
            </div>
            <button type="submit" class="btn btn-primary">Login</button>
          </form>
        </div>
      </div>
    </div>
  </div>
</div>


</body>
</html>

```

## OUTPUT 10(d):
![Screenshot 2023-12-29 205810](https://github.com/saiganesh2006/ODD2023-WT-Ex-10-BOOTSTRAP/assets/145742342/9d8d76f7-887b-4a06-bcbb-45a7e6f9d968)

## RESULT:
Successfully Created the basic email login form in Bootstrap with validation function.

## DEVELOPED BY : D.B.V.SAI GANESH
## REGISTER NUMBER : 212223240025

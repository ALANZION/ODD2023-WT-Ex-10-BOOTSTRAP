# Ex-10-BOOTSTRAP 
## AIM :
To Create a Responsive feedback form for a virtual workshop on Constructing Modern Websites
built with Bootstrap.
DESIGN STEPS :
### STEP 1 :
Initialize the HTML document with the necessary Bootstrap links.
### STEP 2 :
Create a container for the form and add a heading.
### Step 3:
Construct the form
### Step 4:
Add a submit button and Link Bootstrap JavaScript.
## PROGRAM :
DEVELOPED BY : ALAN ZION H
REGISTER NO : 212223240004

```
<!DOCTYPE html>
<html>
<head>
<title>Feedback Form</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/cs
</head>
<body>
<div class="container">
<h2 class="mt-5">Workshop Feedback Form</h2>
<form>
<div class="form-group">
<label for="name">Name:</label>
<input type="text" class="form-control" id="name" placeholder="Enter y
</div>
<div class="form-group">
<label for="email">Email:</label>
<input type="email" class="form-control" id="email" placeholder="Enter
</div>
<div class="form-group">
<label for="feedback">Feedback:</label>
<textarea class="form-control" id="feedback" placeholder="Enter your f
</div>
<button type="submit" class="btn btn-primary">Submit</button>
</form>
</div>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.j
</body>
</html>
```
## OUTPUT:


## RESULT :
This code creates a responsive feedback form for a virtual workshop on constructing modern
websites built with Bootstrap.
QUESTION 10(B)
## AIM :
Create a Responsive student registration form for ABC Engineering College built with Bootstrap.
DESIGN STEPS :
### Step 1:
Initialize the HTML document with the necessary Bootstrap links.
### Step 2:
Create a container for the form and add a heading.### 
### Step 3:
Inside the form, create form groups for the student’s name, email, and course.
### Step 4:
Add a submit button for the form.
### Step 5:
Link the Bootstrap JavaScript file at the end of the body.
## PROGRAM :
DEVELOPED BY : ALAN ZION H
REGISTER NO : 212223240004

```
<!DOCTYPE html>
<html>
<head>
<title>Student Registration Form</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/cs
</head>
<body>
<div class="container">
<h2 class="mt-5">ABC Engineering College - Student Registration</h2>
<form>
<div class="form-group">
<label for="name">Name:</label>
<input type="text" class="form-control" id="name" placeholder="Enter y
</div>
<div class="form-group">
<label for="email">Email:</label>
<input type="email" class="form-control" id="email" placeholder="Enter
</div>
<div class="form-group">
<label for="course">Course:</label>
<input type="text" class="form-control" id="course" placeholder="Enter
</div>
<button type="submit" class="btn btn-primary">Register</button>
</form>
</div>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.j
</body>
</html>
 ```
## OUTPUT:


## RESULT :
This code creates a Responsive student registration form for ABC Engineering College built with
Bootstrap.
QUESTION 10(C)
## AIM :
Develop a program to structure vertical form layouts which handle form validation in bootstrap.
DESIGN STEPS :
### Step 1:
Initialize the HTML document with the necessary Bootstrap links.
### Step 2:
Create a container for the form and add a heading.
### Step 3:
Inside the form, create a form group for the name input field. Add the required attribute to the
input field for validation.
### Step 4
Add a submit button for the form.
### Step 5:
Add a script to handle the form validation on submit.
## PROGRAM :
DEVELOPED BY : ALAN ZION H
REGISTER NO : 21222323240004

```
<!DOCTYPE html>
<html>
<head>
<title>Form Validation</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/cs
</head>
<body>
<div class="container">
<h2 class="mt-5">Form with Validation</h2>
<form class="needs-validation" novalidate>
<div class="form-group">
<label for="name">Name:</label>
<input type="text" class="form-control" id="name" placeholder="Enter y
<div class="invalid-feedback">Please enter your name.</div>
</div>
<button type="submit" class="btn btn-primary">Submit</button>
</form>
</div>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.j
<script>
(function() {
'use strict';
window.addEventListener('load', function() {
var forms = document.getElementsByClassName('needs-validation');
var validation = Array.prototype.filter.call(forms, function(form) {
form.addEventListener('submit', function(event) {
if (form.checkValidity() === false) {
event.preventDefault();
event.stopPropagation();
}
form.classList.add('was-validated');
}, false);
});
}, false);
})();
</script>
</body>
</html>
  ```
## OUTPUT:

## RESULT :
This code develops a program to structure vertical form layouts which handle form validation in
bootstrap.
QUESTION 10(D)
## AIM :
Create a basic email login form in Bootstrap with validation function.
DESIGN STEPS :
### Step 1:
Initialize the HTML document with the necessary Bootstrap links.
### Step 2:
Create a container for the form and add a heading.
### Step 3:
Inside the form, create a form group for the email input field. Add the required attribute to the
input field for validation.
### Step 4:
Add a submit button for the form.
### Step 5:
Add a script to handle the form validation on submit.
## PROGRAM :
DEVELOPED BY : ALAN ZION H
REGISTER NO : 212223240004

```
<!DOCTYPE html>
<html>
<head>
<title>Login Form</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/cs
</head>
<body>
<div class="container">
<h2 class="mt-5">Login Form</h2>
<form class="needs-validation" novalidate>
<div class="form-group">
<label for="email">Email:</label>
<input type="email" class="form-control" id="email" placeholder="Enter
<div class="invalid-feedback">Please enter a valid email.</div>
</div>
<button type="submit" class="btn btn-primary">Login</button>
</form>
</div>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.j
<script>
(function() {
'use strict';
window.addEventListener('load', function() {
var forms = document.getElementsByClassName('needs-validation');
var validation = Array.prototype.filter.call(forms, function(form) {
form.addEventListener('submit', function(event) {
if (form.checkValidity() === false) {
event.preventDefault();
event.stopPropagation();
}
form.classList.add('was-validated');
}, false);
});
}, false);
})();
</script>
</body>
</html>
```
# OUTPUT:


## RESULT :
This code creates a basic email login form in Bootstrap with validation functionAIM :
To Create a Responsive feedback form for a virtual workshop on Constructing Modern Websites
built with Bootstrap.
DESIGN STEPS :
### STEP 1 :
Initialize the HTML document with the necessary Bootstrap links.
### STEP 2 :
Create a container for the form and add a heading.
### Step 3:
Construct the form
### Step 4:
Add a submit button and Link Bootstrap JavaScript.
## PROGRAM :
DEVELOPED BY : ALAN ZION H
REGISTER NO : 212223240004
```
<!DOCTYPE html>
<html>
<head>
<title>Feedback Form</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/cs
</head>
<body>
<div class="container">
<h2 class="mt-5">Workshop Feedback Form</h2>
<form>
<div class="form-group">
<label for="name">Name:</label>
<input type="text" class="form-control" id="name" placeholder="Enter y
</div>
<div class="form-group">
<label for="email">Email:</label>
<input type="email" class="form-control" id="email" placeholder="Enter
</div>
<div class="form-group">
<label for="feedback">Feedback:</label>
<textarea class="form-control" id="feedback" placeholder="Enter your f
</div>
<button type="submit" class="btn btn-primary">Submit</button>
</form>
</div>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.j
</body>
</html>
```
## OUTPUT:
![Screenshot 2024-01-03 093231](https://github.com/ALANZION/ODD2023-WT-Ex-10-BOOTSTRAP/assets/145743064/7eafbcf1-fa00-4427-9a1e-b2aeca653a72)


## RESULT :
This code creates a responsive feedback form for a virtual workshop on constructing modern
websites built with Bootstrap.
QUESTION 10(B)
## AIM :
Create a Responsive student registration form for ABC Engineering College built with Bootstrap.
DESIGN STEPS :
### Step 1:
Initialize the HTML document with the necessary Bootstrap links.
### Step 2:
Create a container for the form and add a heading.
### Step 3:
Inside the form, create form groups for the student’s name, email, and course.
### Step 4:
Add a submit button for the form.
### Step 5:
Link the Bootstrap JavaScript file at the end of the body.
## PROGRAM :
DEVELOPED BY : ALAN ZION H
REGISTER NO : 212223240004

```
<!DOCTYPE html>
<html>
<head>
<title>Student Registration Form</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/cs
</head>
<body>
<div class="container">
<h2 class="mt-5">ABC Engineering College - Student Registration</h2>
<form>
<div class="form-group">
<label for="name">Name:</label>
<input type="text" class="form-control" id="name" placeholder="Enter y
</div>
<div class="form-group">
<label for="email">Email:</label>
<input type="email" class="form-control" id="email" placeholder="Enter
</div>
<div class="form-group">
<label for="course">Course:</label>
<input type="text" class="form-control" id="course" placeholder="Enter
</div>
<button type="submit" class="btn btn-primary">Register</button>
</form>
</div>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.j
</body>
</html>
  ```
## OUTPUT:

![Screenshot 2024-01-03 093156](https://github.com/ALANZION/ODD2023-WT-Ex-10-BOOTSTRAP/assets/145743064/5a97886a-894a-4db1-8a18-76be56e9dd60)

## RESULT :
This code creates a Responsive student registration form for ABC Engineering College built with
Bootstrap.
QUESTION 10(C)
## AIM :
Develop a program to structure vertical form layouts which handle form validation in bootstrap.
DESIGN STEPS :
### Step 1:
Initialize the HTML document with the necessary Bootstrap links.
### Step 2:
Create a container for the form and add a heading.
### Step 3:
Inside the form, create a form group for the name input field. Add the required attribute to the
input field for validation.
### Step 4:
Add a submit button for the form.
### Step 5:
Add a script to handle the form validation on submit.
## PROGRAM :
DEVELOPED BY : ALAN ZION H
REGISTER NO : 212223240004

  ```
<!DOCTYPE html>
<html>
<head>
<title>Form Validation</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/cs
</head>
<body>
<div class="container">
<h2 class="mt-5">Form with Validation</h2>
<form class="needs-validation" novalidate>
<div class="form-group">
<label for="name">Name:</label>
<input type="text" class="form-control" id="name" placeholder="Enter y
<div class="invalid-feedback">Please enter your name.</div>
</div>
<button type="submit" class="btn btn-primary">Submit</button>
</form>
</div>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.j
<script>
(function() {
'use strict';
window.addEventListener('load', function() {
var forms = document.getElementsByClassName('needs-validation');
var validation = Array.prototype.filter.call(forms, function(form) {
form.addEventListener('submit', function(event) {
if (form.checkValidity() === false) {
event.preventDefault();
event.stopPropagation();
}
form.classList.add('was-validated');
}, false);
});
}, false);
})();
</script>
</body>
</html>
  ```
## OUTPUT :
![Screenshot 2024-01-03 093057](https://github.com/ALANZION/ODD2023-WT-Ex-10-BOOTSTRAP/assets/145743064/303766f5-4434-42ea-bb57-febdffc475dc)


## RESULT :
This code develops a program to structure vertical form layouts which handle form validation in
bootstrap.
QUESTION 10(D)
## AIM :
Create a basic email login form in Bootstrap with validation function.
DESIGN STEPS :
### Step 1:
Initialize the HTML document with the necessary Bootstrap links.
### Step 2:
Create a container for the form and add a heading.
### Step 3:
Inside the form, create a form group for the email input field. Add the required attribute to the
input field for validation.
### Step 4:
Add a submit button for the form.
### Step 5:
Add a script to handle the form validation on submit.
## PROGRAM :
DEVELOPED BY : ALAN ZION H
REGISTER NO : 212223240004

```
<!DOCTYPE html>
<html>
<head>
<title>Login Form</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/cs
</head>
<body>
<div class="container">
<h2 class="mt-5">Login Form</h2>
<form class="needs-validation" novalidate>
<div class="form-group">
<label for="email">Email:</label>
<input type="email" class="form-control" id="email" placeholder="Enter
<div class="invalid-feedback">Please enter a valid email.</div>
</div>
<button type="submit" class="btn btn-primary">Login</button>
</form>
</div>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.j
<script>
(function() {
'use strict';
window.addEventListener('load', function() {
var forms = document.getElementsByClassName('needs-validation');
var validation = Array.prototype.filter.call(forms, function(form) {
form.addEventListener('submit', function(event) {
if (form.checkValidity() === false) {
event.preventDefault();
event.stopPropagation();
}
form.classList.add('was-validated');
}, false);
});
}, false);
})();
</script>
</body>
</html>
  ```
## OUTPUT :
![Screenshot 2024-01-03 092346](https://github.com/ALANZION/ODD2023-WT-Ex-10-BOOTSTRAP/assets/145743064/750aabf1-6a87-4f64-8a05-12270d779170)


## RESULT :
This code creates a basic email login form in Bootstrap with validation functionv

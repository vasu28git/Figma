# Ex09 Event Registration Web Application
# Date:25-11-2024
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
signin.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brain and Strategy Event</title>
    <link rel="stylesheet" href="figma.css">
</head>
<body>
    <div class="page">
        <img class="logo" src="logo.png" alt="Logo">
        <img class="main-logo" src="mainlogo.png" alt="Main Logo">
        <h1 class="page-title">Brain and Strategy Event</h1>
        <form action="#" method="post">
            <div class="input-field">
                <label for="email">Email</label>
                <input type="email" id="email" name="email" placeholder="Enter your email">
            </div>
            <div class="input-field">
                <label for="password">Password</label>
                <input type="password" id="password" name="password" placeholder="Enter your password">
            </div>
            <button type="submit" class="button">Sign In</button>
        </form>
        <a href="events.html" class="link">Go to Event List</a>
    </div>
</body>
</html>
~~~
events.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event List - Brain and Strategy Event</title>
    <link rel="stylesheet" href="figma.css">
</head>
<body>
    <div class="page">
        <img class="logo" src="logo.png" alt="Logo">
        <img class="main-logo" src="mainlogo.png" alt="Main Logo">
        <h1 class="page-title">Brain and Strategy Event</h1>
        <div class="event-list">
            <p>&#x2022; ThinkTank Summit</p>
            <p>&#x2022; Strategic Sparks</p>
            <p>&#x2022; Innovator's Edge</p>
            <p>&#x2022; The Big Picture Forum</p>
            <p>&#x2022; Mindset Mastery</p>
            <p>&#x2022; Brainpower 360°</p>
            <p>&#x2022; VisionCraft Conference</p>
        </div>
        <a href="register.html" class="link">Go to Register</a>
    </div>
</body>
</html>
~~~
register.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Register - Brain and Strategy Event</title>
    <link rel="stylesheet" href="figma.css">
</head>
<body>
    <div class="page">
        <img class="logo" src="logo.png" alt="Logo">
        <img class="main-logo" src="mainlogo.png" alt="Main Logo">
        <h1 class="page-title">Brain and Strategy Event</h1>
        <form action="#" method="post">
            <div class="input-field">
                <label for="name">Name</label>
                <input type="text" id="name" name="name" placeholder="value">
            </div>
            <div class="input-field">
                <label for="register-number">Register No</label>
                <input type="text" id="register-number" name="register-number" placeholder="value">
            </div>
            <div class="input-field">
                <label for="department">Department</label>
                <input type="text" id="department" name="department" placeholder="value">
            </div>
            <button type="submit" class="button">Register</button>
        </form>
        <a href="signin.html" class="link">Back to Sign In</a>
    </div>
</body>
</html>
~~~
figma.css
~~~
body {
    margin: 0;
    font-family: Arial, sans-serif;
}
.page {
    width: 440px;
    height: 956px;
    margin: 0 auto;
    background: white;
    position: relative;
}
.logo {
    width: 440px;
    height: 66px;
    position: absolute;
    top: 0;
    left: 0;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}
.main-logo {
    width: 173px;
    height: 167px;
    position: absolute;
    top: 77px;
    left: 135px;
}
.page-title {
    position: absolute;
    top: 279px;
    width: 440px;
    text-align: center;
    font-size: 27px;
    font-style: italic;
    font-weight: 800;
}
.input-field {
    display: flex;
    flex-direction: column;
    margin: 10px 86px;
}
.input-field label {
    font-size: 16px;
}
.input-field input {
    padding: 10px;
    border: 2px solid black;
    border-radius: 8px;
}
.button {
    width: calc(100% - 172px);
    margin: 10px 86px;
    padding: 12px;
    background: #2C2C2C;
    color: #F5F5F5;
    text-align: center;
    border: none;
    border-radius: 8px;
    cursor: pointer;
}
.button:hover {
    background: #444;
}
.link {
    text-align: center;
    margin: 10px 0;
    color: #1E1E1E;
    text-decoration: underline;
    cursor: pointer;
}
.event-list {
    padding: 0 58px;
    margin-top: 370px;
}
.event-list p {
    font-size: 20px;
    line-height: 1.6;
    font-style: italic;
}

~~~
# OUTPUT:

![page1](https://github.com/user-attachments/assets/8435dcae-d881-4757-89ab-4a9bc308f861)


![page2](https://github.com/user-attachments/assets/963fca3d-921e-41f5-82f3-41ba0478af92)


![page3](https://github.com/user-attachments/assets/cc2b76c7-70d8-429b-b3bf-55bc7cc528c1)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.

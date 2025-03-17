# FCC-Design-a-business-card
HTML5 and CSS code for a business card I designed 

** start of undefined **

<!DOCTYPE html>
<html lang="en">

<head>
    <link href='styles.css'rel='stylesheet'/>
    <meta charset="utf-8">
    <title>Business Card</title>
</head>
<body>
<main>
<div class='business-card'>
    <img src='https://cdn.freecodecamp.org/curriculum/labs/flower.jpg' alt='Flower' class='profile-image'>
    <p class='full-name'>Louis Radford</p>
    <p class='designation'>Full Stack Web Developer</p>
    <p class='company'>Free Code Camp</p>
    <hr>  
    <p>louisradford@outlook.com</p>
    <p>+44 7974 413137</p>
    <a href='https://github.com/LouisRadford?tab=repositories'>Portfolio</a>
   <hr>
    <div class='social-media'>
    <h2>Connect with me</h2>
       <a href='https://x.com/louradfordd'>Twitter</a>
        <a href='https://www.linkedin.com/in/louisradford/'>LinkedIn</a>
        <a href='https://github.com/LouisRadford?tab=repositories'>GitHub</a>
    </main>
</body>
</html>

** end of undefined **

** start of undefined **

body{
  background-color: rosybrown;
  font-family: Arial, sans-serif;
  padding: 20px;
}
.business-card{
  width: 300px;
  background-color: white;
  padding: 20px;
  margin-top: 100px;
  font-size: 16px;
  text-align: center;
  margin-left: auto;
  margin-right: auto;
}
p{
  margin-top: 5px;
  margin-bottom: 5px;
}
.full-name{
  font-size: 30px;
  font-color: grey;
  margin-top: 15px;
}
.designation{
  font-size: 25;
  font-color: gray;
  margin-top: 15px;
}
hr{
   margin-top: 20px;
  margin-bottom: 20px
}
.profile-image{
  width: 200px;
  height: 200px;
}
a {
  color: black;
  text-decoration: none;
}

a:visited {
  color: black;
}

a:hover {
  color: brown;
  text-decoration: underline;
}

a:active {
  color: brown;
}



** end of undefined **


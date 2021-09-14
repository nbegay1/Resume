<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume</title>
    <link rel="stylesheet" href="Resume_Site_Temp.css">

</head>
<body>

    <div id = "left_side">
        <h1>Name</h1>
        <h2>Title</h2>
        <p>Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text</p>

        <div id = "profile">
            <h2>Profile</h2>
            <p>Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text</p>
            <p>Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text</p>
        </div>

        <div id = "skills">
            <h2>Skills</h2>
            <li>Text Temp</li>
            <li>Text Temp</li>
            <li>Text Temp</li>
            <li>Text Temp</li>
            <li>Text Temp</li>
            <li>Text Temp</li>
        </div>

        <div id = "Contact">
            <h2>Contact</h2>
            <p> <a href="mailto:">email@gmail.com </a></p>
            <p> <a href="tel:5555555555">5555555555</a> </p>
            <p>Webstie: www.notarealsite.com</p>
        </div>
    </div>

    <div id = "right_side">
        <div id = "experience">
        <h2>Experience</h2>
        <h3>Work History</h3>
        <p> <em>Time Frame</em> </p>
        <p>Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text</p>
        <h3>Work History</h3>
        <p> <em>Time Frame</em> </p>
        <p>Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text</p>
        <h3>Work History</h3>
        <p> <em>Time Frame</em> </p>
        <p>Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text</p>
    
        </div>
 
        <div id = "education">
            <h2>Educatoin</h2>
            <h3>School</h3>
            <p> <em>Time Frame</em> </p>
            <p>Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text</p>
            <h3>School</h3>
            <p> <em>Time Frame</em> </p>
            <p>Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text Temp Text</p>
            
        </div>
    </div>
    
</body>
</html>
body{
    font-family: 'Times New Roman', Times, serif;
    margin: auto;
    max-width: 1000px;
    display: flex;
    align-items: flex-start;
    font-size: 12pt;
}
#left_side{
    flex: 1 1 600px;
    padding: 1em;
    line-height: 1.5em;
}
#right_side{
    border-left: black solid 1px;
    flex: 1 1 600px;
    padding: 1em;
    line-height: 1.5em;
}
h1,
h2{
    text-align: center;
}
h2{
    position: relative; top: 15px;
    border-bottom: black solid 1px;
}
#title{
    text-align: center;
    font-size: 24px;
}
p{
    margin-top: 0px;
    margin-bottom: .5em;
}

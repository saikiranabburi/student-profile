<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color:rgb(34, 90, 112);
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(32, 32, 95);
            /* color: white; */
            text-align: center;
            padding: 20px;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            background-color: white; 
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px color(srgb rgb(31, 29, 29) rgb(126, 128, 126) rgb(133, 133, 136));
        }
        .profile-header {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 20px;
        }
        .profile-header img {
            border-radius: 50%;
            width: 120px;
            height: 120px;
            margin-right: 20px;
        }
        .profile-header h2 {
            margin: 0;
        }
        .profile-header p {
            font-size: 1.1em;
            color: #555;
        }
        .info {
            display: flex;
            justify-content: space-between;
            color: rgb(99, 77, 50);
            margin-bottom: 20px;
        }
        .info div {
            width: 45%;
        }
        .info h3 {
            color: #4CAF50;
        }
        .skills, .hobbies {
            margin-top: 20px;
        }
        .skills ul, .hobbies ul {
            list-style-type: none;
            padding: 0;
        }
        .skills ul li, .hobbies ul li {
            /* background-color: #f1f1f1; */
            margin: 5px 0;
            padding: 8px;
            border-radius: 4px;
        }
        .footer{
            color: #4CAF50;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Student Profile</h1>
</header>

<div class="container">
    <div class="profile-header">
        <div>
            <h2>saikiran Abburi</h2>
            <p>Student |electronics and communication engineering</p>
        </div>
    </div>

    <div class="info">
        <div>
            <h3>Personal Information</h3>
            <p><strong>Email:</strong> saikiranabburi1@gmail.com</p>
            <p><strong>Phone:</strong> +91 8179610599</p>
            <p><strong>Date of Birth:</strong> october 1, 2003</p>
        </div>
        <div>
            <h3>Academic Information</h3>
            <p><strong>Course:</strong> Bachelor of technology in electronics and communication engineering </p>
            <p><strong>collage:</strong> sasi institute of technology and engineering </p>
            <p><strong>Year:</strong> 3rd Year</p>
        </div>
    </div>

    <div class="skills">
        <h3>Skills</h3>
        <ul>
            <li>JavaScript</li>
            <li>HTML & CSS</li>
            <li>Python</li>
            <li>React.js</li>
        </ul>
    </div>

    <div class="hobbies">
        <h3>Hobbies</h3>
        <ul>
            <li>Coding</li>
            <li>Photography</li>
        </ul>
    </div>
</div>
<footer>
    <h1>my webpage completion</h1>
</footer>

</body>
</html>

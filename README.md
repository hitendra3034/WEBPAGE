# WEBPAGE

   
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navbar Example</title>
    <style>
        /* Add some basic styling for the navbar */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        
        ul.navbar {
            list-style-type: none;
            background-color: #333;
            overflow: hidden;
            margin: 0;
            padding: 0;
        }

        ul.navbar li {
            float: left;
        }

        ul.navbar li a {
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }

        ul.navbar li a:hover {
            background-color: #555;
        }
    </style>
</head>
<body>
    <ul class="navbar">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</body>
</html>


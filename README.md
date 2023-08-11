<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello, hello! - Demo Page</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <style>
        /* Basic Reset */
        *, *:before, *:after {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        <link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>


        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            background-color: #f5f5f5;
            color: #333;
            padding: 50px;
        }

        header {
            background-color: #3498db;  /* Primary Color */
            color: #fff;
            padding: 20px 0;
            margin-bottom: 20px;
            text-align: center;
        }

        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        nav {
            margin: 20px 0;
            text-align: center;
        }

        nav a {
            display: inline-block;
            padding: 10px 20px;
            margin: 0 5px;
            background-color: #f5f5f5;
            color: #333;
            border-radius: 5px;
            transition: background-color 0.3s, color 0.3s;
        }

        nav a:hover, nav a.active {
            background-color: #3498db;  /* Primary Color */
            color: #fff;
        }

        a {
            color: #3498db;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        img.profile-pic {
            width: 150px;
            border-radius: 50%;
            margin: 20px 0;
        }

        footer {
            margin-top: 20px;
            text-align: center;
        }

        section {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>

<body>

    <header>
        <img src="path-to-your-image.jpg" alt="Your Picture" class="profile-pic">
        <h1>James Afful</h1>
        <p>Welcome to my GitHub page</p>
    </header>

    <nav>
        <a href="professional.html">Professional</a>
        <a href="personal.html">Personal</a>
        <a href="#">Coming Soon</a>
    </nav>

    <section>
        <h2>About Me</h2>
        <p>Hello! I'm James Afful, a mechanical engineering graduate student at Iowa State University. I love to talk about #CFD (Computational Fluid Dynamics), #HPC (High-Performance Computing), and #ML (Machine Learning). Here, I will talk about my professional life and other things I do with my time. Check out my projects below!</p>

        <h2>Projects</h2>
        <ul>
            <li><a href="#link-to-your-project-1">Project 1</a>: Brief description of project 1.</li>
            <li><a href="#link-to-your-project-2">Project 2</a>: Brief description of project 2.</li>
            <li><a href="#link-to-your-project-3">Project 3</a>: Brief description of project 3.</li>
            <li><a href="#link-to-your-project-4">Project 4</a>: Brief description of project 4.</li>
            <li><a href="#link-to-your-project-5">Project 5</a>: Brief description of project 5.</li>
            <li><a href="#link-to-your-project-6">Project 6</a>: Brief description of project 6.</li>
            <li><a href="#link-to-your-project-7">Project 7</a>: Brief description of project 7.</li>

        </ul>
    </section>

    <footer>
        <p>Find me on <a href="https://github.com/jamesafful">GitHub</a> | <a href="https://linkedin.com/in/james-afful-745247179">LinkedIn</a> | <a href="https://instagram.com/_james_afful">Instagram</a></p>  | <a href="https://twitter.com/_james_afful">Twitter</a>
    </footer>

</body>

</html>

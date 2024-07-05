# Personal-portfolio-page

### HTML Structure

html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to your CSS file -->
</head>
<body>
    <header>
        <div class="container">
            <h1>My Portfolio</h1>
            <p>Welcome to my portfolio website</p>
        </div>
    </header>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Write a brief introduction about yourself here.</p>
        </div>
    </section>

    <section id="projects">
        <div class="container">
            <h2>Projects</h2>
            <div class="project">
                <h3>Project 1</h3>
                <p>Description of Project 1</p>
            </div>
            <div class="project">
                <h3>Project 2</h3>
                <p>Description of Project 2</p>
            </div>
            <!-- Add more projects as needed -->
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Your Name</p>
        </div>
    </footer>
</body>
</html>





### CSS (styles.css)


css
/* Reset default browser styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Basic styling */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

header {
    background: #333;
    color: #fff;
    padding-top: 30px;
    min-height: 70px;
    border-bottom: #3c3c3c 3px solid;
}

header h1 {
    float: left;
    margin-top: 10px;
    padding-left: 20px;
    font-size: 24px;
}

header p {
    float: right;
    margin-top: 18px;
    padding-right: 20px;
    font-size: 16px;
}

section {
    padding: 20px 0;
}

section h2 {
    color: #333;
    font-size: 26px;
    margin-bottom: 20px;
}

.project {
    background: #f4f4f4;
    margin: 10px;
    padding: 20px;
    border: #ccc 1px solid;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    left: 0;
    bottom: 0;
    width: 100%;
}


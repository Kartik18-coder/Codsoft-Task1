# Codsoft-Task1
I Developed This website using HTML , CSS, Java Script
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Landing Page</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f4f4f4;
            color: #333;
        }

        header, footer {
            background-color: #2c3e50;
            color: #ecf0f1;
            padding: 1em;
            text-align: center;
        }

        section {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2em;
        }

        h1 {
            color: #3498db;
        }

        p {
            line-height: 1.6;
        }

        .main-content {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
        }

        .feature {
            flex: 1;
            margin: 0 1em;
            padding: 1em;
            background-color: #ecf0f1;
            border-radius: 5px;
        }

        footer {
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>Your Brand</h1>
        <p>Welcome to our awesome landing page!</p>
    </header>

    <section>
        <div class="main-content">
            <div class="feature">
                <h2>Feature 1</h2>
                <p>Description of the first feature.</p>
            </div>
            <div class="feature">
                <h2>Feature 2</h2>
                <p>Description of the second feature.</p>
            </div>
            <div class="feature">
                <h2>Feature 3</h2>
                <p>Description of the third feature.</p>
            </div>
        </div>
    </section>

    <footer>
        &copy; 2024 Your Brand. All rights reserved.
    </footer>

</body>
</html>


#level 1 Task 2
index.html:

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Your Name - Portfolio</title>
</head>

<body>
    <header>
        <div class="logo">Your Name</div>
        <div class="tagline">Web Developer Extraordinaire</div>
    </header>

    <section id="about">
        <img src="your-image.jpg" alt="Your Name">
        <p>
            Hi, I'm Your Name, a passionate web developer with experience in creating
            beautiful and responsive websites.
        </p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML5</li>
            <li>CSS3</li>
            <li>JavaScript</li>
            <li>Responsive Design</li>
            <li>Web Development</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <img src="project1.jpg" alt="Project 1">
            <h3>Project 1</h3>
            <p>Description of Project 1.</p>
        </div>
        <div class="project">
            <img src="project2.jpg" alt="Project 2">
            <h3>Project 2</h3>
            <p>Description of Project 2.</p>
        </div>
    </section>

    <section id="resume">
        <h2>Resume</h2>
        <p>Download my resume <a href="your-resume.pdf" target="_blank">here</a>.</p>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: your.email@example.com</p>
        <p>Phone: (123) 456-7890</p>
    </section>

    <footer>
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>
</body>

</html>


styles.css:
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

.tagline {
    font-style: italic;
}

section {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
}

img {
    max-width: 100%;
    height: auto;
}

ul {
    list-style-type: none;
    padding: 0;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}


# level 1 Task 3
index.html:

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Basic Calculator</title>
</head>

<body>
    <div class="calculator">
        <input type="text" id="display" readonly>
        <div class="buttons" onclick="handleButtonClick(event)">
            <button class="operator">+</button>
            <button class="operator">-</button>
            <button class="operator">*</button>
            <button class="operator">/</button>
            <button>7</button>
            <button>8</button>
            <button>9</button>
            <button class="operator">C</button>
            <button>4</button>
            <button>5</button>
            <button>6</button>
            <button class="equals">=</button>
            <button>1</button>
            <button>2</button>
            <button>3</button>
            <button class="clear">0</button>
            <button>.</button>
        </div>
    </div>
    <script src="script.js"></script>
</body>

</html>


styles.css:

body {
    font-family: 'Arial', sans-serif;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    margin: 0;
}

.calculator {
    border: 1px solid #ccc;
    border-radius: 5px;
    overflow: hidden;
}

#display {
    width: 100%;
    padding: 10px;
    font-size: 1.5em;
    border: none;
    outline: none;
    text-align: right;
}

.buttons {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
    padding: 10px;
}

button {
    width: 100%;
    padding: 15px;
    font-size: 1.2em;
    border: 1px solid #ccc;
    background-color: #f8f8f8;
    cursor: pointer;
}

button:hover {
    background-color: #e0e0e0;
}

button.clear {
    grid-column: span 2;
}

button.equals {
    background-color: #4caf50;
    color: white;
}

button.operator {
    background-color: #ffa500;
    color: white;
}


script.js:

document.addEventListener('DOMContentLoaded', function () {
    let display = document.getElementById('display');
    let buttons = document.querySelector('.buttons');

    let currentInput = '';

    buttons.addEventListener('click', handleButtonClick);

    function handleButtonClick(event) {
        const buttonValue = event.target.innerText;

        if (buttonValue === 'C') {
            clearDisplay();
        } else if (buttonValue === '=') {
            calculateResult();
        } else {
            updateDisplay(buttonValue);
        }
    }

    function updateDisplay(value) {
        currentInput += value;
        display.value = currentInput;
    }

    function clearDisplay() {
        currentInput = '';
        display.value = '';
    }

    function calculateResult() {
        try {
            currentInput = eval(currentInput);
            display.value = currentInput;
        } catch (error) {
            display.value = 'Error';
        }
    }
});

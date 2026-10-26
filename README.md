# Experiment No. 4

## Title: Program to Create a Website Using HTML, CSS and JavaScript

## 1. Program Code

**File Name: index.html**

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">

    <title>My First Website</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f4f4f4;
        }

        header {
            background: #0077cc;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background: #333;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 15px;
            text-decoration: none;
            font-size: 18px;
        }

        nav a:hover {
            color: #00e6e6;
        }

        .container {
            padding: 30px;
        }

        button {
            padding: 12px 20px;
            background: #0077cc;
            color: white;
            border: none;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
        }

        button:hover {
            background: #005fa3;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
        }
    </style>
</head>

<body>

    <header>
        <h1>Welcome to My Website</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </nav>

    <div class="container">

        <h2>Hello User!</h2>

        <p>
            This is a simple website created using
            HTML, CSS, and JavaScript.
        </p>

        <button onclick="showMessage()">
            Click Me
        </button>

        <p id="output"
           style="margin-top:20px;
                  font-size:18px;
                  color:#0077cc;">
        </p>

    </div>

    <footer>
        <p>© 2026 My Website | Designed by You</p>
    </footer>

    <script>
        function showMessage() {

            document.getElementById("output").innerHTML =
                "You clicked the button! JavaScript is working.";
        }
    </script>

</body>
</html>
```

## 2. Aim

To design and develop a simple website using HTML, CSS, and JavaScript and execute it using the Live Server extension in Visual Studio Code.

## 3. Theory

- **HTML:** Defines the structure of a webpage.
- **CSS:** Adds colours, fonts, backgrounds, and layouts.
- **JavaScript:** Provides interactive functionality.
- **VS Code:** A code editor used for web development.
- **Live Server:** Runs the website in a browser and automatically refreshes it.

## 4. Steps to Execute

1. Install Visual Studio Code.
2. Install the Live Server extension.
3. Create a project folder.
4. Create a file named `index.html`.
5. Paste the HTML, CSS, and JavaScript code.
6. Save the file.
7. Right-click and select **Open with Live Server**.
8. Click the button to test the JavaScript functionality.

## 5. Output

The webpage displays:

- Welcome to My Website
- Navigation links: Home, About, Services, Contact
- Hello User!
- Click Me button

After clicking the button:

```text
You clicked the button! JavaScript is working.
```

## 6. Conclusion

Thus, a simple interactive website was successfully developed using HTML, CSS, and JavaScript and executed using Live Server.

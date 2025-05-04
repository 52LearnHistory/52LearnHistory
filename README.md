- 👋 Hi, I’m @52LearnHistory
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
52LearnHistory/52LearnHistory is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Free Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f8ff;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
        }
        h1 {
            margin: 0;
        }
        .container {
            padding: 20px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Free Website! 🚀</h1>
    </header>
    <div class="container">
        <p>This is a simple webpage hosted for free on GitHub Pages.</p>
        <button onclick="showMessage()">Click Me!</button>
        <p id="demo"></p>
    </div>

    <script>
        function showMessage() {
            document.getElementById("demo").innerHTML = "Hello! You clicked the button! 😊";
        }
    </script>
</body>
</html>

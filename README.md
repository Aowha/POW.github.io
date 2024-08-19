<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Powaret Rurkrai</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap');

        body {
            background: url('https://cdn.pixabay.com/photo/2016/12/28/09/31/black-hole-1938197_1280.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #e1e1e6;
            font-family: 'Orbitron', sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .container {
            text-align: center;
            border: 3px solid #a29bfe;
            padding: 20px;
            width: 90%;
            max-width: 600px;
            background-color: rgba(32, 0, 44, 0.9);
            border-radius: 15px;
            box-shadow: 0 0 20px #a29bfe;
        }

        h1 {
            color: #a29bfe;
            font-size: 3em;
            margin-bottom: 10px;
            text-transform: uppercase;
            letter-spacing: 2px;
            animation: glitch 1s infinite;
        }

        p {
            font-size: 1.2em;
            margin: 10px 0;
        }

        .contact-info {
            margin-top: 20px;
            font-size: 1em;
            background-color: #2d3436;
            padding: 10px;
            border-radius: 10px;
            border: 1px solid #6c5ce7;
        }

        .contact-info a {
            color: #a29bfe;
            text-decoration: none;
            font-weight: bold;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        .buttons {
            margin-top: 20px;
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            margin: 10px;
            font-size: 1em;
            color: #fff;
            background-color: #6c5ce7;
            border: none;
            border-radius: 5px;
            text-transform: uppercase;
            text-decoration: none;
            box-shadow: 0 0 10px #6c5ce7;
            transition: background-color 0.3s, box-shadow 0.3s;
        }

        .button:hover {
            background-color: #a29bfe;
            box-shadow: 0 0 15px #a29bfe;
        }

        @keyframes glitch {
            0% { transform: translate(0); }
            20% { transform: translate(-2px, 2px); }
            40% { transform: translate(-2px, -2px); }
            60% { transform: translate(2px, 2px); }
            80% { transform: translate(2px, -2px); }
            100% { transform: translate(0); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Powaret Rurkrai</h1>
        <p>Welcome to my personal webpage. Let's connect!</p>
        <div class="contact-info">
            <p>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
            <p>Phone: <a href="tel:+1234567890">+1 234 567 890</a></p>
        </div>
        <div class="buttons">
            <a href="https://yourportfolio.com" class="button">Portfolio</a>
            <a href="https://linkedin.com/in/yourprofile" class="button">LinkedIn</a>
            <a href="https://github.com/yourgithub" class="button">GitHub</a>
        </div>
    </div>
</body>
</html>
12:35 PM 8/19/2024

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
            max-width: 400px; /* Adjusted for mobile devices */
            background-color: rgba(32, 0, 44, 0.9);
            border-radius: 15px;
            box-shadow: 0 0 20px #a29bfe;
        }

        h1 {
            color: #a29bfe;
            font-size: 2.5em; /* Slightly smaller for better readability on mobile */
            margin-bottom: 10px;
            text-transform: uppercase;
            letter-spacing: 2px;
            animation: glitch 1s infinite;
        }

        p {
            font-size: 1.1em; /* Adjusted for mobile readability */
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
            word-wrap: break-word; /* Ensures long text doesn't overflow */
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        .buttons {
            margin-top: 20px;
        }

        .button {
            display: block;
            padding: 10px 20px;
            margin: 10px auto;
            font-size: 1em;
            color: #fff;
            background-color: #6c5ce7;
            border: none;
            border-radius: 5px;
            text-transform: uppercase;
            text-decoration: none;
            box-shadow: 0 0 10px #6c5ce7;
            transition: background-color 0.3s, box-shadow 0.3s;
            width: 80%; /* Adjusted for mobile */
        }

        .button:hover {
            background-color: #a29bfe;
            box-shadow: 0 0 15px

# BIRTHDAY.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Ratna!</title>
    <style>
        body {
            background: url('https://www.transparenttextures.com/patterns/balloons.png'); /* Balloon Pattern */
            background-color: #fbe5d6; /* Pastel background color */
            background-size: cover;
            font-family: 'Arial', sans-serif;
            color: #fff;
            text-align: center;
            padding: 50px;
            overflow-x: hidden;
        }

        h1 {
            font-size: 50px;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: #ffb6b6; /* Pastel pink */
            background: rgba(255, 255, 255, 0.7);
            display: inline-block;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }

        p {
            font-size: 22px;
            line-height: 1.6;
            margin-top: 20px;
            background: rgba(255, 255, 255, 0.8);
            display: inline-block;
            padding: 15px;
            border-radius: 8px;
            max-width: 600px;
            margin: 30px auto;
            color: #fce3d8; /* Light pastel yellow */
        }

        .highlight {
            color: #ffeb3b; /* Highlight color in bright yellow */
            font-weight: bold;
        }

        .balloons {
            margin: 20px auto;
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        .balloon {
            width: 100px;
            height: 150px;
            border-radius: 50%;
            background: #ffb6b6; /* Pastel pink */
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 20px;
            font-weight: bold;
            color: #fff;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }

        .balloon:nth-child(2) {
            background: #ffeb3b; /* Yellow balloon */
        }

        .cake {
            margin-top: 30px;
            width: 200px;
            height: auto;
        }

        .footer {
            margin-top: 40px;
            font-size: 18px;
            background-color: rgba(255, 255, 255, 0.7);
            padding: 10px;
            border-radius: 5px;
        }

        .button {
            background-color: #ffb6b6; /* Pastel pink */
            color: #fff;
            padding: 12px 30px;
            border-radius: 30px;
            font-size: 18px;
            text-decoration: none;
            display: inline-block;
            margin-top: 30px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            transition: background-color 0.3s;
        }

        .button:hover {
            background-color: #fce3d8; /* Light pastel yellow */
        }

        audio {
            display: none; /* Hide the audio player */
        }
    </style>
</head>
<body>
    <!-- Background Music -->
    <audio autoplay loop>
        <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    <h1>Happy Birthday Ratna!</h1>

    <!-- Balloons -->
    <div class="balloons">
        <div class="balloon">Ratna</div>
        <div class="balloon">22 Years</div>
    </div>

    <!-- Cake Image -->
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6d/Birthday_cake_with_candles.png" alt="Birthday Cake" class="cake">

    <p>
        On your special day, I just wanted to take a moment to tell you how much you mean to me. You are my <span class="highlight">favorite coder</span>, the one who makes every challenge seem solvable and every problem a little bit easier. You’re the <span class="highlight">algorithm</span> that keeps me going, the bug-fixer of my world, and the one who makes my life feel like the most amazing project ever. 🖥️❤️
    </p>

    <p>
        Here's to another year of <span class="highlight">success</span>, <span class="highlight">love</span>, and <span class="highlight">endless adventure</span> together. May all your dreams compile into reality with no errors, and may your heart always be filled with joy. I love you more than all the lines of code in the world. 😘
    </p>

    <a href="https://www.github.com" class="button">Let’s code our future together!</a>

    <div class="footer">
        Wishing you the best birthday ever, Ratna. 💻🎉
    </div>
</body>
</html>

# BIRTHDAY.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Ratna!</title>
    <style>
        body {
            background-color: #000; /* Black background for dramatic effect */
            font-family: 'Poppins', sans-serif;
            color: #fff;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }

        .container {
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            position: relative;
        }

        h1 {
            font-size: 4rem;
            font-weight: bold;
            color: #ff6b81; /* Vibrant pink */
            margin-bottom: 20px;
            text-shadow: 3px 3px 8px rgba(255, 107, 129, 0.5);
        }

        .message {
            font-size: 1.5rem;
            line-height: 1.8;
            max-width: 800px;
            margin: 20px auto;
            background: rgba(0, 0, 0, 0.8);
            padding: 20px;
            border-radius: 15px;
            border: 2px solid #f9a825; /* Golden yellow border */
            color: #e3f2fd; /* Light blue text */
        }

        .highlight {
            color: #f9a825; /* Golden yellow highlight */
            font-weight: bold;
        }

        .balloons {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            z-index: -1;
            background: url('https://i.imgur.com/Z4Ry4Ve.png') no-repeat center top;
            background-size: cover;
            opacity: 0.6;
        }

        .cake {
            width: 300px;
            height: auto;
            margin: 20px 0;
            filter: drop-shadow(0 5px 15px rgba(255, 255, 255, 0.2));
        }

        .button {
            background-color: #ff6b81; /* Pink button */
            color: #fff;
            font-size: 1.2rem;
            font-weight: bold;
            text-decoration: none;
            padding: 15px 30px;
            border-radius: 25px;
            margin-top: 30px;
            box-shadow: 0 4px 15px rgba(255, 107, 129, 0.4);
            transition: transform 0.3s, background-color 0.3s;
        }

        .button:hover {
            transform: scale(1.1);
            background-color: #f9a825; /* Golden yellow hover */
        }

        footer {
            margin-top: 40px;
            font-size: 1rem;
            color: #bbb;
        }

        audio {
            display: none; /* Hide the audio player */
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Balloons in the background -->
        <div class="balloons"></div>

        <!-- Title -->
        <h1>Happy Birthday Ratna!</h1>

        <!-- Cake Image -->
        <img src="https://i.imgur.com/ZrIptAA.png" alt="Birthday Cake" class="cake">

        <!-- Message -->
        <div class="message">
            <p>
                Dear Ratna, on your <span class="highlight">22nd birthday</span>, I just want you to know how much you mean to me. 
                You’re the <span class="highlight">coder</span> who fills my life with endless joy, the <span class="highlight">algorithm</span> that keeps my heart running, 
                and the bug-fixer of all my worries. May your dreams compile flawlessly and your happiness never encounter an error. ❤️
            </p>
        </div>

        <!-- Button -->
        <a href="https://github.com/" class="button">Let’s code our future together!</a>

        <!-- Footer -->
        <footer>
            Wishing you a birthday as amazing as you are. 💻🎉
        </footer>

        <!-- Background Music -->
        <audio autoplay loop>
            <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
    </div>
</body>
</html>


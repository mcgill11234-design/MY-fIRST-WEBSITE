<!DOCTYPE html>

<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Custom Page</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            background-image: url('bowtie.jpg');
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            font-family: 'Poppins', sans-serif;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            position: relative;
            color: #000;
        }

        h1 {
            font-family: 'Arial Black', sans-serif;
            color: hotpink;
            text-align: center;
            text-shadow: 2px 2px 5px #ffc0cb;
            margin: 0;
        }

        p {
            font-size: 15px;
            text-align: center;
            text-shadow: 1px 1px 3px lightgrey;
            margin: 20px;
        }

        .bottom-left {
            position: absolute;
            bottom: 0;
            left: 0;
        }

        .bottom-right {
            position: absolute;
            bottom: 0;
            right: 0;
            border-radius: 15px;
            box-shadow: 0 0 15px #c71585;
        }

        .audio-container {
            position: absolute;
            bottom: 10px;
            left: 50%;
            transform: translateX(-50%);
        }
    </style>

</head>

<body>

    <h1>Happy Birthday!</h1>
    <p>
        🎉✨ Happy Birthday, Andrea! 🎂💖<br>
        May your special day be filled with love, <br>joy, and countless blessings.<br> 🙏🌸 May God continue to guide
        your
        steps, bless
        your heart,<br> and fulfill all the desires of your soul.</br>

    </p>
    <p>
        For I know the plans I have for you,<br>" declares the Lord, "<br>plans to prosper you and not to harm you,<br>
        plans to
        give you
        hope and a future.<br>
        Jeremiah 29:11 📖✨
        </br>
    </p>

    <img src="Hello.gif" alt="GIF Image" class="bottom-left">

    <img src="Drea.jpg" alt="Rounded Shadow Image" class="bottom-right" width="200">

    <div class="audio-container">
        <audio controls>
            <source src="Happy Birthday (Piano Version).mp3" type="audio/mpeg">

        </audio>
    </div>

</body>

</html>

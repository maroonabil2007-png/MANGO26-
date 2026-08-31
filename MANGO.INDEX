<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Love ❤️</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            min-height: 100vh;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #ff4b6e, #ff8fab, #ffc2d1);
        }

        /* Main Card */
        .card {
            position: relative;
            z-index: 10;
            width: 420px;
            padding: 45px 35px;
            text-align: center;

            background: rgba(255, 255, 255, 0.2);
            border: 2px solid rgba(255, 255, 255, 0.4);
            border-radius: 30px;

            backdrop-filter: blur(15px);

            box-shadow:
                0 20px 50px rgba(120, 0, 40, 0.3);

            color: white;
        }

        /* Big Heart */
        .big-heart {
            font-size: 90px;
            animation: heartbeat 1.2s infinite;
            filter: drop-shadow(0 5px 10px rgba(100, 0, 30, 0.3));
        }

        /* Title */
        h1 {
            margin: 15px 0;
            font-size: 48px;
            letter-spacing: 2px;
            text-shadow: 0 4px 10px rgba(100, 0, 30, 0.3);
        }

        /* Text */
        p {
            font-size: 18px;
            line-height: 1.7;
        }

        .special {
            margin-top: 15px;
            font-size: 22px;
            font-weight: bold;
        }

        /* Button */
        button {
            margin-top: 25px;
            padding: 14px 32px;

            border: none;
            border-radius: 50px;

            background: white;
            color: #ff416c;

            font-size: 17px;
            font-weight: bold;

            cursor: pointer;

            transition: 0.3s;

            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.2);
        }

        button:hover {
            transform: scale(1.1);
            background: #ff416c;
            color: white;
        }

        /* Hidden Message */
        #message {
            margin-top: 20px;
            font-size: 18px;
            font-weight: bold;
        }

        /* Floating Hearts */
        .hearts span {
            position: absolute;
            bottom: -60px;

            font-size: 30px;

            animation: floatUp 8s linear infinite;

            opacity: 0;
        }

        .hearts span:nth-child(1) {
            left: 5%;
            animation-delay: 0s;
        }

        .hearts span:nth-child(2) {
            left: 15%;
            animation-delay: 2s;
        }

        .hearts span:nth-child(3) {
            left: 30%;
            animation-delay: 4s;
        }

        .hearts span:nth-child(4) {
            left: 45%;
            animation-delay: 1s;
        }

        .hearts span:nth-child(5) {
            left: 60%;
            animation-delay: 3s;
        }

        .hearts span:nth-child(6) {
            left: 75%;
            animation-delay: 5s;
        }

        .hearts span:nth-child(7) {
            left: 90%;
            animation-delay: 6s;
        }

        /* Heartbeat */
        @keyframes heartbeat {
            0%, 100% {
                transform: scale(1);
            }

            25% {
                transform: scale(1.2);
            }

            50% {
                transform: scale(1);
            }

            75% {
                transform: scale(1.2);
            }
        }

        /* Floating Animation */
        @keyframes floatUp {
            0% {
                bottom: -60px;
                opacity: 0;
                transform: translateX(0) rotate(0deg);
            }

            20% {
                opacity: 1;
            }

            80% {
                opacity: 1;
            }

            100% {
                bottom: 110vh;
                opacity: 0;
                transform: translateX(-100px) rotate(360deg);
            }
        }

        /* Mobile */
        @media (max-width: 500px) {
            .card {
                width: 90%;
                padding: 35px 20px;
            }

            .big-heart {
                font-size: 70px;
            }

            h1 {
                font-size: 38px;
            }

            p {
                font-size: 16px;
            }
        }
    </style>
</head>

<body>

    <!-- Floating Hearts -->
    <div class="hearts">
        <span>❤️</span>
        <span>💕</span>
        <span>💖</span>
        <span>💗</span>
        <span>💘</span>
        <span>💞</span>
        <span>❤️</span>
    </div>

    <!-- Love Card -->
    <div class="card">

        <div class="big-heart">
            ❤️
        </div>

        <h1> YOUANA MY Love</h1>

        <p>
            You are the reason my heart smiles every day.
            Life is more beautiful when I have you by my side.
        </p>

        <p class="special">
            I Love You Forever ❤️
        </p>

        <button onclick="showMessage()">
            Click Me 💕
        </button>

        <div id="message"></div>

    </div>

    <script>
        function showMessage() {
            document.getElementById("message").innerHTML =
                "You will always have a special place in my heart. ❤️💕";
        }
    </script>

</body>
</html>

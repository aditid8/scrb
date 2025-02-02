<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Joyful Web Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom, #e0f7fa, #b2ebf2);
            text-align: center;
            padding: 50px;
            position: relative;
            overflow: hidden;
        }
        button {
            margin: 10px;
            padding: 15px 30px;
            font-size: 18px;
            cursor: pointer;
            background-color: #81d4fa;
            border: none;
            border-radius: 25px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.2s;
        }
        button:hover {
            transform: scale(1.05);
        }
        .message {
            display: none;
            margin-top: 20px;
            font-size: 20px;
            color: #333;
        }
        .balloon {
            position: absolute;
            width: 50px;
            height: 70px;
            background-color: #81d4fa;
            border-radius: 50px 50px 0 0;
            animation: float 3s ease-in-out infinite;
        }
        @keyframes float {
            0% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0); }
        }
    </style>
</head>
<body>
    <h1>A YEAR OF MOTHERHOOD: A BEAUTIFUL JOURNEY OF LOVE, JOY & ENDLESS HUGS! 💖👶</h1>
    <h2>Welcome to the Joyful Web Page!</h2>
    <button onclick="toggleMessage(1)">Toggle Message 1</button>
    <button onclick="toggleMessage(2)">Toggle Message 2</button>
    <button onclick="toggleMessage(3)">Toggle Message 3</button>
    <button onclick="toggleMessage(4)">Toggle Message 4</button>
    <button onclick="toggleMessage(5)">Toggle Message 5</button>

    <div id="message1" class="message">A Year of Love & Joy! 💖 One year of endless cuddles, sleepless nights, and boundless love! Wishing you warmth, happiness, and beautiful moments as you continue this incredible journey of motherhood. 🌸✨</div>
    <div id="message2" class="message">Embracing Motherhood with Love! 🌿 From tiny giggles to first words, you've nurtured a little soul with pure love! May your heart always be as full as your little one’s laughter. 💕👶</div>
    <div id="message3" class="message">To a Beautiful Mama! 🌟 A year of being a wonderful mother—nurturing, loving, and glowing with happiness! May your days be filled with love, joy, and sweet baby hugs! 🤗💛</div>
    <div id="message4" class="message">Cherishing Every Moment! 🍼 One year of love, learning, and magical motherhood! May your journey be filled with countless cherished memories and happiness beyond measure. 💞🌈</div>
    <div id="message5" class="message">A Mother’s Love Knows No Bounds! 🌻 Through every challenge and every smile, you’ve embraced motherhood with grace and strength. Wishing you endless joy and warm cuddles always! ❤️🌟</div>

    <script>
        function toggleMessage(num) {
            const message = document.getElementById(`message${num}`);
            if (message.style.display === "none" || message.style.display === "") {
                message.style.display = "block";
            } else {
                message.style.display = "none";
            }
        }
    </script>

    <!-- Balloons -->
    <div class="balloon" style="left: 10%; top: 20%;"></div>
    <div class="balloon" style="left: 30%; top: 10%;"></div>
    <div class="balloon" style="left: 50%; top: 25%;"></div>
    <div class="balloon" style="left: 70%; top: 15%;"></div>
    <div class="balloon" style="left: 90%; top: 30%;"></div>
</body>
</html>

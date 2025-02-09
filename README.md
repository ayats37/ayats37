<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aya's Page</title>
    <style>
        @keyframes floatMove {
            0% {
                transform: translateY(0) rotate(0deg);
                opacity: 0;
            }
            25% {
                transform: translateY(-10px) rotate(-5deg);
                opacity: 0.7;
            }
            50% {
                transform: translateY(0) rotate(5deg);
                opacity: 1;
            }
            75% {
                transform: translateY(10px) rotate(-5deg);
                opacity: 0.7;
            }
            100% {
                transform: translateY(0) rotate(0deg);
                opacity: 1;
            }
        }

        .anime-text {
            color: red;
            font-size: 30px;
            font-weight: bold;
            animation: floatMove 3s ease-in-out infinite;
        }
    </style>
</head>
<body>

    <p class="anime-text">Hi there, I'm Aya Touirass! 👋</p>
    
    <p align="center">
        <a href="https://github.com/oakoudad/badge42">
            <img src="https://badge.mediaplus.ma/black/taya" alt="taya's 42 stats" />
        </a>
    </p>

</body>
</html>



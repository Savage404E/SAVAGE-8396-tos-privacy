<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>SAVAGE#8396 Bot Privacy Policy and Terms of Service</title>
    <style>
        body {
            background: #222;
            color: #eee;
            font-family: 'Segoe UI', 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }
        /* Background word styling */
        .bg-word {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%) rotate(-60deg);
            font-size: 14rem; /* Increased size */
            font-weight: bold;
            color: rgba(160, 89, 255, 0.18); /* Increased opacity */
            letter-spacing: 2rem;
            user-select: none;
            pointer-events: none;
            z-index: 0;
            animation: bgWordAnim 6s infinite alternate;
            text-shadow:
                0 0 80px #a259ff,
                0 0 160px #00bcd4,
                0 0 24px #fff; /* Added white glow */
        }
        @keyframes bgWordAnim {
            0% { filter: blur(1px); opacity: 0.18; }
            50% { filter: blur(0px); opacity: 0.25; }
            100% { filter: blur(1px); opacity: 0.18; }
        }
        .header {
            text-align: center;
            padding: 2rem 1rem 1rem 1rem;
            font-size: 2rem;
            font-weight: bold;
            letter-spacing: 1px;
            background: linear-gradient(90deg, #00bcd4 0%, #ff4081 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        .container {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 80vh;
            position: relative;
            z-index: 1;
        }
        .links {
            background: rgba(40,40,40,0.85);
            padding: 2rem 3rem;
            border-radius: 16px;
            box-shadow: 0 4px 24px rgba(0,0,0,0.3);
            text-align: center;
            position: relative;
            z-index: 1;
        }
        .links a {
            color: #00bcd4;
            text-decoration: none;
            font-size: 1.2rem;
            margin: 0 0.5rem;
            transition: color 0.2s, text-shadow 0.2s;
            text-shadow: 0 0 8px #00bcd4;
        }
        .links a:hover {
            color: #ff4081;
            text-shadow: 0 0 12px #ff4081;
        }
        /* Neon light effect */
        .neon {
            position: absolute;
            top: 0; left: 0; width: 100%; height: 100%;
            pointer-events: none;
            z-index: 0;
        }
        .neon span {
            position: absolute;
            border-radius: 50%;
            filter: blur(32px);
            opacity: 0.6;
            animation: neonMove 6s infinite alternate;
        }
        .neon .blue {
            background: #00bcd4;
            width: 180px; height: 180px;
            left: 10%; top: 10%;
            animation-delay: 0s;
        }
        .neon .pink {
            background: #ff4081;
            width: 120px; height: 120px;
            right: 15%; top: 60%;
            animation-delay: 2s;
        }
        .neon .purple {
            background: #a259ff;
            width: 100px; height: 100px;
            left: 70%; top: 30%;
            animation-delay: 1s;
        }
        @keyframes neonMove {
            0% { transform: translateY(0) scale(1);}
            100% { transform: translateY(40px) scale(1.1);}
        }
    </style>
</head>
<body>
    <div class="bg-word">SAVAGE</div>
    <div class="header">
        SAVAGE#8396 Bot Privacy Policy and Terms of Service
    </div>
    <div class="container">
        <div class="links">
            <p>This is the first link to <a href="privacy.html">Privacy Policy</a>.</p>
            <p>This is the second link to <a href="tos.html">Terms of Service</a>.</p>
        </div>
        <div class="neon">
            <span class="blue"></span>
            <span class="pink"></span>
            <span class="purple"></span>
        </div>
    </div>
</body>
</html>

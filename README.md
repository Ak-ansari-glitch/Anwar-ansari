<!DOCTYPE html>
<html>
<head>
    <style>
        body { background-color: #1a1a1a; color: #ff4d6d; text-align: center; font-family: 'Arial', sans-serif; }
        .rose { font-size: 100px; margin-top: 20vh; animation: bloom 3s ease-in-out; }
        @keyframes bloom {
            0% { transform: scale(0); opacity: 0; }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); opacity: 1; }
        }
        .message { opacity: 0; animation: fadeIn 2s forwards 2.5s; margin-top: 20px; }
        @keyframes fadeIn { to { opacity: 1; } }
    </style>
</head>
<body>
    <div class="rose">🌹</div>
    <div class="message">
        <h1>Happy Rose Day, [Name]!</h1>
        <p>A digital rose for a girl who’s one in a million.</p>
    </div>
</body>
</html>

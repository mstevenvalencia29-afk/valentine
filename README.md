<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Crismarie!</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background: linear-gradient(135deg, #fce4ec 0%, #f8bbd0 100%);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #880e4f;
            text-align: center;
        }

        .card {
            background: white;
            padding: 3rem;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            max-width: 400px;
            margin: 20px;
            border: 2px solid #f06292;
            animation: fadeIn 1.5s ease-out;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: #d81b60;
        }

        .name {
            font-size: 3rem;
            font-weight: bold;
            display: block;
            color: #ad1457;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        }

        p {
            font-size: 1.2rem;
            line-height: 1.6;
        }

        .cake {
            font-size: 4rem;
            margin: 20px 0;
        }

        .button {
            display: inline-block;
            margin-top: 25px;
            padding: 12px 25px;
            background-color: #d81b60;
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            transition: transform 0.3s ease;
        }

        .button:hover {
            transform: scale(1.1);
            background-color: #ad1457;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Floating balloon emojis */
        .balloons {
            position: absolute;
            width: 100%;
            height: 100%;
            overflow: hidden;
            z-index: -1;
        }
    </style>
</head>
<body>

    <div class="card">
        <div class="cake">🎂</div>
        <h1>Happy Birthday,</h1>
        <span class="name">Crismarie!</span>
        <p>Wishing you a day filled with laughter, love, and all the cake you can eat. May this year be your brightest one yet!</p>
        <a href="#" class="button" onclick="alert('Sending you a huge virtual hug! 🤗')">Celebrate!</a>
    </div>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nadjad Med Animation Time</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        /* Body Styling */
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background: linear-gradient(135deg, #000000, #1c1c1c);
            color: white;
            text-align: center;
            padding: 20px;
        }

        /* Title Styling */
        h1 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            animation: fadeIn 1s ease-in-out;
            color: #ffd700;
            text-shadow: 0 0 15px rgba(255, 215, 0, 0.8);
        }

        p {
            max-width: 600px;
            line-height: 1.6;
            margin-bottom: 20px;
            color: #d3d3d3;
        }

        /* Button Styling */
        .button-container {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .btn {
            padding: 12px 24px;
            font-size: 18px;
            font-weight: bold;
            color: white;
            background: linear-gradient(135deg, #8a2be2, #4b0082);
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: transform 0.3s ease, background 0.3s ease, box-shadow 0.3s ease;
            text-decoration: none;
            display: inline-block;
            width: 200px;
            text-align: center;
            box-shadow: 0 0 10px rgba(138, 43, 226, 0.8);
        }

        .btn:hover {
            transform: scale(1.1);
            background: linear-gradient(135deg, #9932cc, #8b008b);
            box-shadow: 0 0 20px rgba(147, 112, 219, 1);
        }

        /* Fade-in Animation */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>

    <h1>Welcome to Nadjad's World!</h1>
    <p>
        Welcome to Nadjad's world!
        A channel full of fun and creativity, where hilarious animation meets video games and epic stories! 🌟
        Here, you will find:
        🎮 Exciting gaming adventures with thrilling challenges and cool games.
        🎬 Unique animations telling funny and action-packed stories.
        🛡️ Epic knight tales that take you to worlds of fantasy and magic.
        📖 Personal stories that will make you laugh, inspire you, and amaze you!
        Subscribe now and join the creative and fun family – the best is yet to come! 🚀✨
        #Nadjad_Creativity_And_Imagination
    </p>
    
    <div class="button-container">
        <a href="https://www.youtube.com/@NadjadouMed" target="_blank" class="btn">Go to YouTube</a>
        <a href="https://scratch.mit.edu/users/NADJAD242/" target="_blank" class="btn">Go to Scratch</a>
        <a href="https://discord.gg/NCpzGmT9rK" target="_blank" class="btn">Join Discord</a>
    </div>

</body>
</html>

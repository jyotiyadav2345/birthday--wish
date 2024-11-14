<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday [Friend's Name]!</title>
    <style>
        /* General Body Styling */
        body {
            background: #FFDEE9;
            color: #4A148C;
            font-family: 'Arial', sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            overflow: hidden;
            position: relative;
        }

        /* Header (HAPPY BIRTHDAY) */
        h1 {
            font-size: 4em;
            margin-top: 100px;
            text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.1);
            color: #FF4081;
        }

        /* Sub-heading for a fun intro message */
        h2 {
            font-size: 1.8em;
            color: #F50057;
        }

        /* Styling for paragraph text */
        p {
            font-size: 1.3em;
            color: #6200EA;
            margin-top: 20px;
        }

        /* Confetti Animation */
        .confetti {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            pointer-events: none;
            z-index: 10;
            animation: confettiFall 5s infinite;
        }

        @keyframes confettiFall {
            0% {
                opacity: 1;
                transform: translateY(-100%);
            }
            100% {
                opacity: 0;
                transform: translateY(100%);
            }
        }

        /* Surprise Button Styling */
        button {
            background-color: #FF4081;
            color: white;
            font-size: 1.5em;
            padding: 15px 30px;
            border: none;
            border-radius: 10px;
            margin-top: 30px;
            cursor: pointer;
            transition: background 0.3s;
        }

        button:hover {
            background-color: #D500F9;
        }

        /* Additional Styling for Images/Content */
        .image-container {
            margin-top: 50px;
        }

        .birthday-image {
            max-width: 80%;
            height: auto;
            border-radius: 15px;
        }

        .message-container {
            margin-top: 40px;
            padding: 30px;
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        /* Audio/Sound Styling */
        .audio-container {
            margin-top: 40px;
        }
        
        .audio-container audio {
            border-radius: 10px;
        }

    </style>
</head>
<body>

    <!-- Confetti Animation -->
    <div class="confetti">
        <!-- You can insert your confetti gif here -->
        <img src="https://i.imgur.com/MTXUjxX.gif" alt="Confetti Animation" />
    </div>

    <!-- Main Title -->
    <h1>Happy Birthday, [Friend's Name]!</h1>

    <!-- Fun Birthday Intro -->
    <h2>Let’s Celebrate YOU! 🎉</h2>

    <!-- Personalized Birthday Message -->
    <p>Wishing you an amazing day filled with laughter, love, and endless happiness. 🎂🎁</p>

    <!-- Interactive Surprise Button -->
    <button onclick="surpriseMessage()">Click for a Surprise!</button>

    <!-- Surprise Message Function -->
    <script>
        function surpriseMessage() {
            alert("Surprise! 🎉 You're awesome! Have the best birthday ever!");
        }
    </script>

    <!-- Image Gallery Section -->
    <div class="image-container">
        <img src="https://via.placeholder.com/600x400?text=Your+Happy+Memories" class="birthday-image" alt="Birthday Image">
        <!-- Replace above image URL with your own images -->
    </div>

    <!-- Message Container (Optional Personal Message) -->
    <div class="message-container">
        <h3>A Special Message Just for You!</h3>
        <p>"[Add your personal message here. Example: I’m so lucky to have you as a friend! Every moment with you is a treasure, and I can’t wait for more adventures together!]"</p>
    </div>

    <!-- Audio or Video Section (Optional) -->
    <div class="audio-container">
        <h3>🎶 Birthday Song Just for You!</h3>
        <audio controls>
            <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
    </div>

    <script>
        // Additional JS functionality can go here (if you want interactive games or animations)
    </script>

</body>
</html>

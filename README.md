<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fork Verification - Devil Crash V5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
            background-color: #121212;
            color: white;
        }
        .title {
            font-size: 50px;
            font-weight: bold;
            background: linear-gradient(90deg, #ff0000, #ff7300, #ffeb00, #00ff00, #00eaff, #0044ff, #9900ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            display: inline-block;
        }
        .btn {
            padding: 15px 25px;
            background-color: #25D366;
            color: white;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            border-radius: 5px;
            display: inline-block;
            margin: 10px;
            cursor: pointer;
        }
        .btn-youtube {
            background-color: #FF0000;
        }
        .hidden {
            display: none;
        }
    </style>
</head>
<body>

    <h1 class="title">🔥 DEVIL CRASH V5 🔥</h1>
    
    <h2>🔒 Follow WhatsApp & YouTube to Unlock Fork</h2>
    <p>To fork <strong>Devil Crash V5</strong>, you <strong>must follow both our WhatsApp Channel and YouTube Channel.</strong></p>

    <!-- WhatsApp Follow Button -->
    <a class="btn" href="https://whatsapp.com/channel/0029Vb2zlJP1CYoLCdr1k13f" target="_blank" onclick="followWhatsApp()">✅ Follow WhatsApp</a>

    <!-- YouTube Follow Button -->
    <a class="btn btn-youtube" href="https://www.youtube.com/@DEVIL-KING-STORE" target="_blank" onclick="followYouTube()">▶️ Follow YouTube</a>

    <br><br>

    <!-- Fork Button (Initially Hidden) -->
    <a id="forkBtn" class="btn hidden" href="https://github.com/Devilxking789/DEVIL-CRASH-V5/fork">🚀 Click Here to Fork</a>

    <script>
        let whatsappFollowed = false;
        let youtubeFollowed = false;

        function followWhatsApp() {
            whatsappFollowed = true;
            checkUnlock();
        }

        function followYouTube() {
            youtubeFollowed = true;
            checkUnlock();
        }

        function checkUnlock() {
            if (whatsappFollowed && youtubeFollowed) {
                setTimeout(() => {
                    document.getElementById("forkBtn").classList.remove("hidden");
                }, 3000); // Unlock Fork Button after 3 seconds if both are followed
            }
        }
    </script>

</body>
</html>

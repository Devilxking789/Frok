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
        .hidden {
            display: none;
        }
    </style>
</head>
<body>

    <h1>🔒 Follow WhatsApp Channel to Fork</h1>
    <p>To fork **Devil Crash V5**, you **must follow our WhatsApp Channel first.**</p>

    <!-- WhatsApp Follow Button -->
    <a class="btn" href="https://whatsapp.com/channel/0029Vb2zlJP1CYoLCdr1k13f" target="_blank" onclick="unlockFork()">✅ Follow & Unlock Fork</a>

    <br><br>

    <!-- Auto Redirect Fork Button -->
    <a id="forkBtn" class="btn hidden" href="https://github.com/Devilxking789/DEVIL-CRASH-V5/fork">🚀 Click Here to Fork</a>

    <script>
        function unlockFork() {
            setTimeout(() => {
                document.getElementById("forkBtn").classList.remove("hidden");
                document.getElementById("forkBtn").click(); // Auto-click fork after unlocking
            }, 5000); // Wait 5 seconds before showing and auto-clicking the fork button
        }
    </script>

</body>
</html>

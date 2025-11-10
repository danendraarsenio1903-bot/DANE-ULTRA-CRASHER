# DANE-ULTRA-CRASHER
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>☠️𝘿𝘼𝙉𝙀 𝘾𝙍𝘼𝙎𝙃𝙀𝙍 𝙐𝙇𝙏𝙍𝘼☠️</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: black;
            color: red;
            text-align: center;
            padding: 20px;
        }
        .container {
            width: 80%;
            margin: auto;
        }
        input[type="text"] {
            padding: 10px;
            margin: 10px 0;
            width: 100%;
            box-sizing: border-box;
            background-color: #333;
            color: white;
            border: none;
        }
        button {
            background-color: red;
            color: white;
            padding: 14px 20px;
            margin: 8px 0;
            border: none;
            cursor: pointer;
            width: 100%;
        }
        button:hover {
            opacity: 0.8;
        }
        .role {
            margin-top: 20px;
            font-weight: bold;
        }
        .popup {
            display: none;
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background-color: rgba(0, 0, 0, 0.8);
            color: white;
            padding: 20px;
            border-radius: 5px;
            z-index: 1000;
            width: 80%;
            max-width: 400px;
        }
        .popup p {
            margin: 0;
        }
        .close-button {
            position: absolute;
            top: 10px;
            right: 10px;
            cursor: pointer;
            font-size: 20px;
            color: white;
        }
        select {
            padding: 10px;
            margin: 10px 0;
            width: 100%;
            box-sizing: border-box;
            background-color: #333;
            color: white;
            border: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>☠️𝘿𝘼𝙉𝙀 𝘾𝙍𝘼𝙎𝙃𝙀𝙍 𝙐𝙇𝙏𝙍𝘼☠️</h1>
        <div>Input Nomor</div>
        <input type="text" placeholder="628xxxxxx">
        <div>Blank Hard</div>
        <select id="blank-hard-select">
            <option value="fc-permanen">FC PERMANEN</option>
            <option value="delay-parah">DELAY PARAH</option>
            <option value="blank-hard">BLANK HARD</option>
        </select>
        <button onclick="showMessage()">SEND</button>
        <div class="role">ROLE: BUYER PERMANEN</div>

        <div id="popup" class="popup">
            <span class="close-button" onclick="closePopup()">x</span>
            <p>HALAMAN INI MENYATAKAN</p>
            <p>☠️𝙀𝙍𝙍𝙊𝙍 𝙏𝙀𝙇𝘼𝙃 𝘿𝙄 𝙆𝙄𝙍𝙄𝙈☠️</p>
            <p>DEV : DANEK</p>
        </div>
    </div>

    <script>
        function showMessage() {
            document.getElementById('popup').style.display = 'block';
        }

        function closePopup() {
            document.getElementById('popup').style.display = 'none';
        }
    </script>
</body>
</html>

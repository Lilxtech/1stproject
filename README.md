<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <titl> REGISTRATION PAGE </title>
    <style>
        body {
            background-color: black;
            color: white;
            text-align: center;
            font-family: Arial, sans-serif;
        }
        .container {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
            margin: 20px;
        }
        .icon {
            background: #222;
            padding: 20px;
            border-radius: 10px;
            cursor: pointer;
        }
        .icon img {
            width: 50px;
            height: 50px;
        }
        .bottom-nav {
            position: fixed;
            bottom: 0;
            width: 100%;
            display: flex;
            justify-content: space-around;
            background: #111;
            padding: 10px;
        }
        .bottom-nav img {
            width: 30px;
            height: 30px;
        }
    </style>
</head>
<body>

    <h1>HQ App</h1>

    <div class="container">
        <div class="icon" onclick="navigateTo('pak_services.html')">
            <img src="pak_services.png" alt="Pak e-Services">
            <p>ONLINE SERVICES</p>
        </div>
        <div class="icon" onclick="navigateTo('live_tv.html')">
            <img src="live_tv.png" alt="Live TV">
            <p>Live TV</p>
        </div>
        <div class="icon" onclick="navigateTo('chat.html')">
            <img src="chat.png" alt="Chatting">
            <p>Chatting</p>
        </div>
        <div class="icon" onclick="navigateTo('users.html')">
            <img src="users.png" alt="Users">
            <p>Users</p>
        </div>
        <div class="icon" onclick="navigateTo('tips.html')">
            <img src="tips.png" alt="Tips & Tricks">
            <p>Tips & Tricks</p>
        </div>
        <div class="icon" onclick="navigateTo('hacking.html')">
            <img src="hacking.png" alt="Hacking">
            <p>Hacking</p>
        </div>
        <div class="icon" onclick="navigateTo('tools.html')">
            <img src="tools.png" alt="Online Tools">
            <p>Online Tools</p>
        </div>
        <div class="icon" onclick="navigateTo('courses.html')">
            <img src="courses.png" alt="Free Courses">
            <p>Free Courses</p>
        </div>
        <div class="icon" onclick="navigateTo('digital_assets.html')">
            <img src="assets.png" alt="Digital Assets">
            <p>UPDATES</p>
        </div>
        <div class="icon" onclick="navigateTo('social.html')">
            <img src="social.png" alt="Social Media">
            <p>Our Social Media</p>
        </div>
    </div>

    <div class="bottom-nav">
        <img src="globe.png" alt="Web">
        <img src="whatsapp.png" alt="WhatsApp">
        <img src="home.png" alt="Home">
        <img src="chat.png" alt="Chat">
        <img src="telegram.png" alt="Telegram">
    </div>

    <script>
        function navigateTo(page) {
            window.location.href = page;
        }
    </script>

</body>
</html>

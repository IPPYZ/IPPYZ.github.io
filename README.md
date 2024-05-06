<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bio Page</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            height: 100vh;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            position: relative;
        }
        #video-background {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1; /* لجعل الفيديو في الخلفية */
        }
        .content {
            background: rgba(255, 255, 255, 0.7);
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            z-index: 1; /* لجعل النص والمحتوى أمام الفيديو */
        }
        .profile-pic {
            width: 150px;
            height: 150px;
            overflow: hidden;
            margin: 0 auto 20px;
            border-radius: 50%;
        }
        .profile-pic img {
            width: 150px;
            height: 150px;
            object-fit: cover;
            border-radius: 50%;
        }
    </style>
</head>
<body>
    <video id="video-background" autoplay loop muted>
        <source src="https://github.com/IPPYZ/IPPYZ.github.io/raw/main/Karl%20Kroenen%20%20Lay%20all%20your%20Love%20on%20me%20%23edit%20%23viral%20%234k%20%23dc%20%23hellboy%20%23aftereffects%20%23subscribe.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <audio id="audio-background" autoplay loop>
        <source src="https://github.com/IPPYZ/IPPYZ.github.io/raw/main/Karl%20Kroenen%20%20Lay%20all%20your%20Love%20on%20me%20%23edit%20%23viral%20%234k%20%23dc%20%23hellboy%20%23aftereffects%20%23subscribe.mp3" type="audio/mpeg">
        Your browser does not support the audio tag.
    </audio>
    <div class="content">
        <div class="profile-pic">
            <img src="https://img.freepik.com/premium-photo/arabic-calligraphy-wallpaper-wall-with-brown-background-old-paper-interlacing_430468-582.jpg?w=1480" alt="Your Profile Picture">
        </div>
        <h1>Welcome to My Bio Page!</h1>
        <p>This is where you can find all the information about me.</p>
        <p>Follow me on <a href="https://www.instagram.com/ippyz">Instagram</a>.</p>
    </div>
</body>
</html>

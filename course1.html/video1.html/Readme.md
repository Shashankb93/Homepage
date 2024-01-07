<html>
<head>
    <title>Video 1: Number System</title>
    <style>
        /* Add your own CSS style here */
    </style>
</head>
<body>
    <div id="header">
        <h1>Video 1: Number System</h1>
        <p>This video covers the basics of number system, such as types of numbers, divisibility rules, factors, multiples, prime numbers, and HCF and LCM. You will learn how to identify and classify different kinds of numbers and how to perform various operations on them.</p>
    </div>
    <div id="content">
        <div id="video-player">
            <h2>Video Player</h2>
            <p>Here you can watch the video lecture for number system. You can adjust the volume, speed, and quality of the video. You can also pause, resume, rewind, or fast-forward the video.</p>
            <video id="video" width="640" height="480" controls>
                <source src="video1.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </div>
        <div id="upload-videos">
            <h2>Upload Videos</h2>
            <p>Here you can upload your own video lectures for number system. This option is only available for the owner of the website. Please enter your username and password to access this feature.</p>
            <form action="login.php" method="post">
                <label for="username">Username:</label>
                <input type="text" id="username" name="username" required>
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>
                <input type="submit" value="Login" name="submit">
            </form>
            <!-- Add the code for uploading video files after the user is authenticated -->
        </div>
    </div>
    <div id="footer">
        <p>© 2024 Bank Exams Prep. All rights reserved.</p>
    </div>
</body>
</html>

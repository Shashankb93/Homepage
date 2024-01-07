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
        <div id="upload-files">
            <h2>Upload Files</h2>
            <p>Here you can upload your own files related to number system, such as notes, worksheets, solutions, or questions. You can also view and download the files uploaded by other users. Please make sure that your files are in PDF format and do not contain any inappropriate or irrelevant content.</p>
            <form action="upload.php" method="post" enctype="multipart/form-data">
                <label for="file">Select a PDF file to upload:</label>
                <input type="file" id="file" name="file" accept="application/pdf">
                <input type="submit" value="Upload" name="submit">
            </form>
            <table>
                <tr>
                    <th>File Name</th>
                    <th>File Size</th>
                    <th>File Description</th>
                    <th>Download Link</th>
                </tr>
                <!-- Add more rows here with the file details and download links -->
            </table>
        </div>
    </div>
    <div id="footer">
        <p>© 2024 Bank Exams Prep. All rights reserved.</p>
    </div>
</body>
</html>

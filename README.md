<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Page Title</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1 id="title">Page Title</h1>
    <img id="profile-img" src="profile.jpg" alt="Profile Image">
    <p id="caption">Caption for the image goes here.</p>
    <div id="content">
        <p>This is some content...</p>
        <p>More content goes here...</p>
    </div>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    text-align: center;
}

#title {
    color: #333;
}

#profile-img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    margin: 20px auto;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
}

#caption {
    color: #666;
}

#content {
    margin: 20px auto;
    padding: 20px;
    background-color: #f9f9f9;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
}

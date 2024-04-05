<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Welcome to Our Landing Page</h1>
        </div>
        <div class="content">
            <img src="profile.jpg" alt="Profile Image">
            <p class="caption">Caption for the image goes here.</p>
            <div class="paragraphs">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla vitae purus vel quam sollicitudin commodo. Nullam posuere est at magna vehicula fringilla. In hac habitasse platea dictumst. Sed at magna enim. Fusce faucibus tristique turpis vel vestibulum. Duis commodo urna id nisl luctus, eget cursus metus viverra.</p>
                <p>Proin non ligula nec enim tempor posuere. Fusce sit amet purus nec enim eleifend pellentesque. Donec dictum erat ac tortor pharetra, vitae faucibus risus vestibulum. Morbi vitae molestie sapien. In non arcu eleifend, aliquam metus eu, blandit est. Suspendisse non condimentum purus, nec feugiat nisi.</p>
            </div>
        </div>
    </div>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f8f8f8;
    margin: 0;
}

.container {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
}

.header {
    text-align: center;
    padding-bottom: 20px;
}

.header h1 {
    color: #333;
}

.content {
    text-align: center;
}

.content img {
    border-radius: 50%;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
    margin-bottom: 20px;
}

.caption {
    color: #666;
}

.paragraphs {
    text-align: justify;
    color: #333;
    line-height: 1.6;
}

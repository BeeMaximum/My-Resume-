<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Survey Form</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Survey Form</h1>
        <form id="survey-form">
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="age">Age:</label>
                <input type="number" id="age" name="age" required>
            </div>
            <div class="form-group">
                <label for="gender">Gender:</label>
                <select id="gender" name="gender" required>
                    <option value="">Select</option>
                    <option value="male">Male</option>
                    <option value="female">Female</option>
                    <option value="other">Other</option>
                </select>
            </div>
            <div class="form-group">
                <label for="feedback">Feedback:</label>
                <textarea id="feedback" name="feedback" rows="4" cols="50"></textarea>
            </div>
            <div class="form-group">
                <label>How did you hear about us?</label><br>
                <input type="radio" id="hear-website" name="hear" value="website">
                <label for="hear-website">Website</label><br>
                <input type="radio" id="hear-friend" name="hear" value="friend">
                <label for="hear-friend">Friend</label><br>
                <input type="radio" id="hear-advertisement" name="hear" value="advertisement">
                <label for="hear-advertisement">Advertisement</label>
            </div>
            <div class="form-group">
                <label>What services are you interested in?</label><br>
                <input type="checkbox" id="service-webdev" name="services" value="webdev">
                <label for="service-webdev">Web Development</label><br>
                <input type="checkbox" id="service-mobiledev" name="services" value="mobiledev">
                <label for="service-mobiledev">Mobile App Development</label><br>
                <input type="checkbox" id="service-design" name="services" value="design">
                <label for="service-design">Design Services</label>
            </div>
            <button type="submit">Submit</button>
        </form>
    </div>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
}

.container {
    max-width: 600px;
    margin: 0 auto;
    padding: 20px;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1 {
    text-align: center;
    color: #333;
}

.form-group {
    margin-bottom: 20px;
}

label {
    font-weight: bold;
}

input[type="text"],
input[type="email"],
input[type="number"],
textarea,
select {
    width: 100%;
    padding: 10px;
    border-radius: 5px;
    border: 1px solid #ccc;
}

input[type="radio"],
input[type="checkbox"] {
    margin-right: 10px;
}

button {
    display: block;
    width: 100%;
    padding: 10px;
    background-color: #4caf50;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

button:hover {
    background-color: #45a049;
}

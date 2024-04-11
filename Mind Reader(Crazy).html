<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mind Reader</title>
    <style>
        /* Centering the page */
        body {
            font-family: 'Arial', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background: linear-gradient(to bottom right, #4cb8c4, #3b9760); /* Gradient background */
        }

        /* Main content styles */
        .container {
            text-align: center;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Shadow effect */
        }

        /* Styling for the loading bar */
        #loadingBarContainer {
            display: none;
            width: 100%;
            height: 30px;
            background-color: #f0f0f0;
            border: 1px solid #ccc;
            margin-top: 20px;
            border-radius: 5px;
        }

        #loadingBar {
            height: 100%;
            background-color: #4caf50;
            width: 0%;
            border-radius: 5px;
            transition: width 5s linear; /* Animation duration */
        }

        /* Styling for the input box */
        input[type="number"] {
            width: 200px;
            padding: 10px;
            margin-top: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            outline: none;
        }

        /* Styling for the submit button */
        button {
            padding: 10px 20px;
            margin-top: 10px;
            background-color: #4cb8c4; /* Match the gradient color */
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease; /* Smooth transition */
        }

        button:hover {
            background-color: #3b9760; /* Darker shade on hover */
        }

        /* Styling for the popup message */
        .popup {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background-color: #fff; /* Solid white background */
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
            z-index: 999;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welcome to Mind Reader</h1>
        <p>Think of a number between 1 and 100.</p>
        <input type="number" id="userNumber" placeholder="Pick a number" onkeypress="handleKeyPress(event)">
        <button onclick="readMind()">Submit</button>

        <div id="loadingBarContainer">
            <div id="loadingBar"></div>
        </div>
    </div>

    <div id="popupResult" class="popup" style="display: none;">
        <p>Your number is <span id="userNumberResult"></span></p>
        <button onclick="goBack()">Go Back</button>
    </div>

    <script>
        // Function to handle Enter key press
        function handleKeyPress(event) {
            if (event.key === "Enter") {
                readMind();
            }
        }

        function readMind() {
            var userNumber = parseInt(document.getElementById("userNumber").value);

            // Check if the entered value is a number and between 1 and 100
            if (isNaN(userNumber) || userNumber < 1 || userNumber > 100) {
                alert("Please enter a valid number between 1 and 100.");
                return;
            }

            // Show the loading bar and start progress immediately
            document.getElementById("loadingBarContainer").style.display = "block";
            var loadingBar = document.getElementById("loadingBar");
            loadingBar.style.width = "0%";
            setTimeout(function() {
                // Set loading bar width to 100% after a slight delay
                loadingBar.style.width = "100%";
            }, 50); // A slight delay to ensure smooth transition

            // Simulate loading for 5 seconds (5000 milliseconds)
            setTimeout(function() {
                // Hide the loading bar
                document.getElementById("loadingBarContainer").style.display = "none";
                document.getElementById("popupResult").style.display = "block";
                document.getElementById("userNumberResult").innerText = userNumber;
            }, 5000);
        }

        function goBack() {
            // Hide the popup and reset input fields
            document.getElementById("popupResult").style.display = "none";
            document.getElementById("userNumber").value = "";
            document.getElementById("loadingBarContainer").style.display = "none";
        }
    </script>
</body>
</html>

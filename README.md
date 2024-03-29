<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Congratulations Virtual Gift Package</title>
    <style>
        /* CSS styling for the virtual gift package */
        body {
            background-color: #f8f8f8;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .gift-box {
            width: 150px;
            height: 150px;
            background-image: url('gift-box.png'); /* Gift box image */
            background-size: cover;
            display: inline-block;
            margin: 20px;
            cursor: pointer;
        }
        .gift-box:hover {
            animation: bounce 0.5s ease-in-out infinite; /* Add a bouncing animation on hover */
        }
        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
    </style>
</head>
<body>
    <h1>Congratulations Virtual Gift Package</h1>
    <div class="gift-box" onclick="revealMessage(this)"></div> <!-- Gift box element with onclick event -->

    <!-- JavaScript to reveal a congratulatory message when clicking on the gift box -->
    <script>
        function revealMessage(box) {
            // Add animation or transition to simulate opening the gift box
            box.style.transform = "rotateY(180deg)";
            
            // Display a more adorable and exciting congratulatory message inside the gift box
            box.innerHTML = "<p style='margin-top: 50px; font-size: 18px;'>🎉 Hooray! Congratulations to our incredible SCOME members! 🌟 Your unwavering support and enthusiasm have brought so much joy and success to our team! 🥳 Let's celebrate together! 🎈</p>";
        }
    </script>
</body>
</html>

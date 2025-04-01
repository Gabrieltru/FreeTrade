# FreeTrade
<!-- <!-- <html lang="en"> -->
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
</head>
<body>
    <h1>Welcome to FreeTrade! Here you can learn how to trade Stocks!</h1>
    <p>This is my first webpage hosted on GitHub Pages.</p>
    <p>Here you can see stock prices indicators and trade entrys</p>
    <p>Hello</p>
    <button onclick="alert('Button clicked!')">Click Me</button>
</body>
 <button onclick="toggleMenu()">Open Menu</button>

    <!-- Hidden menu -->
    <div id="menu">
        <h2>Stock Trading Menu</h2>
        <ul>
            <li>View Stock Prices</li>
            <li>Stock Indicators</li>
            <li>Trade Entries</li>
            <li>Learn How to Trade</li>
        </ul>
    </div>

    <script>
        function toggleMenu() {
            // Get the menu element
            var menu = document.getElementById("menu");

            // Toggle the visibility of the menu
            if (menu.style.display === "none") {
                menu.style.display = "block";  // Show the menu
            } else {
                menu.style.display = "none";  // Hide the menu
            }
        }
    </script>
</body>
</html>
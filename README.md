# Welcome to FreeTrade!


## Here you can see stock prices indicators and trade entries.


<!-- Button to open the menu -->
<button onclick="toggleMenu()">Menu</button>

<!-- Hidden menu -->
<div id="menu" style="display: none; background-color: lightgray; padding: 20px; margin-top: 10px;">
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
        var menu = document.getElementById("menu");
        if (menu.style.display === "none") {
            menu.style.display = "block";
        } else {
            menu.style.display = "none";
        }
    }
</script>

### Resources

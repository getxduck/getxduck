<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Xduck Purchase Options</title>
</head>

<body>
    <h1>Welcome to Xduck Purchase Options!</h1>
    <p>Xduck is available for purchase through the following options:</p>

    <h2>Option 1: Steam Account with Gorilla Tag 1 time purchase</h2>
    <p>If you choose this option, you need to provide a Steam account with Gorilla Tag game.</p>
    <button onclick="purchaseWithSteam()">Buy with Steam</button>

    <h2>Option 2: Discord Boost Every Month boost every month to contine getting updates</h2>
    <p>If you choose this option, you need to provide a Discord boost every month.</p>
    <button onclick="purchaseWithDiscord()">Buy with Discord Boost</button>

    <div id="purchase-info"></div>

    <script>
        function purchaseWithSteam() {
            // Code to handle purchase with Steam account
            document.getElementById("purchase-info").innerText = "Contact @realxcat on discord to continue";
        }

        function purchaseWithDiscord() {
            // Open the specified Discord URL in a new tab
            window.open("https://discord.gg/jy4R44nupf", "_blank");
        }
    </script>
</body>

</html>

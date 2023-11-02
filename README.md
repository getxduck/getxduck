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

    <h2>Option 2: Discord Boost Every Month 1 boost per month</h2>
    <p>If you choose this option, you need to provide a Discord boost every month.</p>
    <button onclick="purchaseWithDiscord()">Buy with Discord Boost</button>

    <div id="purchase-info"></div>

    <script>
        function purchaseWithSteam() {
            // Code to handle purchase with Steam account
            document.getElementById("purchase-info").innerText = "Please provide your Steam account details with Gorilla Tag to complete the purchase.";
        }

        function purchaseWithDiscord() {
            // Code to handle purchase with Discord boost
            document.getElementById("purchase-info").innerText = "Please provide your Discord boost details to set up monthly payments for the purchase.";
        }
    </script>
</body>

</html>

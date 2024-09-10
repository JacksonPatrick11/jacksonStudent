# Coin Flip Game

Click the button below to flip a coin!

<button id="flipButton">Flip Coin</button>

<div class="result" id="result"></div>

<script>
    document.getElementById("flipButton").addEventListener("click", function() {
        let result = Math.random() < 0.5 ? "Heads" : "Tails";
        document.getElementById("result").innerText = result;
    });
</script>

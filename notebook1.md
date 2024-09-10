# Dice Roll Game

Click the button below to roll the dice!

<div style="text-align: center;">
    <button onclick="rollDice()">Roll the Dice</button>
    <div id="diceResult" style="font-size: 100px; margin-top: 20px;">🎲</div>
</div>

<script>
function rollDice() {
const diceResult = document.getElementById('diceResult');
 const roll = Math.floor(Math.random() * 6) + 1;
 diceResult.textContent = roll;
    }
</script>

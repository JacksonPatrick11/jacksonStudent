# Magic 8-Ball Game

Ask a yes-or-no question and click the button to get an answer!

<button id="askButton">Ask the Magic 8-Ball</button>

<div class="answer" id="answer"></div>

<script>
    document.getElementById("askButton").addEventListener("click", function() {
        const answers = [
            "Yes",
            "No",
            "Maybe",
            "Ask again later",
            "Definitely",
            "I don't think so",
            "Absolutely",
            "Not a chance"
        ];
        const randomAnswer = answers[Math.floor(Math.random() * answers.length)];
        document.getElementById("answer").innerText = randomAnswer;
    });
</script>

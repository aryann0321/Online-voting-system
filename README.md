<div class="container">
<h1>Online Voting System</h1>
<p id="hpara">Developed by ARYAN </p>
<button class="refresh-button" onclick="refreshPage()">Refresh</button>
<div class="form">
    <label for="name">Enter Your Name:</label>
    <input type="text" id="name" placeholder="Enter your name">
</div>
<div class="candidates">
    <h4 id="cp">Nominated Parties:</h4>
    <div class="candidate">
        <input type="radio" id="candidate1" name="candidate" value="BJP">
        <label for="candidate1">BJP</label>
    </div>
    <div class="candidate">
        <input type="radio" id="candidate2" name="candidate" value="Congress">
        <label for="candidate2">Congress</label>
    </div>
    <div class="candidate">
        <input type="radio" id="candidate3" name="candidate" value="Other">
        <label for="candidate3">Other</label>
    </div>
</div>
<button class="btn" onclick="vote()">Vote</button> <br>
<button class="btn" onclick="calculateVotes()">Calculate Votes</button>
<div class="message" id="message"></div>
<div class="result" id="result"></div>
</div>

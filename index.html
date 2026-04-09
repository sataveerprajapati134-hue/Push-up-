<!DOCTYPE html>
<html>
<head>
    <title>Push-Up Challenge 1-1000</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #1e3c72, #2a5298);
            text-align: center;
            color: white;
            margin: 0;
            padding: 20px;
        }
        h1 {
            margin-bottom: 10px;
        }
        input, button {
            padding: 10px;
            margin: 5px;
            border-radius: 5px;
            border: none;
        }
        button {
            background: orange;
            font-weight: bold;
            cursor: pointer;
        }
        table {
            margin: 20px auto;
            width: 80%;
            max-width: 400px;
            border-collapse: collapse;
            background: rgba(0,0,0,0.6);
        }
        th, td {
            padding: 10px;
            border-bottom: 1px solid white;
        }
        th {
            background: black;
        }
    </style>
</head>
<body>

<h1>💪 Push-Up Challenge (1 - 1000)</h1>
<p>Apna naam aur push-ups enter karo. Top 3 ko rank milega!</p>

<input type="text" id="name" placeholder="Enter Your Name">
<input type="number" id="pushups" placeholder="Push-Ups">
<button onclick="addScore()">Submit</button>

<h2>🏆 Leaderboard</h2>

<table id="leaderboard">
    <tr>
        <th>Rank</th>
        <th>Name</th>
        <th>Push-Ups</th>
    </tr>
</table>

<script>
let scores = JSON.parse(localStorage.getItem("scores")) || [];

function addScore() {
    let name = document.getElementById("name").value;
    let pushups = parseInt(document.getElementById("pushups").value);

    if (!name || !pushups) {
        alert("Please enter valid details!");
        return;
    }

    if (pushups > 1000) {
        alert("Maximum limit is 1000!");
        return;
    }

    scores.push({name, pushups});
    scores.sort((a, b) => b.pushups - a.pushups);
    scores = scores.slice(0, 10);

    localStorage.setItem("scores", JSON.stringify(scores));
    displayLeaderboard();
}

function displayLeaderboard() {
    let table = document.getElementById("leaderboard");
    table.innerHTML = `
        <tr>
            <th>Rank</th>
            <th>Name</th>
            <th>Push-Ups</th>
        </tr>
    `;

    scores.forEach((player, index) => {
        let row = table.insertRow();
        row.insertCell(0).innerHTML = index + 1;
        row.insertCell(1).innerHTML = player.name;
        row.insertCell(2).innerHTML = player.pushups;
    });
}

displayLeaderboard();
</script>

</body>
</html>

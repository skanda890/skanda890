<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GitHub Contributions Game</title>
<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Arial', sans-serif;
  background-color: #f4f4f4;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

#game-container {
  width: 80%;
  max-width: 600px;
  margin: auto;
  padding: 20px;
  background-color: #fff;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  text-align: center;
}

.metric {
  margin-bottom: 15px;
}

.metric-label {
  display: block;
  font-size: 1.2em;
  color: #333;
  margin-bottom: 5px;
}

.metric-value {
  font-size: 2em;
  color: #4CAF50;
}
</style>
</head>
<body>

<div id="game-container">
  <!-- Game elements go here -->
</div>

<script>
// Replace 'yourPersonalAccessToken' with your actual GitHub Personal Access Token
const token = 'yourPersonalAccessToken';
const username = 'skanda890';

async function getContributions(token, username) {
  const headers = {
    'Authorization': `bearer ${token}`,
  }
  const body = {
    "query": `query {
      user(login: "${username}") {
        contributionsCollection {
          contributionCalendar {
            totalContributions
            weeks {
              contributionDays {
                contributionCount
                date
                weekday
              }
            }
          }
        }
      }
    }`
  }
  const response = await fetch('https://api.github.com/graphql', {
    method: 'POST',
    body: JSON.stringify(body),
    headers: headers
  })
  const data = await response.json();
  return data;
}

// Function to update the game state with new contribution data
function updateGameState(contributions) {
  // Implement game logic to update the state based on contributions
}

// Fetch contributions and update the game state
getContributions(token, username).then(data => {
  const contributions = data.data.user.contributionsCollection.contributionCalendar.totalContributions;
  updateGameState(contributions);
});
</script>
</body>
</html>

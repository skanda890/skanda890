<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GitHub PR Count</title>
<h1>GitHub Merged PR Count</h1>
<p>Enter a GitHub username to get the count of merged pull requests:</p>
<input type="text" id="username" placeholder="GitHub Username">
<button onclick="getPRCount()">Get PR Count</button>
<div id="prCount" class="result"></div>
</div>
<script>
function getPRCount() {
  var username = document.getElementById('skanda890').value;
  if (!username) {
    alert('Please enter a GitHub username.');
    return;
  }
  var query = `
    {
      search(query: "is:pr author:skanda890", type: ISSUE) {
        issueCount
      }
    }
  `;
  document.getElementById('prCount').textContent = 'Query: ' + query;
}
</script>
</body>
</html>

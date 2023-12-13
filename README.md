fetch("https://raw.githubusercontent.com/standard/standard/master/CHANGELOG.md")
      .then(response => response.text())
      .then(data => document.getElementById('code').textContent = data)

/* style.css */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f5f7fa;
  color: #333;
}

a {
  color: #f1faee;
  text-decoration: none;
}

header {
  background-color: #1d3557;
  color: white;
  padding: 20px;
  text-align: center;
}

nav {
  background-color: #457b9d;
  padding: 10px 0;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s;
}

nav a:hover {
  color: #f1faee;
}

.hero {
  padding: 60px 20px;
  background-color: #a8dadc;
  text-align: center;
}

.hero h1 {
  font-size: 3em;
  margin-bottom: 10px;
}

.features {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
  padding: 40px 20px;
  max-width: 1200px;
  margin: auto;
}

.feature {
  background-color: white;
  padding: 20px;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}

.feature:hover {
  transform: translateY(-5px);
}

.feature h3 {
  color: #1d3557;
}

footer {
  background-color: #1d3557;
  color: white;
  padding: 20px;
  text-align: center;
  font-size: 0.9em;
}

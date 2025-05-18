# Final Project and Deployment

## Objectives
Build a fully functional web application.
Apply HTML, CSS, and JavaScript concepts learned.
Deploy the project using GitHub Pages, Netlify, or Vercel.

## Instructions
Choose one of the following project ideas:
Blog Website: Implement a multi-page site with navigation.
Ecommerce Website: Implement a multi-page site with navigation.

>[!NOTE]
> - Include at least:
> - A responsive design.
> - JavaScript interactivity.
> - A deployment link.

## Tasks

Create a well-structured HTML5 document.<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Home | My Website</title>
  <link rel="stylesheet" href="css/styles.css" />
</head>
<body>
  <header>
    <h1>My Website</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>Welcome!</h2>
      <p>This is the homepage of my responsive website.</p>
    </section>
  </main>

  <footer>
    <p>© 2025 My Website</p>
  </footer>
  <script src="js/script.js"></script>
</body>
</html>body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

nav {
  background: #333;
  padding: 1em;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 1em;
  text-decoration: none;
}

@media (max-width: 600px) {
  nav a {
    display: block;
    margin: 0.5em 0;
  }
}



Use at least 5 different HTML elements.
Ensure semantic correctness.
document.addEventListener("DOMContentLoaded", () => {
  const form = document.querySelector("form");
  form?.addEventListener("submit", function (e) {
    const email = form.querySelector("input[tabby.wwambui@gmail.com']");
    if (!email.value.includes("@")) {
      alert(tabby.wwambui@gmail.com.");
      e.preventDefault();
    }
  });
});
Good luck and happy coding! 🚀💻

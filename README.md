<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Book with Raj</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #fffaf4;
      color: #333;
    }

    header {
      background-color: #ff6600;
      color: white;
      padding: 60px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2em;
      max-width: 700px;
      margin: auto;
    }

    .intro {
      text-align: center;
      padding: 40px 20px;
      font-size: 1.1em;
      max-width: 800px;
      margin: auto;
    }

    .categories {
      padding: 40px 20px;
      background-color: #f5f5f5;
    }

    .categories h2 {
      text-align: center;
      margin-bottom: 30px;
      font-size: 2em;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .card {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      overflow: hidden;
      text-align: center;
    }

    .card img {
      width: 100%;
      height: 250px;
      object-fit: cover;
    }

    .card h3 {
      padding: 10px;
      font-size: 1.1em;
    }

    .why {
      padding: 40px 20px;
      text-align: center;
    }

    .why h2 {
      font-size: 2em;
      margin-bottom: 20px;
    }

    .why ul {
      list-style: none;
      padding: 0;
      font-size: 1.1em;
    }

    .why ul li {
      margin: 10px 0;
    }

    .cta {
      text-align: center;
      padding: 40px 20px;
    }

    .cta a {
      background-color: #ff6600;
      color: white;
      padding: 15px 30px;
      font-size: 18px;
      text-decoration: none;
      border-radius: 8px;
      transition: background-color 0.3s ease;
    }

    .cta a:hover {
      background-color: #e65c00;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 30px 20px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2em;
      }

      .card img {
        height: 180px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Book with Raj</h1>
    <p>✨ Welcome to Book with Raj – Your Gateway to Great Reads!</p>
  </header>

  <section class="intro">
    <p>
      Whether you're a passionate reader or just starting your literary journey, you've landed in the right place. At <strong>Book with Raj</strong>, we celebrate the magic of books—from timeless classics to modern masterpieces, from thrilling mysteries to heartwarming romances.
    </p>
    <p>📚 Explore. Discover. Fall in Love with Books.</p>
  </section>

  <section class="categories">
    <h2>📸 Featured Categories</h2>
    <div class="grid">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1524995997946-a1c2e315a42f" alt="Fiction & Literature">
        <h3>Fiction & Literature</h3>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1517430816045-df4b7de11d1d" alt="Self-Help & Motivation">
        <h3>Self-Help & Motivation</h3>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1589820296154-7c1b1f3b6b3e" alt="Children’s Books">
        <h3>Children’s Books</h3>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1606788075761-7b7a5c3c7c3e" alt="Cookbooks & Lifestyle">
        <h3>Cookbooks & Lifestyle</h3>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1581091870622-3b6a1f3b6b3e" alt="Academic & Reference">
        <h3>Academic & Reference</h3>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1607746882042-944635dfe10e" alt="Graphic Novels & Comics">
        <h3>Graphic Novels & Comics</h3>
      </div>
    </div>
  </section>

  <section class="why">
    <h2>🗣️ Why Book with Raj?</h2>
    <ul>
      <li>✔️ Curated selections for every type of reader</li>
      <li>✔️ Honest reviews and recommendations</li>
      <li>✔️ Easy access to purchase your next favorite book</li>
      <li>✔️ A growing community of book lovers</li>
    </ul>
  </section>

  <section class="cta">
    <h2>🚀 Ready to Begin Your Reading Adventure?</h2>
    <a href="https://amzn.to/4nzO5aY" target="_blank">Get Start</a>
  </section>

  <footer>
    <p>📬 Stay Connected</p>
    <p>Want updates on new releases, reviews, and book deals? Subscribe to our newsletter and follow us on social media!</p>
    <p>&copy; 2025 Book with Raj</p>
  </footer>

</body>
</html>

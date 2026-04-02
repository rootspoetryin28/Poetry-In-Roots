Poetry-In-Roots/
├── index.html       ← Homepage with all poems/blog cards
├── post.html        ← Template for individual poems/blogs
├── css/
│   └── style.css    ← Styling for cards, layout, colors
├── images/          ← All images you used in posts
└── videos/ (optional, or just links to YouTube) 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Poetry In Roots</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <h1>Poetry In Roots</h1>

  <!-- Example Blog Card -->
  <div class="card">
    <h2>Self Respect V/s Ego</h2>
    <p>EGO – 3 letter word with negative energy…</p>
    <a href="post.html?post=self-respect-vs-ego">Read Full Post</a>
    <div class="links">
      <a href="https://www.instagram.com/reels/DWR1iXXioru/">Instagram</a>
      <a href="https://www.facebook.com/reel/1884490325563377">Facebook</a>
      <a href="https://www.youtube.com/shorts/2vE-59B85DA">YouTube</a>
    </div>
  </div>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Self Respect V/s Ego</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <h1>Self Respect V/s Ego</h1>
  <p>
    Full poem or blog content goes here...
  </p>

  <a href="index.html">← Back to Blog</a>

  <div class="links">
    <a href="https://www.instagram.com/reels/DWR1iXXioru/">Instagram</a>
    <a href="https://www.facebook.com/reel/1884490325563377">Facebook</a>
    <a href="https://www.youtube.com/shorts/2vE-59B85DA">YouTube</a>
  </div>
</body>
</html>body {
  font-family: Arial, sans-serif;
  background: #fdf6f0;
  color: #333;
  margin: 0;
  padding: 20px;
}

h1 { text-align: center; }

.card {
  background: #fff;
  padding: 20px;
  margin: 10px auto;
  border-radius: 10px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
  max-width: 600px;
}a {
  margin-right: 10px;
  text-decoration: none;
  color: #d35400;
}

.links {
  margin-top: 10px;
}
4️⃣ style.css (Basic Styling)
  <!-- Repeat similar card structure for all your blogs/posts -->git init
git add .
git commit -m "Add website files"
git branch -M main
git remote add origin https://github.com/rootspoetryin28/Poetry-In-Roots.git
git push -u origin main
</body>
</html>

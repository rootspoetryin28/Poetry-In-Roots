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

  <!-- Repeat similar card structure for all your blogs/posts -->
</body>
</html>

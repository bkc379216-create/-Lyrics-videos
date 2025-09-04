# -Lyrics-videos
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Bibek’s Lyric Videos</title>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<style>
  body { font-family: 'Roboto', sans-serif; margin:0; padding:0; background:#f9f9f9; color:#333;}
  header { background:#ff5252; color:#fff; padding:20px 10px; text-align:center;}
  nav a { color:#fff; margin:0 15px; text-decoration:none; font-weight:bold;}
  nav { margin-top:10px;}
  section { padding:40px 20px; max-width:1000px; margin:auto;}
  h2 { margin-bottom:20px; text-align:center;}
  .video-grid { display:grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap:20px;}
  .video-card { background:#fff; padding:10px; border-radius:8px; box-shadow:0 4px 6px rgba(0,0,0,0.1);}
  .video-card iframe { width:100%; height:200px; border:none; border-radius:5px;}
  footer { text-align:center; padding:20px; background:#333; color:#fff; margin-top:40px;}
  .subscribe { text-align:center; margin-top:20px;}
  .subscribe input[type="email"] { padding:10px; width:250px; border-radius:5px; border:1px solid #ccc;}
  .subscribe button { padding:10px 20px; border:none; background:#ff5252; color:#fff; border-radius:5px; cursor:pointer;}
</style>
</head>
<body>

<header>
  <h1>Bibek’s Lyric Videos</h1>
  <nav>
    <a href="#home">Home</a>
    <a href="#videos">Videos</a>
    <a href="#subscribe">Subscribe</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="home">
  <h2>Welcome to My Lyric Video Collection</h2>
  <p style="text-align:center;">Enjoy trending Nepali songs with animated lyrics and unique edits!</p>
</section>

<section id="videos">
  <h2>Latest Videos</h2>
  <div class="video-grid">
    <!-- Sample Video Embed -->
    <div class="video-card">
      <iframe src="https://www.youtube.com/embed/VIDEO_ID_1" allowfullscreen></iframe>
      <p>Chitthi Bhitra – Sajjan Raj Vaidya</p>
    </div>
    <div class="video-card">
      <iframe src="https://www.youtube.com/embed/VIDEO_ID_2" allowfullscreen></iframe>
      <p>Kutu Ma Kutu – Instrumental</p>
    </div>
    <div class="video-card">
      <iframe src="https://www.youtube.com/embed/VIDEO_ID_3" allowfullscreen></iframe>
      <p>Saili – Lyric Edit</p>
    </div>
  </div>
</section>

<section id="subscribe">
  <h2>Subscribe for Updates</h2>
  <div class="subscribe">
    <input type="email" placeholder="Enter your email" id="email">
    <button onclick="subscribe()">Subscribe</button>
  </div>
</section>

<section id="contact">
  <h2>Contact Me</h2>
  <p style="text-align:center;">Email: bibekkc@example.com</p>
</section>

<footer>
  &copy; 2025 Bibek Kc. All Rights Reserved.
</footer>

<script>
function subscribe() {
  var email = document.getElementById('email').value;
  if(email) {
    alert('Thanks for subscribing: ' + email);
  } else {
    alert('Please enter a valid email!');
  }
}
</script>

</body>
</html>

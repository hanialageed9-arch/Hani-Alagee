<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<title>مؤسسة رعاية الطفولة</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>مؤسسة رعاية الطفولة</h1>
  <p>نرعى الأطفال، نبني المستقبل</p>
</header>

<nav>
  <a href="#">الرئيسية</a>
  <a href="#">من نحن</a>
  <a href="#">خدماتنا</a>
  <a href="#">معرض الصور</a>
  <a href="#">تواصل معنا</a>
</nav>

<section class="about">
  <h2>من نحن</h2>
  <p>
    مؤسسة رعاية الطفولة هي مؤسسة إنسانية تهدف إلى حماية الأطفال
    وتوفير بيئة آمنة لهم من خلال التعليم والرعاية الصحية والدعم النفسي.
  </p>
</section>

<section class="services">
  <h2>خدماتنا</h2>
  <div class="cards">
    <div class="card">👶 رعاية الأطفال</div>
    <div class="card">📚 التعليم</div>
    <div class="card">🏥 الرعاية الصحية</div>
  </div>
</section>

<section class="gallery">
  <h2>معرض الصور</h2>
  <img src="images/child1.jpg">
  <img src="images/child2.jpg">
  <img src="images/child3.jpg">
</section>

<footer>
  <p>© 2026 مؤسسة رعاية الطفولة</p>
</footer>

</body>
</html>
body {
  margin: 0;
  font-family: Arial, Tahoma;
  background: #f4f6f8;
}

header {
  background: #2e86de;
  color: white;
  padding: 30px;
  text-align: center;
}

nav {
  background: #1e3799;
  text-align: center;
  padding: 10px;
}

nav a {
  color: white;
  margin: 10px;
  text-decoration: none;
  font-weight: bold;
}

section {
  padding: 30px;
  text-align: center;
}

.cards {
  display: flex;
  justify-content: center;
  gap: 15px;
  flex-wrap: wrap;
}

.card {
  background: white;
  padding: 20px;
  width: 200px;
  border-radius: 10px;
  box-shadow: 0 0 10px #ccc;
}

.gallery img {
  width: 200px;
  margin: 10px;
  border-radius: 10px;
}

footer {
  background: #1e3799;
  color: white;
  text-align: center;
  padding: 15px;
}

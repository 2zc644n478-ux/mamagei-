<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<title>Mamagei-Haus – Virtueller Begegnungsraum</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
  <img src="mamagei.svg" class="logo">
  <h1>Willkommen im Mamagei-Haus</h1>
  <p>Ein Ort für Humor, Wärme und Erkenntnis.</p>
</header>

<section class="kreise">
  <a href="welt.html" class="kreis welt">ÄUSSERER KREIS<br>Die Welt</a>
  <a href="freunde.html" class="kreis freunde">MITTLERER KREIS<br>Freunde</a>
  <a href="rudel.html" class="kreis rudel">INNERER KREIS<br>Rudel</a>
</section>

<footer>
  <p>© 2026 Jürg Emler – Mamagei-Haus</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<title>Rudel – Innerer Kreis</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<h1>🐺 Rudelplatz</h1>
<p>Der geschützte Raum für Familie, Herz und Ursprung.</p>

<h2>Wochenimpuls</h2>
<p>„Was hat dich diese Woche zum Lächeln gebracht?“</p>

<h2>Kreisfrage</h2>
<p>„Welcher Umweg hat dich weitergebracht?“</p>

<h2>Rudel-Chronik</h2>
<ul>
  <li>Gemeinsame Momente</li>
  <li>Fotos</li>
  <li>Geschichten</li>
</ul>

<h2>Virtuelle Lounge</h2>
<p>Chat, Audio-Zonen, Feuerkreis.</p>

<a href="index.html">Zurück</a>

</body>
</html>
<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<title>Freunde – Mittlerer Kreis</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<h1>🤝 Freunde</h1>
<p>Der Raum für Austausch, Humor und Inspiration.</p>

<h2>Humor-Ecke</h2>
<p>Ein Ort für kleine Funken der Leichtigkeit.</p>

<h2>Musik des Tages</h2>
<p>Ein Lied, das den Kopf neigt wie der Mamagei.</p>

<h2>Fundstücke</h2>
<p>Bilder, Links, Gedanken.</p>

<a href="index.html">Zurück</a>

</body>
</html>
<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<title>Die Welt – Öffentlicher Bereich</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<h1>🌍 Die Welt</h1>
<p>Der öffentliche Raum deiner Webseite.</p>

<h2>Die Trilogie</h2>
<ul>
  <li>Öl in der Lagune</li>
  <li>Circle of Life</li>
  <li>Interview mit dem Teufel</li>
</ul>

<h2>Gedankenstrom</h2>
<p>Essays, Miniaturen, Humorfunken.</p>

<h2>Galerie</h2>
<p>Öffentliche Bilder und Mamagei-Varianten.</p>

<a href="index.html">Zurück</a>

</body>
</html>
body {
  font-family: "Lato", sans-serif;
  background: #fdfdfd;
  color: #333;
  text-align: center;
  margin: 0;
  padding: 0;
}

header {
  padding: 40px;
  background: #0F5F66;
  color: white;
}

.logo {
  width: 120px;
}

.kreise {
  display: flex;
  justify-content: center;
  gap: 40px;
  margin: 60px 0;
}

.kreis {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  text-decoration: none;
  color: white;
  font-size: 20px;
  padding: 20px;
}

.welt { background: #3FB7A8; }
.freunde { background: #D46F4D; }
.rudel { background: #C9A44C; }

footer {
  margin-top: 80px;
  padding: 20px;
  background: #eee;
}
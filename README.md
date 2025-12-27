<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SAST | San Andreas State Troopers</title>
  <style>
    :root {
      --blue: #0b3d91;
      --dark: #020617;
      --bg: #0e1117;
      --text: #e6e6e6;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: 'Segoe UI', Arial, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }
    header {
      background: linear-gradient(135deg, var(--blue), #020617);
      padding: 90px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 46px;
      margin-bottom: 10px;
      letter-spacing: 3px;
    }
    header p {
      font-size: 20px;
      opacity: 0.9;
    }
    nav {
      background: var(--dark);
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 16px 0;
      position: sticky;
      top: 0;
      z-index: 100;
    }
    nav a {
      color: var(--text);
      text-decoration: none;
      font-weight: 600;
      letter-spacing: 1px;
    }
    nav a:hover { color: #4da3ff; }
    section {
      max-width: 1200px;
      margin: auto;
      padding: 70px 20px;
    }
    section h2 {
      font-size: 34px;
      margin-bottom: 25px;
      border-left: 6px solid var(--blue);
      padding-left: 15px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 25px;
    }
    .card {
      background: var(--dark);
      padding: 28px;
      border-radius: 14px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.45);
    }
    .card h3 { margin-top: 0; }
    .rank-list li {
      margin-bottom: 6px;
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 14px 26px;
      background: var(--blue);
      color: #fff;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
      letter-spacing: 1px;
    }
    .btn:hover { background: #1457c9; }
    footer {
      background: var(--dark);
      text-align: center;
      padding: 35px 20px;
      font-size: 14px;
      opacity: 0.85;
    }
  </style>
</head>
<body>

<header>
  <h1>SAN ANDREAS STATE TROOPERS</h1>
  <p>Pentagonowa Formacja Porządkowa</p>
</header>

<nav>
  <a href="#about">O nas</a>
  <a href="#structure">Struktura</a>
  <a href="#divisions">Dywizje</a>
  <a href="#recruitment">Rekrutacja</a>
  <a href="#contact">Kontakt</a>
</nav>

<section id="about">
  <h2>O formacji</h2>
  <p>
    <strong>San Andreas State Troopers (SAST)</strong> to stanowa, zmilitaryzowana formacja porządkowa
    działająca na terenie całego San Andreas. Odpowiadamy za bezpieczeństwo na autostradach,
    wsparcie lokalnych LEA oraz operacje specjalistyczne.
  </p>
</section>

<section id="structure">
  <h2>Struktura i stopnie</h2>
  <div class="grid">
    <div class="card">
      <h3>Kadra dowódcza</h3>
      <ul class="rank-list">
        <li>Colonel – Komendant Stanowy</li>
        <li>Lieutenant Colonel – Zastępca Komendanta</li>
        <li>Major</li>
        <li>Captain</li>
      </ul>
    </div>
    <div class="card">
      <h3>Kadra oficerska</h3>
      <ul class="rank-list">
        <li>Lieutenant</li>
        <li>Sergeant I</li>
        <li>Sergeant II</li>
      </ul>
    </div>
    <div class="card">
      <h3>Funkcjonariusze liniowi</h3>
      <ul class="rank-list">
        <li>Senior Trooper</li>
        <li>Trooper First Class</li>
        <li>Trooper</li>
        <li>Probationary Trooper</li>
      </ul>
    </div>
  </div>
</section>

<section id="divisions">
  <h2>Dywizje</h2>
  <div class="grid">
    <div class="card">
      <h3>Highway Patrol Division</h3>
      <p>Ruch drogowy, pościgi i patrole autostradowe.</p>
    </div>
    <div class="card">
      <h3>Internal Affairs</h3>
      <p>Kontrola wewnętrzna i postępowania dyscyplinarne.</p>
    </div>
    <div class="card">
      <h3>Aerial & Maritime Division</h3>
      <p>Operacje lotnicze i wodne.</p>
    </div>
    <div class="card">
      <h3>Special Operations Division</h3>
      <p>Działania wysokiego ryzyka i wsparcie taktyczne.</p>
    </div>
  </div>
</section>

<section id="recruitment">
  <h2>Rekrutacja</h2>
  <p>
    Dołącz do elitarnej stanowej formacji porządkowej.
    Oferujemy szkolenia, realistyczny roleplay i rozwój kariery.
  </p>
  <a class="btn" href="#contact">Dołącz do SAST</a>
</section>

<section id="contact">
  <h2>Kontakt</h2>
  <p>
    Rekrutacja oraz sprawy organizacyjne odbywają się poprzez Discord serwera RP.
  </p>
</section>

<footer>
  © San Andreas State Troopers | Pentagonowa Formacja Porządkowa
</footer>

</body>
</html>

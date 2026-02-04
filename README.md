# ogarniammature.pl
<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ogarniam Maturę - Dashboard Ucznia</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font-family: 'Inter', sans-serif; background: #0f172a; color: #e5e7eb; line-height: 1.6; }
    header { padding: 40px 20px; text-align: center; background: linear-gradient(135deg, #6366f1, #22d3ee); color: white; }
    header h1 { font-size: 2.5rem; }
    section { padding: 50px 20px; max-width: 1100px; margin: auto; }
    h2 { font-size: 2rem; margin-bottom: 25px; text-align: center; }
    .courses-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .card { background: #020617; padding: 25px; border-radius: 16px; box-shadow: 0 10px 30px rgba(0,0,0,.4); transition: transform .3s; }
    .card:hover { transform: translateY(-5px); }
    .card h3 { margin-bottom: 12px; }
    .card p { color: #cbd5f5; margin-bottom: 15px; }
    .card button { padding: 12px 25px; background: #6366f1; color: white; border: none; border-radius: 999px; font-weight: 600; cursor: pointer; transition: background .3s; }
    .card button:hover { background: #4f46e5; }
    footer { text-align: center; padding: 25px; color: #94a3b8; font-size: .9rem; }
    @media (max-width: 768px) {
      header h1 { font-size: 2rem; }
      h2 { font-size: 1.6rem; }
    }
  </style>
</head>
<body>

<header>
  <h1>Ogarniam Maturę - Dashboard Ucznia</h1>
  <p>Witaj! Tutaj zobaczysz swoje darmowe materiały, zakupione kursy i certyfikaty.</p>
</header>

<section>
  <h2>Darmowe materiały</h2>
  <div class="courses-grid">
    <div class="card">
      <h3>Darmowy PDF 1</h3>
      <p>Przykładowy materiał maturalny, dostępny od razu po rejestracji.</p>
      <button>Pobierz PDF</button>
    </div>
    <div class="card">
      <h3>Darmowy PDF 2</h3>
      <p>Kolejny materiał do zapoznania się z platformą.</p>
      <button>Pobierz PDF</button>
    </div>
  </div>
</section>

<section>
  <h2>Twoje kursy</h2>
  <div class="courses-grid">
    <div class="card">
      <h3>Matematyka - Podstawa</h3>
      <p>Dostępne od: 2026-02-04 | Ważne do: 2027-12-04</p>
      <button>Otwórz PDF</button>
    </div>
    <div class="card">
      <h3>Język Polski - Podstawa</h3>
      <p>Dostępne od: 2026-02-04 | Ważne do: 2027-12-04</p>
      <button>Otwórz PDF</button>
    </div>
    <div class="card">
      <h3>Język Angielski - Podstawa</h3>
      <p>Dostępne od: 2026-02-04 | Ważne do: 2027-12-04</p>
      <button>Otwórz PDF</button>
    </div>
  </div>
</section>

<section>
  <h2>Certyfikaty</h2>
  <div class="courses-grid">
    <div class="card">
      <h3>Certyfikat - Matematyka</h3>
      <p>Po ukończeniu kursu możesz pobrać certyfikat PDF.</p>
      <button>Pobierz certyfikat</button>
    </div>
    <div class="card">
      <h3>Certyfikat - Polski</h3>
      <p>Po ukończeniu kursu możesz pobrać certyfikat PDF.</p>
      <button>Pobierz certyfikat</button>
    </div>
    <div class="card">
      <h3>Certyfikat - Angielski</h3>
      <p>Po ukończeniu kursu możesz pobrać certyfikat PDF.</p>
      <button>Pobierz certyfikat</button>
    </div>
  </div>
</section>

<footer>
  © 2026 Ogarniam Maturę. Wszelkie prawa zastrzeżone.
</footer>

<script>
  // Tutaj w przyszłości podłączysz funkcje: otwieranie PDF, pobieranie certyfikatów, Firebase Auth
  document.querySelectorAll('button').forEach(btn => {
    btn.addEventListener('click', () => {
      alert('Tutaj zostanie podpięta funkcja otwierania PDF / pobrania certyfikatu.');
    });
  });
</script>

</body>
</html>

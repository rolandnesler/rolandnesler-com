# rolandnesler-com
Website rolandnesler.com - Zinzino
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Roland Nesler | Testbasierte Gesundheit mit Zinzino</title>
  <meta name="description" content="Roland Nesler begleitet Menschen dabei, Gesundheitsentscheidungen bewusster, messbarer und alltagstauglicher zu gestalten – mit testbasierter Gesundheit und Zinzino." />

  <style>
    :root {
      --bg: #f7f8f5;
      --text: #1f2a24;
      --muted: #607064;
      --green: #2f6b4f;
      --green-dark: #234f3b;
      --card: #ffffff;
      --line: #dfe6dd;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      padding: 24px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: rgba(255, 255, 255, 0.85);
      border-bottom: 1px solid var(--line);
      position: sticky;
      top: 0;
      z-index: 10;
    }

    .logo {
      font-weight: 700;
      font-size: 20px;
      color: var(--green-dark);
    }

    nav a {
      margin-left: 22px;
      text-decoration: none;
      color: var(--text);
      font-size: 15px;
    }

    nav a:hover {
      color: var(--green);
    }

    .hero {
      padding: 80px 8%;
      display: grid;
      grid-template-columns: 1.1fr 0.9fr;
      gap: 48px;
      align-items: center;
    }

    .hero h1 {
      font-size: clamp(38px, 5vw, 64px);
      line-height: 1.08;
      margin: 0 0 24px;
      color: var(--green-dark);
    }

    .hero p {
      font-size: 20px;
      color: var(--muted);
      margin-bottom: 32px;
      max-width: 660px;
    }

    .buttons {
      display: flex;
      flex-wrap: wrap;
      gap: 14px;
    }

    .button {
      display: inline-block;
      padding: 14px 22px;
      border-radius: 999px;
      text-decoration: none;
      font-weight: 700;
      border: 2px solid var(--green);
    }

    .button.primary {
      background: var(--green);
      color: white;
    }

    .button.secondary {
      color: var(--green);
      background: transparent;
    }

    .image-placeholder {
      min-height: 420px;
      border-radius: 28px;
      background: linear-gradient(135deg, #dfe9df, #b8cdbd);
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 32px;
      color: var(--green-dark);
      font-weight: 700;
      box-shadow: 0 18px 50px rgba(31, 42, 36, 0.12);
    }

    section {
      padding: 72px 8%;
    }

    .section-title {
      max-width: 760px;
      margin-bottom: 34px;
    }

    .section-title h2 {
      font-size: 36px;
      line-height: 1.2;
      margin: 0 0 14px;
      color: var(--green-dark);
    }

    .section-title p {
      color: var(--muted);
      font-size: 18px;
      margin: 0;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 22px;
    }

    .card {
      background: var(--card);
      padding: 28px;
      border-radius: 22px;
      border: 1px solid var(--line);
      box-shadow: 0 10px 30px rgba(31, 42, 36, 0.06);
    }

    .card h3 {
      margin-top: 0;
      color: var(--green-dark);
      font-size: 22px;
    }

    .card p {
      color: var(--muted);
      margin-bottom: 0;
    }

    .wide {
      background: var(--green-dark);
      color: white;
      border-radius: 30px;
      padding: 48px;
    }

    .wide h2 {
      margin-top: 0;
      font-size: 34px;
    }

    .wide p {
      color: #e6efe8;
      font-size: 18px;
      max-width: 860px;
    }

    .note {
      font-size: 14px;
      color: var(--muted);
      max-width: 900px;
    }

    footer {
      padding: 36px 8%;
      border-top: 1px solid var(--line);
      color: var(--muted);
      font-size: 14px;
    }

    @media (max-width: 900px) {
      header {
        display: block;
      }

      nav {
        margin-top: 14px;
      }

      nav a {
        margin: 0 14px 10px 0;
        display: inline-block;
      }

      .hero {
        grid-template-columns: 1fr;
        padding-top: 52px;
      }

      .cards {
        grid-template-columns: 1fr;
      }

      .wide {
        padding: 32px;
      }
    }
  </style>
</head>

<body>
  <header>
    <div class="logo">Roland Nesler</div>
    <nav>
      <a href="#gesundheit">Testbasierte Gesundheit</a>
      <a href="#tests">Tests</a>
      <a href="#partner">Partner werden</a>
      <a href="#kontakt">Kontakt</a>
    </nav>
  </header>

  <main>
    <section class="hero">
      <div>
        <h1>Testbasierte Gesundheit mit Zinzino: Messen statt raten.</h1>
        <p>
          Ich begleite Menschen dabei, ihre Gesundheitsentscheidungen bewusster,
          messbarer und alltagstauglicher zu gestalten – mit modernen Home Health Tests,
          gezielter Versorgung und regelmäßiger Verlaufskontrolle.
        </p>
        <div class="buttons">
          <a class="button primary" href="#kontakt">Gespräch buchen</a>
          <a class="button secondary" href="#tests">Tests ansehen</a>
        </div>
      </div>

      <div class="image-placeholder">
        Hier kommt später dein Hero-Bild hinein:<br />
        IMG_8629.jpeg
      </div>
    </section>

    <section id="gesundheit">
      <div class="section-title">
        <h2>Messen – gezielt versorgen – Verlauf kontrollieren</h2>
        <p>
          Nicht raten, sondern messen. Nicht beliebig supplementieren, sondern gezielt versorgen.
          Nicht vergessen, sondern den Verlauf kontrollieren.
        </p>
      </div>

      <div class="cards">
        <div class="card">
          <h3>Messen</h3>
          <p>
            Home Health Tests können Orientierung geben und helfen, persönliche Ausgangswerte besser zu verstehen.
          </p>
        </div>

        <div class="card">
          <h3>Gezielt versorgen</h3>
          <p>
            Auf Basis von Messergebnissen lassen sich Ernährung, Routinen und Versorgung bewusster betrachten.
          </p>
        </div>

        <div class="card">
          <h3>Verlauf kontrollieren</h3>
          <p>
            Regelmäßige Kontrolle macht Veränderungen sichtbar und unterstützt langfristige Gesundheitsentscheidungen.
          </p>
        </div>
      </div>
    </section>

    <section id="tests">
      <div class="section-title">
        <h2>Zinzino Home Health Tests</h2>
        <p>
          Der Fokus liegt zunächst auf ausgewählten Tests, die Menschen dabei unterstützen können,
          persönliche Gesundheitsdaten besser einzuordnen.
        </p>
      </div>

      <div class="cards">
        <div class="card">
          <h3>BalanceTest</h3>
          <p>
            Ein Selbsttest für zu Hause zur Analyse ausgewählter Fettsäurewerte.
          </p>
        </div>

        <div class="card">
          <h3>Gut Health Test</h3>
          <p>
            Ein Testkonzept zur Betrachtung ausgewählter Marker im Zusammenhang mit Darmgesundheit und Stoffwechsel.
          </p>
        </div>

        <div class="card">
          <h3>Weitere Tests</h3>
          <p>
            Je nach Markt und Verfügbarkeit können weitere Tests wie Vitamin D oder HbA1c relevant sein.
            Aktuelle Details findest du direkt im offiziellen Zinzino-Shop.
          </p>
        </div>
      </div>
    </section>

    <section>
      <div class="wide">
        <h2>Über Roland</h2>
        <p>
          Ich bin Professional Wellnesstrainer, Ernährungs- und Gesundheits-Coach
          und Zinzino-Partner. Gesundheit bedeutet für mich nicht kurzfristige Trends,
          sondern bewusste Entscheidungen, alltagstaugliche Umsetzung und messbare Entwicklung.
        </p>
        <p>
          Sport, gesunde Ernährung, Krafttraining, Mountainbike fahren, Bergwandern,
          Segeln, Skilaufen und Kochen gehören zu meinem Leben – und prägen auch meinen
          persönlichen Zugang zu Gesundheit.
        </p>
      </div>
    </section>

    <section id="partner">
      <div class="section-title">
        <h2>Partner werden</h2>
        <p>
          Für Menschen, die sich für Gesundheit, Messbarkeit und ein internationales Partnerbusiness interessieren,
          kann Zinzino eine spannende Möglichkeit sein.
        </p>
      </div>

      <div class="card">
        <h3>Seriös, persönlich und ohne Erfolgsversprechen</h3>
        <p>
          Zinzino bietet ein Partnerprogramm mit Vergütungsmöglichkeiten gemäß offiziellem Compensation Plan.
          Ob und in welcher Höhe Einnahmen entstehen, hängt von persönlicher Aktivität, Kundenaufbau,
          Teamaufbau, Marktumfeld, Qualifikation und Umsetzung ab.
        </p>
      </div>
    </section>

    <section id="kontakt">
      <div class="section-title">
        <h2>Lass uns sprechen</h2>
        <p>
          Du möchtest wissen, ob die Tests, Produkte oder die Partnerchance zu dir passen?
          Dann vereinbaren wir am besten ein persönliches Gespräch.
        </p>
      </div>

      <div class="buttons">
        <a class="button primary" href="mailto:roland.nesler@gmail.com">E-Mail schreiben</a>
        <a class="button secondary" href="#">Offiziellen Zinzino-Shop öffnen</a>
      </div>

      <p class="note">
        Hinweis: Die Inhalte dieser Website dienen der Information und ersetzen keine ärztliche Diagnose,
        Beratung oder Behandlung. Aktuelle Preise, Verfügbarkeit und Bestellinformationen findest du direkt
        im offiziellen Zinzino-Shop. Der finale Partnerlink wird noch eingefügt.
      </p>
    </section>
  </main>

  <footer>
    © 2026 Roland Nesler · Impressum und Datenschutz werden ergänzt.
  </footer>
</body>
</html>

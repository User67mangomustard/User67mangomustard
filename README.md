<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <title>Bez Dyskryminacji</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <!-- Firebase -->
  <script src="https://www.gstatic.com/firebasejs/9.23.0/firebase-app-compat.js"></script>
  <script src="https://www.gstatic.com/firebasejs/9.23.0/firebase-database-compat.js"></script>

  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: #0f0f0f;
      color: #f2f2f2;
    }

    header {
      background: #000;
      padding: 30px;
      text-align: center;
      border-bottom: 4px solid #ff8800;
    }

    header h1 {
      color: #ff8800;
      margin: 0;
      font-size: 2.5em;
    }

    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    h2 {
      color: #ff8800;
      border-left: 6px solid #ff8800;
      padding-left: 10px;
    }

    .box {
      background: #1a1a1a;
      padding: 20px;
      border-radius: 6px;
      margin-top: 20px;
    }

    input, textarea {
      width: 100%;
      margin-top: 10px;
      padding: 10px;
      background: #111;
      color: #fff;
      border: 1px solid #ff8800;
      border-radius: 4px;
    }

    button {
      margin-top: 15px;
      padding: 10px 18px;
      background: #ff8800;
      border: none;
      font-weight: bold;
      cursor: pointer;
    }

    .comment {
      background: #111;
      padding: 15px;
      margin-top: 15px;
      border-left: 4px solid #ff8800;
    }

    .actions {
      margin-top: 10px;
      font-size: 0.9em;
    }

    .actions button {
      background: none;
      color: #ff8800;
      border: none;
      cursor: pointer;
      padding: 0;
      margin-right: 10px;
    }

    footer {
      background: #000;
      color: #777;
      text-align: center;
      padding: 20px;
      margin-top: 50px;
    }
  </style>
</head>
<body>

<header>
  <h1>BEZ DYSKRYMINACJI</h1>
  <p style="max-width:800px;margin:15px auto;color:#ccc;">
    Strona poświęcona rasizmowi, wykluczeniu społecznemu i wszelkim formom dyskryminacji.
    Jej celem jest edukacja, uświadamianie oraz stworzenie bezpiecznego miejsca do dzielenia się
    doświadczeniami osób, które doświadczyły niesprawiedliwego traktowania.
  </p>
</header>

<section>
  <h2>Czym jest dyskryminacja?</h2>
  <div class="box">
    <p>
      Dyskryminacja to nierówne, niesprawiedliwe lub krzywdzące traktowanie osób lub grup
      ze względu na określone cechy, takie jak pochodzenie etniczne, kolor skóry, płeć,
      orientacja seksualna, tożsamość płciowa, religia, niepełnosprawność, wiek czy status
      materialny. Bardzo często osoby dyskryminowane nie mają żadnego wpływu na cechy,
      przez które są oceniane i wykluczane.
    </p>
    <p>
      Dyskryminacja może mieć charakter otwarty, na przykład w postaci przemocy fizycznej
      lub werbalnej, ale również ukryty – poprzez stereotypy, uprzedzenia, ignorowanie,
      brak dostępu do edukacji, pracy czy opieki zdrowotnej.
    </p>
  </div>
</section>

<section>
  <h2>Czym jest rasizm?</h2>
  <div class="box">
    <p>
      Rasizm jest jedną z najpowszechniejszych i najbardziej destrukcyjnych form dyskryminacji.
      Polega na przekonaniu, że ludzie mogą być oceniani, klasyfikowani lub traktowani gorzej
      ze względu na kolor skóry, pochodzenie etniczne lub narodowość. Rasizm często opiera się
      na fałszywych przekonaniach, stereotypach i historycznych uprzedzeniach.
    </p>
    <p>
      Może on występować na poziomie indywidualnym, społecznym, a także instytucjonalnym,
      kiedy to całe systemy prawne, edukacyjne lub gospodarcze faworyzują jedne grupy kosztem innych.
    </p>
  </div>
</section>

<section>
  <h2>Rodzaje dyskryminacji</h2>
  <div class="box">
    <ul>
      <li><strong>Rasizm</strong> – dyskryminacja ze względu na kolor skóry lub pochodzenie.</li>
      <li><strong>Seksizm</strong> – nierówne traktowanie ze względu na płeć.</li>
      <li><strong>Homofobia i transfobia</strong> – wrogość wobec osób LGBT+.</li>
      <li><strong>Dyskryminacja ze względu na niepełnosprawność</strong> – fizyczną lub psychiczną.</li>
      <li><strong>Ageizm</strong> – dyskryminacja ze względu na wiek.</li>
      <li><strong>Dyskryminacja ekonomiczna</strong> – ocenianie ludzi przez pryzmat ich sytuacji finansowej.</li>
      <li><strong>Dyskryminacja religijna</strong> – prześladowanie lub wykluczanie ze względu na wyznanie.</li>
    </ul>
  </div>
</section>

<section>
  <h2>Przykłady dyskryminacji w codziennym życiu</h2>
  <div class="box">
    <p>
      Dyskryminacja nie zawsze wygląda jak otwarta przemoc. Często przybiera subtelne formy,
      takie jak gorsze traktowanie w szkole, ignorowanie głosu danej osoby, brak awansu w pracy,
      wyśmiewanie akcentu, wyglądu czy pochodzenia.
    </p>
    <p>
      W internecie dyskryminacja objawia się poprzez hejt, mowę nienawiści, groźby oraz
      dehumanizowanie określonych grup społecznych. Skutki takich działań mogą być bardzo
      poważne i długotrwałe.
    </p>
  </div>
</section>

<section>
  <h2>Dlaczego to jest problem?</h2>
  <div class="box">
    <p>
      Dyskryminacja prowadzi do wykluczenia społecznego, pogorszenia zdrowia psychicznego,
      obniżenia poczucia własnej wartości oraz poczucia braku bezpieczeństwa. W skrajnych
      przypadkach może prowadzić do przemocy, depresji, a nawet samobójstw.
    </p>
    <p>
      Społeczeństwo, które toleruje dyskryminację, traci empatię, solidarność i zdolność
      do współpracy. Dlatego tak ważne jest reagowanie, edukacja i wspieranie osób
      dotkniętych wykluczeniem.
    </p>
  </div>
</section>

<section>
  <h2>Dodaj swoją historię</h2></h2>
  <div class="box">
    <input id="name" placeholder="Imię lub pseudonim" />
    <textarea id="story" rows="5" placeholder="Opisz, czego doświadczyłeś..." ></textarea>
    <button onclick="addStory()">Dodaj</button>
  </div>
</section>

<section>
  <h2>Historie użytkowników</h2>
  <div id="stories"></div>
</section>

<footer>
  © 2026 Bez Dyskryminacji
</footer>

<script>
  const firebaseConfig = {
    apiKey: "TWOJ_API_KEY",
    authDomain: "TWOJ_PROJEKT.firebaseapp.com",
    databaseURL: "https://TWOJ_PROJEKT.firebaseio.com",
    projectId: "TWOJ_PROJEKT",
  };

  firebase.initializeApp(firebaseConfig);
  const db = firebase.database();
  const storiesRef = db.ref("stories");

  function addStory() {
    const name = document.getElementById("name").value || "Anonim";
    const story = document.getElementById("story").value;

    if (!story.trim()) return;

    storiesRef.push({
      name: name,
      story: story,
      reported: false,
      timestamp: Date.now()
    });

    document.getElementById("name").value = "";
    document.getElementById("story").value = "";
  }

  storiesRef.limitToLast(50).on("value", snapshot => {
    const container = document.getElementById("stories");
    container.innerHTML = "";

    snapshot.forEach(child => {
      const data = child.val();
      if (data.reported) return;

      const div = document.createElement("div");
      div.className = "comment";
      div.innerHTML = `
        <strong>${data.name}</strong>
        <p>${data.story}</p>
        <div class="actions">
          <button onclick="reportStory('${child.key}')">Zgłoś hejt</button>
        </div>
      `;
      container.prepend(div);
    });
  });

  function reportStory(id) {
    if (confirm("Zgłosić tę historię do moderacji?")) {
      db.ref("stories/" + id).update({ reported: true });
    }
  }
</script>

</body>
</html>


<!--
**User67mangomustard/User67mangomustard** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

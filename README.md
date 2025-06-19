<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Como Jogar Vôlei</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #dbeafe, #f0f9ff);
      color: #1e3a8a;
    }

    header {
      background-color: #1e40af;
      color: white;
      text-align: center;
      padding: 30px 20px;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
    }

    .tabs {
      display: flex;
      justify-content: center;
      margin-top: 20px;
      flex-wrap: wrap;
    }

    .tab-button {
      padding: 15px 30px;
      background-color: #e0e7ff;
      border: none;
      border-radius: 8px 8px 0 0;
      cursor: pointer;
      font-weight: bold;
      margin: 0 5px;
      transition: background-color 0.3s;
    }

    .tab-button.active {
      background-color: #1e40af;
      color: white;
    }

    .tab-content {
      display: none;
      max-width: 900px;
      margin: auto;
      padding: 30px 20px;
      background-color: white;
      border-radius: 0 0 12px 12px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    }

    .tab-content.active {
      display: block;
    }

    h2 {
      color: #1e3a8a;
    }

    ul {
      padding-left: 20px;
    }

    footer {
      background-color: #1e40af;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Como Jogar Vôlei</h1>
    <p>Aprenda os principais fundamentos: Manchete, Levantamento e Ataque</p>
  </header>

  <div class="tabs">
    <button class="tab-button active" onclick="openTab('manchete')">Manchete</button>
    <button class="tab-button" onclick="openTab('levantamento')">Levantamento</button>
    <button class="tab-button" onclick="openTab('ataque')">Ataque</button>
  </div>

  <div id="manchete" class="tab-content active">
    <h2>🏐 Como Fazer a Manchete</h2>
    <ul>
      <li>Junte os antebraços, com as mãos unidas e esticadas.</li>
      <li>Dobre levemente os joelhos e mantenha os pés afastados na largura dos ombros.</li>
      <li>Espere a bola vir na altura da cintura.</li>
      <li>Toque nela com os antebraços, empurrando levemente com as pernas.</li>
      <li>Evite usar os braços — o movimento vem do corpo.</li>
    </ul>
  </div>

  <div id="levantamento" class="tab-content">
    <h2>📍 Como Fazer o Levantamento</h2>
    <ul>
      <li>Posicione as mãos na frente da testa, formando um triângulo com os dedos.</li>
      <li>Flexione levemente os joelhos e mantenha os cotovelos abertos.</li>
      <li>Toque na bola com a ponta dos dedos, empurrando para cima e para o atacante.</li>
      <li>O levantamento deve ser rápido e preciso.</li>
      <li>Evite segurar ou empurrar demais a bola — o toque deve ser limpo.</li>
    </ul>
  </div>

  <div id="ataque" class="tab-content">
    <h2>💥 Como Fazer o Ataque (Cortada)</h2>
    <ul>
      <li>Corra em direção à bola e salte com os dois pés.</li>
      <li>Mantenha o braço dominante para trás, preparado para o golpe.</li>
      <li>Na altura máxima do salto, golpeie a bola com força e precisão.</li>
      <li>Use o punho aberto para melhor controle e direção.</li>
      <li>Evite tocar na rede e aterrisse com equilíbrio.</li>
    </ul>
  </div>

  <footer>
    <p>Site educativo • Criado com 🏐 amor ao vôlei</p>
  </footer>

  <script>
    function openTab(tabId) {
      const tabs = document.querySelectorAll('.tab-content');
      const buttons = document.querySelectorAll('.tab-button');

      tabs.forEach(tab => tab.classList.remove('active'));
      buttons.forEach(btn => btn.classList.remove('active'));

      document.getElementById(tabId).classList.add('active');
      event.target.classList.add('active');
    }
  </script>
</body>
</html><!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Como Jogar Vôlei</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #dbeafe, #f0f9ff);
      color: #1e3a8a;
    }

    header {
      background-color: #1e40af;
      color: white;
      text-align: center;
      padding: 30px 20px;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
    }

    .tabs {
      display: flex;
      justify-content: center;
      margin-top: 20px;
      flex-wrap: wrap;
    }

    .tab-button {
      padding: 15px 30px;
      background-color: #e0e7ff;
      border: none;
      border-radius: 8px 8px 0 0;
      cursor: pointer;
      font-weight: bold;
      margin: 0 5px;
      transition: background-color 0.3s;
    }

    .tab-button.active {
      background-color: #1e40af;
      color: white;
    }

    .tab-content {
      display: none;
      max-width: 900px;
      margin: auto;
      padding: 30px 20px;
      background-color: white;
      border-radius: 0 0 12px 12px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    }

    .tab-content.active {
      display: block;
    }

    h2 {
      color: #1e3a8a;
    }

    ul {
      padding-left: 20px;
    }

    footer {
      background-color: #1e40af;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Como Jogar Vôlei</h1>
    <p>Aprenda os principais fundamentos: Manchete, Levantamento e Ataque</p>
  </header>

  <div class="tabs">
    <button class="tab-button active" onclick="openTab('manchete')">Manchete</button>
    <button class="tab-button" onclick="openTab('levantamento')">Levantamento</button>
    <button class="tab-button" onclick="openTab('ataque')">Ataque</button>
  </div>

  <div id="manchete" class="tab-content active">
    <h2>🏐 Como Fazer a Manchete</h2>
    <ul>
      <li>Junte os antebraços, com as mãos unidas e esticadas.</li>
      <li>Dobre levemente os joelhos e mantenha os pés afastados na largura dos ombros.</li>
      <li>Espere a bola vir na altura da cintura.</li>
      <li>Toque nela com os antebraços, empurrando levemente com as pernas.</li>
      <li>Evite usar os braços — o movimento vem do corpo.</li>
    </ul>
  </div>

  <div id="levantamento" class="tab-content">
    <h2>📍 Como Fazer o Levantamento</h2>
    <ul>
      <li>Posicione as mãos na frente da testa, formando um triângulo com os dedos.</li>
      <li>Flexione levemente os joelhos e mantenha os cotovelos abertos.</li>
      <li>Toque na bola com a ponta dos dedos, empurrando para cima e para o atacante.</li>
      <li>O levantamento deve ser rápido e preciso.</li>
      <li>Evite segurar ou empurrar demais a bola — o toque deve ser limpo.</li>
    </ul>
  </div>

  <div id="ataque" class="tab-content">
    <h2>💥 Como Fazer o Ataque (Cortada)</h2>
    <ul>
      <li>Corra em direção à bola e salte com os dois pés.</li>
      <li>Mantenha o braço dominante para trás, preparado para o golpe.</li>
      <li>Na altura máxima do salto, golpeie a bola com força e precisão.</li>
      <li>Use o punho aberto para melhor controle e direção.</li>
      <li>Evite tocar na rede e aterrisse com equilíbrio.</li>
    </ul>
  </div>

  <footer>
    <p>Site educativo • Criado com 🏐 amor ao vôlei</p>
  </footer>

  <script>
    function openTab(tabId) {
      const tabs = document.querySelectorAll('.tab-content');
      const buttons = document.querySelectorAll('.tab-button');

      tabs.forEach(tab => tab.classList.remove('active'));
      buttons.forEach(btn => btn.classList.remove('active'));

      document.getElementById(tabId).classList.add('active');
      event.target.classList.add('active');
    }
  </script>
</body>
</html>

<!DOCTYPE html>

<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Pedra, Papel, Tesoura, Lagarto, Spock — jogo online multiplayer e modo offline contra a máquina.">
  <meta name="theme-color" content="#090a0f">

  <title>Pedra, Papel, Tesoura, Lagarto, Spock</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      min-height: 100%;
      background: #090a0f;
    }

    body {
      min-height: 100vh;
      font-family: Arial, Helvetica, sans-serif;
      background:
        radial-gradient(circle at top, #202743 0%, #0d1019 45%, #090a0f 100%);
      color: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 30px 16px;
    }

    .container {
      width: min(100%, 900px);
      text-align: center;
    }

    .logo {
      width: min(360px, 88vw);
      max-height: 55vh;
      object-fit: contain;
      display: block;
      margin: 0 auto 28px;
      border-radius: 24px;
      box-shadow:
        0 0 25px rgba(0, 200, 255, 0.18),
        0 0 60px rgba(0, 140, 255, 0.10);
    }

    h1 {
      font-size: clamp(2rem, 7vw, 4.2rem);
      line-height: 1.05;
      font-weight: 800;
      margin-bottom: 16px;
      letter-spacing: -1px;
    }

    .subtitle {
      max-width: 650px;
      margin: 0 auto 34px;
      color: #d2d5df;
      font-size: clamp(1rem, 3vw, 1.3rem);
      line-height: 1.5;
    }

    .buttons {
      display: grid;
      gap: 16px;
      max-width: 500px;
      margin: 0 auto;
    }

    .button {
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 62px;
      padding: 16px 20px;
      border-radius: 16px;
      text-decoration: none;
      color: #fff;
      font-size: 1.12rem;
      font-weight: 800;
      letter-spacing: 0.2px;
      background: linear-gradient(135deg, #1a2033, #2c3552);
      border: 1px solid rgba(255,255,255,0.13);
      box-shadow: 0 8px 30px rgba(0,0,0,0.2);
      transition: transform .2s ease, box-shadow .2s ease;
    }

    .button:hover {
      transform: translateY(-3px);
      box-shadow: 0 14px 36px rgba(0,0,0,0.28);
    }

    .download {
      background: linear-gradient(135deg, #087d5b, #00ad7d);
    }

    .cards {
      margin-top: 35px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 14px;
    }

    .card {
      padding: 19px;
      border-radius: 16px;
      background: rgba(255,255,255,0.045);
      border: 1px solid rgba(255,255,255,0.08);
      color: #cfd3dd;
    }

    .card strong {
      display: block;
      color: #fff;
      font-size: 1rem;
      margin-bottom: 8px;
    }

    footer {
      margin-top: 36px;
      color: #7f8491;
      font-size: .9rem;
    }

    @media (max-width: 600px) {
      body {
        padding: 22px 14px;
      }

      .logo {
        width: min(340px, 92vw);
        max-height: 48vh;
        margin-bottom: 22px;
      }

      h1 {
        font-size: 2rem;
      }

      .button {
        min-height: 58px;
        font-size: 1rem;
      }

      .cards {
        grid-template-columns: 1fr;
      }
    }
  </style>

</head>

<body>

  <main class="container">

```
<img
  class="logo"
  src="ChatGPT%20Image%2030%20de%20ago.%20de%202026,%2022_07_31.png"
  alt="Pedra, Papel, Tesoura, Lagarto, Spock"
>

<h1>Pedra, Papel, Tesoura, Lagarto, Spock</h1>

<p class="subtitle">
  Jogue online com seus amigos ou enfrente a máquina no modo offline.
</p>

<div class="buttons">

  <a
    class="button"
    href="https://rock-paper-lizard-spock-showdown.lovable.app"
    target="_blank"
    rel="noopener noreferrer"
  >
    🌐 JOGAR ONLINE
  </a>

  <a
    class="button download"
    href="Pedra-Papel-Tesoura-Lagarto-Spock.apk"
    download
  >
    📱 BAIXAR PARA ANDROID
  </a>

</div>

<section class="cards">

  <div class="card">
    <strong>🌐 Multiplayer</strong>
    Jogue online com seus amigos através das salas.
  </div>

  <div class="card">
    <strong>🤖 Modo Offline</strong>
    Enfrente a máquina mesmo sem internet.
  </div>

  <div class="card">
    <strong>📱 Android</strong>
    Baixe o aplicativo e instale no seu celular.
  </div>

</section>

<footer>
  © 2026 Pedra, Papel, Tesoura, Lagarto, Spock
</footer>
```

  </main>

</body>
</html>

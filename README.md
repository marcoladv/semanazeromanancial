<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Semana Zero</title>

  <!-- Preload fontes -->
  <link rel="preload" href="fonts/vela-sans-regular.woff2" as="font" type="font/woff2" crossorigin>
  <link rel="preload" href="fonts/vela-sans-bold.woff2" as="font" type="font/woff2" crossorigin>

  <style>
    /* ===========================
       FONTES
    ============================ */
    @font-face {
      font-family: "VelaSans";
      src: url("fonts/vela-sans-regular.woff2") format("woff2");
      font-weight: 400;
      font-style: normal;
      font-display: swap;
    }
    @font-face {
      font-family: "VelaSans";
      src: url("fonts/vela-sans-bold.woff2") format("woff2");
      font-weight: 700;
      font-style: normal;
      font-display: swap;
    }

    /* ===========================
       BASE
    ============================ */
    :root {
      --c1: #E4E5F2;
      --c2: #2A3EF4;
    }

    body {
      margin: 0;
      font-family: "VelaSans", sans-serif;
      line-height: 1.7;
      background: linear-gradient(90deg, var(--c1) 0%, var(--c1) 33%, var(--c2) 33%, var(--c2) 100%);
min-height: 100vh;
      color: var(--c1); /* cor do texto */
    }

    header {
      display: grid;
      place-items: center;
      padding: 32px 16px 0;
    }
    header img {
      max-width: 160px;
      height: auto;
    }

    .container {
      max-width: 760px;
      margin: 64px auto 64px;
      padding: 0 24px;
    }

    /* ===========================
       TIPOGRAFIA
    ============================ */
    h1 {
      text-align: center;
      margin: 8px 0 32px;
      font-family: "VelaSans", sans-serif;
      font-weight: 700;
      font-size: 20px; /* 4px maior que corpo (16px) */
      letter-spacing: 0.5px;
    }

    h2 {
      margin: 0 0 12px;
      font-family: "VelaSans", sans-serif;
      font-weight: 700;
      font-size: 18px; /* 2px maior que corpo */
    }

    p {
      margin: 0 0 16px;
      font-family: "VelaSans", sans-serif;
      font-weight: 400;
      font-size: 16px;
    }

    .devocional {
      margin: 0 0 32px;
      padding: 0 0 24px;
      border-bottom: 1px solid rgba(228,229,242,0.3);
    }
    .devocional:last-child {
      border-bottom: 0;
      padding-bottom: 0;
    }
  </style>
</head>
<body>
  <header>
    <!-- Troque por sua logo real -->
    <img src="logo.png" alt="Logo da Igreja" />
  </header>

  <main class="container">
    <h1>SEMANA ZERO</h1>

    <article class="devocional">
      <h2>Título</h2>
      <p>Devocional...</p>
    </article>

    <article class="devocional">
      <h2>Título</h2>
      <p>Devocional...</p>
    </article>
  </main>
</body>
</html>


<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AURELIAN — Luxury Performance</title>  <!-- Google Fonts -->  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">  <style>
    :root {
      --black: #0b0b0c;
      --gold: #c9a24d;
      --dark-gold: #9f7c32;
      --white: #f5f5f5;
      --gray: #9a9a9a;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: var(--black);
      color: var(--white);
      overflow-x: hidden;
    }

    /* NAVBAR */
    header {
      position: fixed;
      width: 100%;
      top: 0;
      z-index: 1000;
      padding: 24px 80px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: rgba(0,0,0,0.35);
      backdrop-filter: blur(12px);
    }

    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 26px;
      letter-spacing: 3px;
      color: var(--gold);
    }

    nav a {
      margin-left: 40px;
      text-decoration: none;
      color: var(--white);
      font-weight: 300;
      position: relative;
    }

    nav a::after {
      content: '';
      position: absolute;
      width: 0;
      height: 1px;
      background: var(--gold);
      left: 0;
      bottom: -6px;
      transition: width 0.3s ease;
    }

    nav a:hover::after {
      width: 100%;
    }

    /* HERO */
    .hero {
      height: 100vh;
      background: linear-gradient(120deg, #050505, #111);
      display: flex;
      align-items: center;
      padding: 0 80px;
      position: relative;
    }

    .hero-content {
      max-width: 700px;
      animation: fadeUp 1.5s ease forwards;
    }

    .hero h2 {
      font-family: 'Playfair Display', serif;
      font-size: 72px;
      line-height: 1.1;
      margin-bottom: 24px;
    }

    .hero h2 span {
      color: var(--gold);
    }

    .hero p {
      font-size: 18px;
      color: var(--gray);
      margin-bottom: 40px;
      max-width: 520px;
    }

    .btn {
     

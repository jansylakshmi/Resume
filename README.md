<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Jhansy Lakshmi | DevOps & AWS Cloud Engineer</title>

  <!-- Fonts & Icons -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

  <style>
    :root {
      --bg: #0d1117;
      --card: #161b22;
      --primary: #58a6ff;
      --secondary: #c77dff;
      --text: #e6edf3;
      --muted: #8b949e;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: var(--bg);
      color: var(--text);
      overflow-x: hidden;
    }

    /* Floating background animation */
    body::before {
      content: "";
      position: fixed;
      width: 200%;
      height: 200%;
      background: radial-gradient(circle at 20% 20%, #1f6feb22, transparent 40%),
                  radial-gradient(circle at 80% 30%, #c77dff22, transparent 40%),
                  radial-gradient(circle at 50% 80%, #58a6ff22, transparent 40%);
      animation: floatBg 20s linear infinite;
      z-index: -1;
    }

    @keyframes floatBg {
      0% { transform: translate(0,0); }
      50% { transform: translate(-5%, -5%); }
      100% { transform: translate(0,0); }
    }

    header {
      text-align: center;
      padding: 90px 20px 60px;
    }

    h1 {
      font-size: clamp(36px, 6vw, 56px);
      margin: 0;
      animation: fadeDown 1.2s ease;
    }

    @keyframes fadeDown {
      from { opacity: 0; transform: translateY(-30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .typing {
      font-size: 20px;
      color: var(--primary);
      height: 28px;
      margin-top: 12px;
    }

    .actions {
      margin-top: 30px;
      display: flex;
      justify-content: center;
      gap: 14px;
      flex-wrap: wrap;
    }

    .btn {
      padding: 12px 20px;
      border-radius: 10px;
      border: 1px solid #30363d;
      background: var(--card);
      color: var(--text);
      font-weight: 600;
      transition: all .3s ease;
    }

    .btn:hover {
      transform: translateY(-3px);
      background: linear-gradient(135deg, var(--primary), var(--secondary));
      color: #000;
    }

    main {
      max-width: 1100px;
      margin: auto;
      padding: 0 20px 80px;
    }

    section {
      margin-top: 60px;
      animation: fadeUp 1.2s ease both;
    }

    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(40px); }
      to { opacity: 1; transform: translateY(0); }
    }

    h2 {
      border-left: 4px solid var(--primary);
      padding-left: 12px;
      margin-bottom: 20px;
    }

    .card {
      background: var(--card);
      padding: 24px;
      border-radius: 16px;
      margin-bottom: 24px;
      border: 1px solid #30363d;
      transition: transform .3s, box-shadow .3s;
    }

    .card:hover {
      transform: translateY(-6px);
      box-shadow: 0 20px 40px rgba(0,0,0,.4);
    }

    .skills {

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
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .skill {
      background: #0d1117;
      padding: 8px 14px;
      border-radius: 999px;
      border: 1px solid #30363d;
      font-size: 14px;
      transition: all .3s;
    }

    .skill:hover {
      background: var(--primary);
      color: #000;
    }

    footer {
      text-align: center;
      padding: 30px 20px;
      color: var(--muted);
      border-top: 1px solid #30363d;
    }

    a { color: var(--primary); text-decoration: none; }

    @media(max-width: 768px) {
      .typing { font-size: 16px; }
    }
  </style>
</head>
<body>

<header>
  <h1>Jhansy Lakshmi</h1>
  <div class="typing" id="typing"></div>

  <div class="actions">
    <a class="btn" href="mailto:jansylakshmicglr@gmail.com"><i class="fa-solid fa-envelope"></i> Email</a>
    <a class="btn" href="https://linkedin.com/in/jhansy-lakshmi-23b710329"><i class="fa-brands fa-linkedin"></i> LinkedIn</a>
    <a class="btn" href="#projects"><i class="fa-solid fa-diagram-project"></i> Projects</a>
  </div>
</header>

<main>

<section>
  <h2>Professional Summary</h2>
  <div class="card">
    Highly driven and detail-oriented <strong>DevOps & AWS Cloud Engineer</strong> with strong hands-on experience in cloud deployment, CI/CD automation, containerization, and infrastructure monitoring. Passionate about building secure, scalable, and cost-efficient cloud solutions.
  </div>
</section>

<section>
  <h2>Technical Skills</h2>
  <div class="card skills">
    <span class="skill">AWS (EC2, VPC, S3, IAM, ALB, RDS)</span>
    <span class="skill">Jenkins & CI/CD</span>
    <span class="skill">Docker</span>
    <span class="skill">Kubernetes</span>
    <span class="skill">Terraform</span>
    <span class="skill">Ansible</span>
    <span class="skill">Linux</span>
    <span class="skill">Shell Scripting</span>
    <span class="skill">CloudWatch & CloudTrail</span>
    <span class="skill">Git & GitHub</span>
  </div>
</section>

<section id="projects">
  <h2>Projects</h2>

  <div class="card">
    <h3>Scalable & Secure E-Commerce Application (AWS)</h3>
    <p>Multi-tier VPC architecture, EC2 Auto Scaling, ALB, S3, IAM, CloudWatch, SNS, SQS.</p>
  </div>

  <div class="card">
    <h3>Event-Driven Log Monitoring & Alerting</h3>
    <p>CloudWatch Agent, metric filters, real-time alerts using SNS.</p>
  </div>

  <div class="card">
    <h3>CI/CD Pipeline for Static Web Application</h3>
    <p>Git → Jenkins → Docker → ECR → EC2 automated deployment pipeline.</p>
  </div>
</section>

<section>
  <h2>Education & Certification</h2>
  <div class="card">
    <p><strong>MSc – Applied Statistics</strong><br>Sri Venkateswara University</p>
    <p><strong>AWS Internship Certificate</strong></p>
  </div>
</section>

<section>
  <h2>Career Gap (2021 – 2024)</h2>
  <div class="card">
    Prepared for competitive government exams while continuously upskilling in AWS, DevOps tools, Linux administration, and completing hands-on cloud projects.
  </div>
</section>

</main>

<footer>
  © 2025 Jhansy Lakshmi | DevOps & Cloud Engineer
</footer>

<script>
  const roles = [
    "DevOps Engineer",
    "AWS Cloud Engineer",
    "Linux Administrator",
    "CI/CD Automation Enthusiast"
  ];
  let index = 0;
  let charIndex = 0;
  const typing = document.getElementById("typing");

  function type() {
    if (charIndex < roles[index].length) {
      typing.textContent += roles[index].charAt(charIndex);
      charIndex++;
      setTimeout(type, 80);
    } else {
      setTimeout(erase, 1500);
    }
  }

  function erase() {
    if (charIndex > 0) {
      typing.textContent = roles[index].substring(0, charIndex - 1);
      charIndex--;
      setTimeout(erase, 50);
    } else {
      index = (index + 1) % roles.length;
      setTimeout(type, 300);
    }
  }

  type();
</script>

</body>
</html>

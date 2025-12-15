<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Jhansy Lakshmi | DevOps & AWS Cloud Engineer</title>
  <style>
    :root {
      --bg: #0b1220;
      --card: #121a2f;
      --primary: #4cc9f0;
      --secondary: #b5179e;
      --text: #e6edf3;
      --muted: #9fb3c8;
      --accent: #4895ef;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: 'Segoe UI', Roboto, Arial, sans-serif;
      background: radial-gradient(1200px 600px at 10% -10%, #1b2a4a 0%, var(--bg) 40%), var(--bg);
      color: var(--text);
      line-height: 1.6;
    }
    a { color: var(--primary); text-decoration: none; }
    header {
      padding: 72px 20px 56px;
      text-align: center;
    }
    .badge {
      display: inline-block; padding: 6px 12px; border-radius: 999px;
      background: linear-gradient(135deg, var(--primary), var(--secondary));
      color: #001018; font-weight: 700; letter-spacing: .3px;
    }
    h1 {
      font-size: clamp(36px, 6vw, 56px);
      margin: 16px 0 8px;
      letter-spacing: .3px;
    }
    .subtitle { color: var(--muted); font-size: 18px; }

    .container { max-width: 1100px; margin: auto; padding: 0 20px 80px; }
    .grid {
      display: grid; grid-template-columns: repeat(12, 1fr); gap: 20px;
    }
    .card {
      grid-column: span 12;
      background: linear-gradient(180deg, #121a2f, #0f1630);
      border: 1px solid #1f2a44;
      border-radius: 18px; padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,.35);
      transition: transform .2s ease, box-shadow .2s ease;
    }
    .card:hover { transform: translateY(-4px); box-shadow: 0 18px 45px rgba(0,0,0,.45); }
    .card h2 { margin-top: 0; font-size: 26px; }
    .muted { color: var(--muted); }

    /* Skills */
    .skills { display: flex; flex-wrap: wrap; gap: 10px; }
    .skill {
      padding: 8px 12px; border-radius: 999px;
      background: #0f1b3a; border: 1px solid #22305a; color: #cfe3ff;
      font-size: 14px;
    }

    /* Two/Three column layout */
    .col-6 { grid-column: span 6; }
    .col-4 { grid-column: span 4; }
    .col-8 { grid-column: span 8; }
    @media (max-width: 900px) {
      .col-6, .col-4, .col-8 { grid-column: span 12; }
    }

    /* Project cards */
    .project { border-left: 4px solid var(--accent); }
    .project h3 { margin: 0 0 8px; }
    ul { margin: 8px 0 0 18px; }

    /* Footer */
    footer {
      text-align: center; padding: 28px 20px; color: var(--muted);
      border-top: 1px solid #1f2a44; background: #0a1022;
    }

    /* Buttons */
    .actions { display: flex; gap: 12px; justify-content: center; margin-top: 18px; }
    .btn {
      padding: 12px 18px; border-radius: 12px; font-weight: 700;
      border: 1px solid #243a6b; background: #0f1b3a; color: #d9ecff;
    }
    .btn.primary {
      background: linear-gradient(135deg, var(--primary), var(--secondary));
      color: #001018; border: none;
    }
  </style>
</head>
<body>
  <header>
    <span class="badge">DevOps & AWS Cloud Engineer</span>
    <h1>Jhansy Lakshmi</h1>
    <p class="subtitle">Cloud Deployment • CI/CD Automation • Containers • IaC • Monitoring</p>
    <div class="actions">
      <a class="btn primary" href="mailto:jansylakshmicglr@gmail.com">Email</a>
      <a class="btn" href="https://linkedin.com/in/jhansy-lakshmi-23b710329">LinkedIn</a>
      <a class="btn" href="#projects">Projects</a>
    </div>
  </header>

  <main class="container">
    <section class="grid">
      <!-- Professional Summary -->
      <div class="card col-8">
        <h2>Professional Summary</h2>
        <p>Highly driven and detail-oriented <strong>DevOps Engineer</strong> with strong hands-on experience in cloud deployment, CI/CD automation, configuration management, and container orchestration. Skilled in designing secure, scalable, and cost-efficient solutions on <strong>AWS</strong>. Adept at solving complex problems, optimizing infrastructure, and implementing automation that improves reliability.</p>
      </div>

      <!-- Contact / Location -->
      <div class="card col-4">
        <h2>Contact</h2>
        <p><strong>Email:</strong> <a href="mailto:jansylakshmicglr@gmail.com">jansylakshmicglr@gmail.com</a></p>
        <p><strong>Phone:</strong> +91 96035 62008</p>
        <p><strong>Location:</strong> Bangalore, India</p>
      </div>

      <!-- Technical Skills -->
      <div class="card col-12">
        <h2>Technical Skills</h2>
        <p class="muted">Cloud • Networking • DevOps • Containers • IaC • Monitoring • Systems</p>
        <div class="skills">
          <span class="skill">AWS: EC2</span><span class="skill">VPC</span><span class="skill">S3</span><span class="skill">IAM</span><span class="skill">ALB</span><span class="skill">Auto Scaling</span><span class="skill">ECR</span><span class="skill">ECS</span><span class="skill">Lambda</span><span class="skill">RDS</span>
          <span class="skill">Networking: Subnets</span><span class="skill">Routing</span><span class="skill">NAT</span><span class="skill">Security Groups</span><span class="skill">IGW</span>
          <span class="skill">CI/CD: Jenkins</span><span class="skill">Git</span><span class="skill">GitHub Actions</span>
          <span class="skill">Docker</span><span class="skill">Kubernetes</span><span class="skill">Ansible</span><span class="skill">Terraform</span>
          <span class="skill">Monitoring: CloudWatch</span><span class="skill">CloudTrail</span>
          <span class="skill">Linux</span><span class="skill">Shell Scripting</span><span class="skill">Python</span>
        </div>
      </div>

      <!-- Projects -->
      <div id="projects" class="card col-12">
        <h2>Project Experience</h2>

        <div class="project card">
          <h3>Scalable & Secure E-Commerce Application on AWS</h3>
          <p class="muted">EC2 • VPC • ALB • Auto Scaling • S3 • CloudWatch • CloudTrail • SNS • SQS • IAM</p>
          <ul>
            <li>Designed a multi-tier VPC with public/private subnets, NAT Gateway, and routing.</li>
            <li>Deployed EC2 Auto Scaling behind ALB for high availability and resilience.</li>
            <li>Implemented S3 versioning, access policies, and lifecycle rules.</li>
            <li>Configured CloudWatch alarms, CloudTrail auditing, SNS notifications, and SQS for async processing.</li>
            <li>Applied IAM least-privilege ac

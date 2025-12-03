<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MY_NAME — Site Reliability Engineer</title>
  <link rel="stylesheet" href="style.css" />
</head>

<body>

<div class="layout">

  <!-- SIDEBAR ---------------------------------------------------->
  <aside class="sidebar">
    <div class="name">MY_NAME</div>
    <div class="role">Site Reliability Engineer</div>

    <nav class="nav">
      <a href="#about">About</a>
      <a href="#experience">Experience</a>
      <a href="#skills">Skills</a>
      <a href="#tech">Tools & Technologies</a>
      <a href="#cv">Download CV</a>
    </nav>
  </aside>

  <!-- MAIN CONTENT ------------------------------------------------>
  <main class="content">

    <!-- ABOUT -->
    <section id="about">
      <h1>About Me</h1>
      <p>
        I'm an SRE with a background in pure mathematics who enjoys debugging distributed 
        systems, understanding how things work under the hood, and building reliable, 
        predictable platforms. I focus on Kubernetes, automation, observability, and 
        simplifying systems without losing technical depth.
      </p>
    </section>

    <!-- EXPERIENCE -->
    <section id="experience">
      <h1>Experience</h1>

      <h2>Senior Site Reliability Engineer — COMPANY_NAME</h2>
      <p class="time">2020 – 2024</p>
      <ul>
        <li>Owned the design of a multi-region AKS platform for authentication workloads.</li>
        <li>Built GitOps deployment with Terraform + FluxCD across all environments.</li>
        <li>Implemented full observability with OpenTelemetry, Prometheus, and Grafana.</li>
        <li>Reduced incident load by 80% via instrumentation and alerting redesign.</li>
        <li>Delivered a zero-downtime migration from on-prem to Azure.</li>
      </ul>

      <h2>Site Reliability Engineer — COMPANY_NAME</h2>
      <p class="time">2018 – 2020</p>
      <ul>
        <li>Migrated a legacy Ruby on Rails app to EKS, improving scalability and resilience.</li>
        <li>Rebuilt monitoring & alerting using Splunk; reduced false positives to near zero.</li>
        <li>Provided infra automation for ML workloads using Terraform and review workflows.</li>
      </ul>

      <h2>DevOps Engineer — COMPANY_NAME</h2>
      <p class="time">2015 – 2018</p>
      <ul>
        <li>Designed a custom container orchestration system before Kubernetes became mainstream.</li>
        <li>Helped build a tool that automated Kubernetes deployments for customer systems.</li>
        <li>Worked directly with clients, converting requirements into dependable infra.</li>
        <li>Mentored junior engineers in Linux, automation, and platform fundamentals.</li>
      </ul>
    </section>

    <!-- SKILLS -->
    <section id="skills">
      <h1>Skills</h1>
      <ul class="skills-list">
        <li>Kubernetes (AKS, EKS, Operators, Networking)</li>
        <li>Terraform, Helm, GitOps (FluxCD)</li>
        <li>Observability: OTel, Prometheus, Grafana</li>
        <li>Distributed systems debugging</li>
        <li>Go, Python, Bash</li>
        <li>Linux administration, L3/L4/L7 networking</li>
        <li>Incident response & reliability engineering</li>
      </ul>
    </section>

    <!-- TOOLS & TECH -->
    <section id="tech">
      <h1>Tools & Technologies</h1>

      <h3>Cloud & Platforms</h3>
      <p>Azure, AWS, on-prem Kubernetes</p>

      <h3>IaC & Automation</h3>
      <p>Terraform, Ansible, Helm, FluxCD</p>

      <h3>Observability</h3>
      <p>Prometheus, Loki, Mimir, OpenTelemetry</p>

      <h3>Systems & Networking</h3>
      <p>Linux internals, routing, load balancing, DNS, HTTP/2</p>
    </section>

    <!-- DOWNLOAD CV -->
    <section id="cv">
      <h1>Download CV</h1>
      <a class="cv-button" href="cv.pdf" download>Download PDF</a>
    </section>

  </main>
</div>

</body>
</html>


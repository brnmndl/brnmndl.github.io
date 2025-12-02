<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Barun Mandal - Site Reliability Engineer</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    :root {
      --bg: #ffffff;
      --text: #1a1a1a;
      --muted: #555;
      --accent: #2363d1;
      --border: #e5e5e5;
    }
    * { box-sizing: border-box; }
    html, body { margin: 0; padding: 0; background: var(--bg); color: var(--text); font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif; }
    a { color: var(--accent); text-decoration: none; }
    a:hover { text-decoration: underline; }
    .page {
      max-width: 980px;
      margin: 24px auto;
      padding: 24px;
    }
    header {
      display: grid;
      grid-template-columns: 1fr auto;
      gap: 16px;
      align-items: center;
      border-bottom: 1px solid var(--border);
      padding-bottom: 12px;
      margin-bottom: 16px;
    }
    .name { font-size: 28px; font-weight: 700; line-height: 1.2; }
    .title { font-size: 16px; color: var(--muted); }
    .contact { text-align: right; font-size: 14px; line-height: 1.6; }
    .contact p { margin: 0; }
    .grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
    }
    .section { margin-bottom: 14px; }
    .section h2 {
      font-size: 16px;
      font-weight: 700;
      letter-spacing: 0.02em;
      margin: 0 0 8px 0;
      text-transform: uppercase;
    }
    .muted { color: var(--muted); }
    ul { margin: 0; padding-left: 18px; }
    li { margin-bottom: 6px; }
    .item {
      margin-bottom: 10px;
    }
    .role {
      font-weight: 600;
    }
    .meta {
      font-size: 13px;
      color: var(--muted);
    }
    .badge {
      display: inline-block;
      border: 1px solid var(--border);
      border-radius: 6px;
      padding: 4px 8px;
      margin: 2px 6px 2px 0;
      font-size: 12px;
      white-space: nowrap;
    }
    /* Print: keep to one page, two columns */
    @page { size: A4; margin: 16mm; }
    @media print {
      .page { margin: 0; padding: 0; }
      a { color: inherit; text-decoration: none; }
    }
    /* Mobile: collapse to single column */
    @media (max-width: 820px) {
      .grid { grid-template-columns: 1fr; }
      .contact { text-align: left; }
    }
  </style>
</head>
<body>
  <main class="page">
    <header>
      <div>
        <div class="name"></div>
        <div class="name">Site Reliability Engineer</div>
      </div>
      <div class="contact">
        <p>Email: <a href="mailto:brnmndl@email.com">brnmndl@email.com</a></p>
        <p>Phone: +46 709201126</p>
      </div>
    </header>

    <div class="grid">
      <!-- Left column -->
      <section class="section">
        <h2>Profile</h2>
        <p class="muted">
            Site Reliability / Platform / DevOps Engineer with 10+ years of experience in designing, building, and scaling reliable systems across on-prem, AWS, and Azure environments. Strong expertise in observability and monitoring using the Grafana stack (Grafana, Mimir, Loki, Tempo, Prometheus) along with Thanos, Vector, Splunk and ELK stack.
        </p>
        <p class="muted">
            Proven skills in Kubernetes, CI/CD (Git, Jenkins), Ansible and Terraform, with deep experience in performance engineering using tools such as Gatling, Locust, JMeter, k6, LoadRunner and Neoload. Proficient in Go, Java, Python, Scala, C/C# and Shell scripting, with hands-on expertise in troubleshooting issues, application profiling, performance tuning and security testing (SQLi, XSS, etc).
        </p>
      </section>

      <section class="section">
        <h2>Core Skills</h2>
        <div>
          <span class="badge">SRE</span>
          <span class="badge">DevOps</span>
          <span class="badge">Observability</span>
          <span class="badge">SLI/SLO/Error Budgets</span>
          <span class="badge">Incident Response</span>
          <span class="badge">Automation</span>
          <span class="badge">Performance & Capacity Engineering</span>
          <span class="badge">Resilience & DR</span>
        </div>
      </section>

      <!-- Right column -->
      <section class="section">
        <h2>Experience</h2>
        <div class="item">
          <div class="role">Site Reliability Engineer — FDJ (La Française des Jeux)</div>
          <div class="meta">March 2025 - Stockholm, Sweden</div>
          <ul>
            <li>Owned reliability KPIs (SLIs/SLOs) and drove error budget policy across critical services.</li>
            <li>Improved observability with unified metrics, logs, and traces; reduced MTTR via runbooks.</li>
            <li>Automated deployments and operational tasks to eliminate TOIL and increase consistency.</li>
          </ul>
        </div>
        <div class="item">
          <div class="role">Site Reliability Engineer — Kindred Group plc</div>
          <div class="meta">Jun 2021 - Mar 2025 • Stockholm, Sweden</div>
        </div>
        <div class="item">
          <div class="role">Performance Engineer — Derivco Sports</div>
          <div class="meta">Oct 2018 - Jun 2021 • Stockholm, Sweden</div>
        </div>
        <div class="item">
          <div class="role">Senior Consultant — PwC India</div>
          <div class="meta">Jan 2015 - Sep 2018 • Kolkata, India</div>
        </div>
        <div class="item">
          <div class="role">Performance Engineer — Cognizant</div>
          <div class="meta">Aug 2012 - Jan 2015 • Kolkata, India</div>
        </div>
      </section>

      <section class="section">
        <h2>Tooling</h2>
        <div>
          <span class="badge">Kubernetes</span>
          <span class="badge">Docker</span>
          <span class="badge">Terraform</span>
          <span class="badge">Ansible</span>
          <span class="badge">CI/CD (GitOps)</span>
          <span class="badge">Jenkins</span>
          <span class="badge">ArgoCD</span>
          <span class="badge">Grafana</span>
          <span class="badge">Prometheus</span>
          <span class="badge">Thanos</span>
          <span class="badge">Mimir</span>
          <span class="badge">InfluxDB</span>
          <span class="badge">Loki</span>
          <span class="badge">Tempo</span>
          <span class="badge">Instana</span>
          <span class="badge">Splunk</span>
          <span class="badge">ELK</span>
          <span class="badge">OpenTelemetry</span>
          <span class="badge">Vector</span>
          <span class="badge">Fluentd/FluentBit</span>
          <span class="badge">Python</span>
          <span class="badge">Go Lang</span>
          <span class="badge">Java</span>
          <span class="badge">Scala</span>
          <span class="badge">Bash</span>
          <span class="badge">C#</span>
          <span class="badge">On-prem (Openstack)</span>
          <span class="badge">AWS</span>
          <span class="badge">Azure</span>
          <span class="badge">Gatling</span>
          <span class="badge">Locust</span>
          <span class="badge">k6</span>
          <span class="badge">JMeter</span>
          <span class="badge">LoadRunner</span>
        </div>
      </section>

      <!-- Left column (continued) -->
      <section class="section">
        <h2>Projects</h2>
        <div class="item">
          <div class="role">Observability Platform Modernization</div>
          <div class="meta">Prometheus + Thanos/Mimir + Vector/OTel + Loki + Tempo + Grafana • 2025</div>
          <ul>
            <li>Migrated fragmented monitoring to a unified stack running in k8s with service-level dashboards and alerts.</li>
            <li>Reduced false positives by tuning alerting with multi-signal correlation and SLO-based alerts.</li>
          </ul>
        </div>
        <div class="item">
          <div class="role">Deployment Automation</div>
          <div class="meta"> GitOps + ArgoCD/Jenkins + Terraform + Ansible • 2025</div>
          <ul>
            <li>Implemented GitOps workflows, standardized environments, and minimized manual changes.</li>
          </ul>
        </div>
      </section>

      <!-- Right column (continued) -->
      <section class="section">
        <h2>Education</h2>
        <div class="item">
          <div class="role">Bachelor of Engineering</div>
          <div class="meta">Indian Institute of Engineering Science and Technology, Shibpur, India</div>
          <div class="meta">10+2+4</div>
          <div class="meta">2008-2012</div>
        </div>
        <div class="item">
          <div class="role">High School, Science</div>
          <div class="meta">Purulia Zilla School, India</div>
          <div class="meta">10+2</div>
          <div class="meta">1998-2008</div>
        </div>
      </section>

      <section class="section">
        <h2>Certifications</h2>
        <ul>
          <li>Cloud Computing: Core Concepts — <a href="https://www.linkedin.com/learning/certificates/ec6aab078ae7267727a51148b525149d99aaf158e82aeccac58380f43853323f?trk=backfilled_certificate">Credential</a></li>
          <li>Microsoft Certified: Azure Fundamentals — <a href="https://www.credly.com/badges/b96985c2-eba5-4622-8aac-135d362f944f/linked_in_profile">Credential</a></li>
          <li>Interactive Python Dashboards with Plotly and Dash — <a href="https://www.udemy.com/certificate/UC-RNQ00DZZ/">Credential</a></li>
          <li>Machine Learning by Stanford University (online) — <a href="https://www.coursera.org/account/accomplishments/certificate/PY5ZNCQMV467">Credential</a></li>
          <li>Python 3 — <a href="https://www.sololearn.com/en/Profile/1519398/">Credential</a></li>
        </ul>
      </section>

      <section class="section">
        <h2>Links</h2>
        <ul>
          <li>LinkedIn: <a href="https://www.linkedin.com/in/barun-mandal-12660817">barun-mandal-12660817</a></li>
          <li>GitHub: <a href="https://github.com/brnmndl">brnmndl</a></li>
          <li>Portfolio: <a href="https://brnmndl.github.io">brnmndl.github.io</a></li>
        </ul>
      </section>
    </div>
  </main>
</body>
</html>

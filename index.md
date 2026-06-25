<html lang="en">
<head>
<meta charset="UTF-8" />
<title>Barun Mandal — Site Reliability & Platform Engineer</title>
<meta name="viewport" content="width=device-width, initial-scale=1" />
<style>
  :root {
    --bg:#fff; --text:#1a1a1a; --muted:#555; --accent:#2363d1; --border:#e5e5e5;
  }
  *{box-sizing:border-box}
  html,body{margin:0;padding:0;background:var(--bg);color:var(--text);
    font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
    font-size:10.5px; line-height:1.35;}
  a{color:var(--accent);text-decoration:none}
  a:hover{text-decoration:underline}
  .page{max-width:980px;margin:0 auto;padding:14mm 14mm;}
  header{display:grid;grid-template-columns:1fr auto;gap:16px;align-items:end;
    border-bottom:2px solid var(--text);padding-bottom:8px;margin-bottom:10px;}
  .name{font-size:24px;font-weight:700;line-height:1.1;letter-spacing:-0.01em}
  .title{font-size:12px;color:var(--muted);margin-top:2px;text-transform:uppercase;letter-spacing:0.08em}
  .contact{text-align:right;font-size:11px;line-height:1.5;color:var(--muted)}
  .contact p{margin:0}
  .grid{display:grid;grid-template-columns:1.6fr 1fr;gap:18px}
  .section{margin-bottom:9px}
  h2{font-size:11px;font-weight:700;letter-spacing:0.1em;margin:0 0 5px 0;
    text-transform:uppercase;color:var(--accent);
    border-bottom:1px solid var(--border);padding-bottom:2px;}
  p{margin:0 0 4px 0}
  ul{margin:2px 0 4px 0;padding-left:14px}
  li{margin-bottom:2px}
  .item{margin-bottom:6px}
  .role{font-weight:600;font-size:16px}
  .meta{font-size:13px;color:var(--muted);margin-bottom:2px}
  .badge{display:inline-block;border:1px solid var(--border);border-radius:4px;
    padding:1px 6px;margin:1px 3px 1px 0;font-size:9px;white-space:nowrap;color:#333;background:#fafafa}
  @page{size:A4;margin:0}
  @media print{ a{color:inherit} }
</style>
</head>
<body>
<div class="page">

  <header>
    <div>
      <div class="name">BARUN MANDAL</div>
      <div class="title">Site Reliability & Platform Engineer</div>
    </div>
    <div class="contact">
      <p><a href="mailto:brnmndl@gmail.com">brnmndl@gmail.com</a></p>
      <p>+46 709 201 126</p>
      <p>Stockholm, Sweden</p>
      <p><a href="https://www.linkedin.com/in/barun-mandal-12660817/">Linkedin</a> |
         <a href="https://github.com/brnmndl">Github</a> |
         <a href="https://brnmndl.github.io">Portfolio</a></p>
    </div>
  </header>

  <div class="section">
    <h2>Profile</h2>
    <p>Site Reliability & Platform Engineer with <strong>14+ years</strong> designing, building and operating reliable systems on Kubernetes. Deep expertise in observability with the <strong>Grafana stack</strong> and others. Open-source-minded, comfortable in owning services end-to-end — from design docs and clean, maintainable code to CI/CD, IaC, on-call troubleshooting, performance engineering & tuning, incident response and mentoring. Strong in Go, Python and Java and experienced with relational stores (PostgreSQL, MySQL, SQLite).</p>
  </div>

  <div class="grid">
    <div>
      <div class="section">
        <h2>Experience</h2>

        <div class="item">
          <div class="role">Site Reliability Engineer — FDJ (La Française des Jeux)</div>
          <div class="meta">Mar 2025 – Present · Stockholm, Sweden</div>
          <ul>
            <li>Own reliability KPIs (SLIs/SLOs) and error-budget policy across critical services.</li>
            <li>Unified metrics, logs and traces; reduced MTTR via structured runbooks and automated alerting.</li>
            <li>Operate large-scale production Kubernetes — on-call, incident response and blameless postmortems.</li>
            <li>Built AI agents and MCP server integrations for metrics discovery and anomaly detection, cutting alert noise and accelerating triage.</li>
          </ul>
        </div>

        <div class="item">
          <div class="role">Site Reliability Engineer — Kindred Group plc</div>
          <div class="meta">Jun 2021 – Mar 2025 · Stockholm, Sweden</div>
          <ul>
            <li>Modernised observability platform (Prometheus + Thanos/Mimir, Loki, Tempo, Grafana, OpenTelemetry).</li>
            <li>Standardised GitOps deployments with ArgoCD, Terraform and Ansible across multi-cluster Kubernetes.</li>
            <li>Led performance & capacity engineering for high-traffic betting platforms.</li>
          </ul>
        </div>

        <div class="item">
          <div class="role">Performance Engineer — Derivco Sports</div>
          <div class="meta">Oct 2018 – Jun 2021 · Stockholm, Sweden</div>
          <ul>
            <li>Designed load and stress testing strategies with Gatling, k6, JMeter and LoadRunner.</li>
            <li>Profiled and tuned JVM/Go services, reducing tail latency and infrastructure cost.</li>
          </ul>
        </div>

        <div class="item">
          <div class="role">Senior Consultant — PwC India</div>
          <div class="meta">Jan 2015 – Sep 2018 · Kolkata, India</div>
          <ul><li>Performance & reliability consulting for enterprise clients; security testing (SQLi, XSS).</li></ul>
        </div>

        <div class="item">
          <div class="role">Performance Engineer — Cognizant</div>
          <div class="meta">Aug 2012 – Jan 2015 · Kolkata, India</div>
          <ul><li>Performance testing and tuning for large-scale enterprise applications.</li></ul>
        </div>
      </div>

      <div class="section">
        <h2>Selected Projects</h2>
        <div class="item">
          <div class="role">Observability Platform Modernisation</div>
          <div class="meta">Prometheus · Thanos/Mimir · Vector/OTel · Loki · Tempo · Grafana</div>
          <ul>
            <li>Migrated fragmented monitoring to a unified, cloud-native stack on Kubernetes with service-level dashboards and full metrics–logs–traces correlation.</li>
            <li>Improved alerting accuracy through SLO-based alerting and signal correlation.</li>
          </ul>
        </div>
        <div class="item">
          <div class="role">Deployment Automation</div>
          <div class="meta">GitOps · ArgoCD · Jenkins · Terraform · Ansible · Kubernetes</div>
          <ul>
            <li>Implemented GitOps workflows with ArgoCD, standardising environment config and eliminating manual drift through declarative IaC.</li>
          </ul>
        </div>
      </div>
    </div>

    <div>
      <div class="section">
        <h2>Core Skills</h2>
        <span class="badge">SRE</span><span class="badge">Observability</span><span class="badge">SLI/SLO</span>
        <span class="badge">Error Budgets</span><span class="badge">DevOps</span><span class="badge">Platform Engineering</span>
        <span class="badge">Incident Response</span><span class="badge">Automation</span>
        <span class="badge">Performance & Capacity</span><span class="badge">Resilience & DR</span>
      </div>

      <div class="section">
        <h2>Tooling</h2>
        <p style="margin-bottom:4px"><strong>Orchestration & IaC:</strong> Kubernetes, Docker, Terraform, Ansible, ArgoCD, Jenkins, GitOps</p>
        <p style="margin-bottom:4px"><strong>Observability:</strong> Grafana, Prometheus, Thanos, Mimir, Loki, Tempo, OpenTelemetry, Vector, Fluentd/Bit, InfluxDB, Victoria, Instana, Splunk, ELK</p>
        <p style="margin-bottom:4px"><strong>Cloud:</strong> AWS, Azure, On-prem (OpenStack)</p>
        <p style="margin-bottom:4px"><strong>Languages:</strong> Go, Python, Java, Scala, C#, Bash</p>
        <p><strong>Performance:</strong> Gatling, Locust, k6, JMeter, LoadRunner, Neoload</p>
      </div>

      <div class="section">
        <h2>Education</h2>
        <div class="item">
          <div class="role">B.E., Engineering</div>
          <div class="meta">Indian Institute of Engineering Science and Technology, Shibpur · 2008–2012</div>
        </div>
        <div class="item">
          <div class="role">High School, Science</div>
          <div class="meta">Purulia Zilla School, India · 1998–2008</div>
        </div>
      </div>

      <div class="section">
        <h2>Certifications</h2>
        <ul>
          <li>Microsoft Certified: Azure Fundamentals</li>
          <li>Cloud Computing: Core Concepts</li>
          <li>Machine Learning — Stanford University (online)</li>
          <li>Interactive Python Dashboards with Plotly & Dash</li>
          <li>Python 3</li>
        </ul>
      </div>
    </div>
  </div>

</div>
</body>
</html>

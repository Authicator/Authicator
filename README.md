[dossier.html](https://github.com/user-attachments/files/29602823/dossier.html)
<meta name="description" content="Victor Okeke — Security Engineering Portfolio. Human-centered security, offensive labs, incident response, and secure web architecture. Open to opportunities.">
# Victor Okeke · "Big Drift"

**Cybersecurity Enthusiast & Human-Centered Security Advocate**  
Anambra State, Nigeria

[![Email](https://img.shields.io/badge/Email-you@example.com-blue?style=flat-square&logo=gmail)](mailto:you@example.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-bigdrift-blue?style=flat-square&logo=linkedin)](https://linkedin.com/in/bigdrift)
[![GitHub](https://img.shields.io/badge/GitHub-bigdrift-181717?style=flat-square&logo=github)](https://github.com/bigdrift)

---

## About Me

I focus on the side of security most people overlook: **behavior and trust matter as much as technology**. I build hands-on experience through CTF challenges and labs — Kali Linux, Metasploit — to understand real-world attacks, while completing a **B.Sc. in Cybersecurity** at Federal University Otuoke and the **ICE HUB Ethical Hacking Programme**. With a background in graphic design, I also translate security concepts into things people actually understand and act on.

**Actively seeking internships, junior security, and security-focused development roles.**

---

## Core Competencies

| Competency | Area |
|------------|------|
| Human-Centered Security | Behavior & Trust |
| Security Awareness & Culture | Risk Communication |
| Offensive Security Labs | Kali Linux / Metasploit |
| Network Traffic Analysis | Wireshark |
| Cryptographic Engineering | AES-256 / OpenSSL |
| Enumeration & Recon | Gobuster / Hydra |
| Incident Response | SHA-256 Audits |
| Secure Web Architecture | CSP / HSTS |
| Security Communication Design | Graphic Design |
| Full-Stack Development | JS / React / Workers |

---

## Case Files — Applied Work

### CASE 001 · V-Net Online Cafe · `IN PRODUCTION`

A live campus platform serving hundreds of university students — registration support, document services, and CV writing. Built and hardened end-to-end.

- **Stack:** Cloudflare Pages · Workers · D1 · R2
- **Security:** Rate limiting · MIME allowlisting · CSP/HSTS

---

### CASE 002 · Breach Integrity & Recovery Exercise · `COMPLETED`

Simulated incident response exercise: file integrity verification, encrypted vault engineering, and traffic analysis, reported against Nigeria's NDPC 72-hour breach disclosure standard.

- **Method:** SHA-256 audit · AES-256-CBC vault
- **Deliverable:** Formatted incident report

---

### CASE 003 · Controlled-Environment Penetration Exercise · `COMPLETED`

Enumeration and credential-testing exercise on a sanctioned training target, with a documented, methodology-first report from recon through flag capture.

- **Method:** Gobuster enumeration · brute-force methodology
- **Scope:** Authorized CTF training environment

---

## Training Record

- **B.Sc. Cybersecurity** — Federal University Otuoke *(300 Level · In Progress)*
- **ICE HUB Cybersecurity & Ethical Hacking Programme** — Active *(Incident Response, Network Security, Offensive Tooling)*
- **Cloud Security Track** — Planned

---

## Contact

- **Email:** [you@example.com](mailto:you@example.com)
- **LinkedIn:** [linkedin.com/in/bigdrift](https://linkedin.com/in/bigdrift)
- **GitHub:** [github.com/bigdrift](https://github.com/bigdrift)

---

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Big Drift — Security Engineering Portfolio</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:wght@400;500;600;700&family=IBM+Plex+Mono:wght@400;500;600&display=swap');

  :root{
    --paper: #F4F5F2;
    --panel: #FFFFFF;
    --ink: #1B1E1C;
    --sub: #565B57;
    --line: #D7DAD3;
    --navy: #1B3A5C;
    --signal: #A8391F;
    --ok: #2F6B4F;
  }

  *{box-sizing:border-box; margin:0; padding:0;}
  body{
    background:var(--paper);
    color:var(--ink);
    font-family:'IBM Plex Sans', sans-serif;
    line-height:1.5;
    -webkit-font-smoothing:antialiased;
  }
  .mono{font-family:'IBM Plex Mono', monospace;}
  ::selection{background:var(--navy); color:#fff;}

  .sheet{max-width:840px; margin:40px auto; background:var(--panel); border:1px solid var(--line);}

  /* doc control bar */
  .docbar{
    display:flex; justify-content:space-between; align-items:center;
    padding:12px 28px; border-bottom:1px solid var(--line);
    font-family:'IBM Plex Mono'; font-size:11px; letter-spacing:0.04em; color:var(--sub);
    background:#EEF0EB; flex-wrap:wrap; gap:8px;
  }
  .docbar b{color:var(--ink);}
  .status-pill{
    display:inline-flex; align-items:center; gap:6px;
    color:var(--ok); font-weight:600;
  }
  .status-pill::before{content:''; width:6px; height:6px; border-radius:50%; background:var(--ok);}

  /* header */
  .header{padding:56px 48px 40px; border-bottom:1px solid var(--line);}
  .ref{font-family:'IBM Plex Mono'; font-size:12px; color:var(--sub); letter-spacing:0.06em; margin-bottom:18px;}
  h1{
    font-size:44px; font-weight:700; letter-spacing:-0.01em; line-height:1.1;
    margin-bottom:10px;
  }
  .role{font-size:17px; color:var(--sub); font-weight:500; margin-bottom:28px;}
  .summary{max-width:620px; font-size:15.5px; color:#333; line-height:1.75;}
  .summary b{color:var(--ink); font-weight:600;}

  /* sections */
  section{padding:36px 48px; border-bottom:1px solid var(--line);}
  .sec-head{
    display:flex; align-items:baseline; gap:12px; margin-bottom:22px;
  }
  .sec-num{font-family:'IBM Plex Mono'; font-size:12px; color:var(--navy); font-weight:600;}
  .sec-title{font-size:13px; font-weight:600; letter-spacing:0.12em; text-transform:uppercase; color:var(--ink);}
  .sec-rule{flex:1; height:1px; background:var(--line);}

  /* competencies */
  .comp-grid{display:grid; grid-template-columns:1fr 1fr; gap:0; border:1px solid var(--line);}
  .comp{
    padding:16px 20px; border-bottom:1px solid var(--line); border-right:1px solid var(--line);
    display:flex; justify-content:space-between; align-items:center;
  }
  .comp:nth-child(2n){border-right:none;}
  .comp-name{font-size:14px; font-weight:500;}
  .comp-level{font-family:'IBM Plex Mono'; font-size:10px; letter-spacing:0.06em; color:var(--sub); text-transform:uppercase;}

  /* case files */
  .case{
    border:1px solid var(--line); margin-bottom:14px; padding:20px 22px;
  }
  .case-top{display:flex; justify-content:space-between; align-items:flex-start; gap:16px; margin-bottom:10px;}
  .case-id{font-family:'IBM Plex Mono'; font-size:11px; color:var(--sub); margin-bottom:4px;}
  .case-title{font-size:16px; font-weight:600;}
  .case-tag{
    font-family:'IBM Plex Mono'; font-size:10px; letter-spacing:0.06em; text-transform:uppercase;
    padding:4px 10px; border:1px solid currentColor; white-space:nowrap; flex-shrink:0;
  }
  .case-tag.active{color:var(--ok);}
  .case-tag.closed{color:var(--navy);}
  .case-desc{font-size:13.5px; color:var(--sub); line-height:1.6; max-width:560px;}
  .case-scope{
    display:flex; gap:18px; margin-top:12px; font-family:'IBM Plex Mono'; font-size:10.5px; color:var(--sub);
  }
  .case-scope span b{color:var(--ink); display:block; font-size:11px; margin-bottom:2px; font-family:'IBM Plex Sans'; font-weight:600;}

  /* training */
  .track{border-left:2px solid var(--line); padding-left:22px; margin-left:6px;}
  .track-item{position:relative; padding-bottom:22px;}
  .track-item:last-child{padding-bottom:0;}
  .track-item::before{
    content:''; position:absolute; left:-27px; top:4px; width:9px; height:9px;
    border-radius:50%; background:var(--panel); border:2px solid var(--navy);
  }
  .track-item.done::before{background:var(--navy);}
  .track-title{font-size:14px; font-weight:600;}
  .track-meta{font-family:'IBM Plex Mono'; font-size:11px; color:var(--sub); margin-top:2px;}

  /* footer / contact */
  .footer-block{padding:40px 48px; background:#EEF0EB;}
  .footer-label{font-family:'IBM Plex Mono'; font-size:11px; color:var(--sub); letter-spacing:0.08em; margin-bottom:14px;}
  .footer-row{display:flex; justify-content:space-between; align-items:flex-end; flex-wrap:wrap; gap:24px;}
  .prepared{font-size:14px; color:var(--ink); line-height:1.6;}
  .prepared b{font-weight:600;}
  .btn{
    display:inline-block; font-family:'IBM Plex Mono'; font-size:12px; letter-spacing:0.04em;
    background:var(--navy); color:#fff; padding:13px 26px; text-decoration:none; font-weight:500;
  }
  .btn:hover{background:#132a42;}
  .contact-links{font-family:'IBM Plex Mono'; font-size:12px; color:var(--sub); margin-top:10px;}
  .contact-links a{color:var(--navy); text-decoration:none;}
  .contact-links a:hover{text-decoration:underline;}

  @media(max-width:640px){
    .sheet{margin:0; border:none;}
    .header, section, .footer-block{padding:28px 22px;}
    h1{font-size:32px;}
    .comp-grid{grid-template-columns:1fr;}
    .comp{border-right:none;}
    .case-top{flex-direction:column;}
    .footer-row{align-items:flex-start;}
  }
</style>
</head>
<body>

<div class="sheet">

  <div class="docbar">
    <div>DOC REF: <b>BD-PORTFOLIO-2026</b> &nbsp;·&nbsp; REV 1.0</div>
    <div class="status-pill">ACTIVELY SEEKING OPPORTUNITIES</div>
  </div>

  <div class="header">
    <div class="ref">CANDIDATE PROFILE / SECURITY ENGINEERING</div>
    <h1>Victor Okeke</h1>
    <div class="role">"Big Drift" — Cybersecurity Enthusiast &amp; Human-Centered Security Advocate — Anambra State, Nigeria</div>
    <p class="summary">
      I focus on the side of security most people overlook: <b>behavior and trust matter as much as technology.</b>
      I build hands-on experience through CTF challenges and labs — Kali Linux, Metasploit — to understand
      real-world attacks, while completing a <b>B.Sc. in Cybersecurity</b> at Federal University Otuoke and the
      <b>ICE HUB Ethical Hacking Programme</b>. With a background in graphic design, I also translate security
      concepts into things people actually understand and act on.
    </p>
  </div>

  <section>
    <div class="sec-head">
      <span class="sec-num">01</span>
      <span class="sec-title">Core Competencies</span>
      <div class="sec-rule"></div>
    </div>
    <div class="comp-grid">
      <div class="comp"><span class="comp-name">Human-Centered Security</span><span class="comp-level">Behavior &amp; Trust</span></div>
      <div class="comp"><span class="comp-name">Security Awareness &amp; Culture</span><span class="comp-level">Risk Communication</span></div>
      <div class="comp"><span class="comp-name">Offensive Security Labs</span><span class="comp-level">Kali Linux / Metasploit</span></div>
      <div class="comp"><span class="comp-name">Network Traffic Analysis</span><span class="comp-level">Wireshark</span></div>
      <div class="comp"><span class="comp-name">Cryptographic Engineering</span><span class="comp-level">AES-256 / OpenSSL</span></div>
      <div class="comp"><span class="comp-name">Enumeration &amp; Recon</span><span class="comp-level">Gobuster / Hydra</span></div>
      <div class="comp"><span class="comp-name">Incident Response</span><span class="comp-level">SHA-256 Audits</span></div>
      <div class="comp"><span class="comp-name">Secure Web Architecture</span><span class="comp-level">CSP / HSTS</span></div>
      <div class="comp"><span class="comp-name">Security Communication Design</span><span class="comp-level">Graphic Design</span></div>
      <div class="comp"><span class="comp-name">Full-Stack Development</span><span class="comp-level">JS / React / Workers</span></div>
    </div>
  </section>

  <section>
    <div class="sec-head">
      <span class="sec-num">02</span>
      <span class="sec-title">Case Files — Applied Work</span>
      <div class="sec-rule"></div>
    </div>

    <div class="case">
      <div class="case-top">
        <div>
          <div class="case-id">CASE 001</div>
          <div class="case-title">V-Net Online Cafe</div>
        </div>
        <div class="case-tag active">IN PRODUCTION</div>
      </div>
      <div class="case-desc">
        A live campus platform serving hundreds of university students — registration support,
        document services, and CV writing. Built and hardened end-to-end.
      </div>
      <div class="case-scope">
        <span><b>Stack</b>Cloudflare Pages · Workers · D1 · R2</span>
        <span><b>Security</b>Rate limiting · MIME allowlisting · CSP/HSTS</span>
      </div>
    </div>

    <div class="case">
      <div class="case-top">
        <div>
          <div class="case-id">CASE 002</div>
          <div class="case-title">Breach Integrity &amp; Recovery Exercise</div>
        </div>
        <div class="case-tag closed">COMPLETED</div>
      </div>
      <div class="case-desc">
        Simulated incident response exercise: file integrity verification, encrypted vault
        engineering, and traffic analysis, reported against Nigeria's NDPC 72-hour breach
        disclosure standard.
      </div>
      <div class="case-scope">
        <span><b>Method</b>SHA-256 audit · AES-256-CBC vault</span>
        <span><b>Deliverable</b>Formatted incident report</span>
      </div>
    </div>

    <div class="case">
      <div class="case-top">
        <div>
          <div class="case-id">CASE 003</div>
          <div class="case-title">Controlled-Environment Penetration Exercise</div>
        </div>
        <div class="case-tag closed">COMPLETED</div>
      </div>
      <div class="case-desc">
        Enumeration and credential-testing exercise on a sanctioned training target, with
        a documented, methodology-first report from recon through flag capture.
      </div>
      <div class="case-scope">
        <span><b>Method</b>Gobuster enumeration · brute-force methodology</span>
        <span><b>Scope</b>Authorized CTF training environment</span>
      </div>
    </div>
  </section>

  <section>
    <div class="sec-head">
      <span class="sec-num">03</span>
      <span class="sec-title">Training Record</span>
      <div class="sec-rule"></div>
    </div>
    <div class="track">
      <div class="track-item done">
        <div class="track-title">B.Sc. Cybersecurity — Federal University Otuoke</div>
        <div class="track-meta">300 LEVEL · IN PROGRESS</div>
      </div>
      <div class="track-item done">
        <div class="track-title">ICE HUB Cybersecurity &amp; Ethical Hacking Programme</div>
        <div class="track-meta">ACTIVE · INCIDENT RESPONSE, NETWORK SECURITY, OFFENSIVE TOOLING</div>
      </div>
      <div class="track-item">
        <div class="track-title">Cloud Security Track</div>
        <div class="track-meta">PLANNED</div>
      </div>
    </div>
  </section>

  <div class="footer-block">
    <div class="footer-label">04 / CONTACT</div>
    <div class="footer-row">
      <div class="prepared">
        <b>Open to internships, junior security, and security-focused dev roles.</b>
        <div class="contact-links">
          <a href="mailto:you@example.com">you@example.com</a> &nbsp;·&nbsp;
          <a href="#">linkedin.com/in/bigdrift</a> &nbsp;·&nbsp;
          <a href="#">github.com/bigdrift</a>
        </div>
      </div>
    </div>
  </div>

</div>

</body>
</html>


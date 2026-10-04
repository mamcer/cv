<style>
:root {
    --primary-color: #1a2a3a;
    --accent-color: #34495e;
    --sidebar-bg: #f8f9fa;
    --text-main: #2c3e50;
    --text-muted: #5d6d7e;
}

body {
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
    font-size: 9.5pt;
    line-height: 1.4;
    color: var(--text-main);
    margin: 0;
    padding: 0;
    -webkit-font-smoothing: antialiased;
}

.cv-wrapper {
    display: grid;
    grid-template-columns: 230px 1fr;
    min-height: 297mm;
}

.sidebar {
    background-color: var(--sidebar-bg);
    padding: 26px 20px;
    border-right: 1px solid #eee;
}

.sidebar h3 {
    font-size: 10pt;
    color: var(--primary-color);
    text-transform: uppercase;
    letter-spacing: 1.5px;
    margin-top: 18px;
    margin-bottom: 8px;
    border-bottom: 1px solid #dcdde1;
    padding-bottom: 5px;
}

.sidebar ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

.sidebar li {
    font-size: 9pt;
    margin-bottom: 5px;
    color: var(--text-muted);
}

.main-col {
    padding: 26px 32px;
}

.main-col h1 {
    font-size: 22pt;
    color: var(--primary-color);
    margin: 0;
    font-weight: 700;
    letter-spacing: -0.5px;
}

.main-col .subtitle {
    font-size: 10.5pt;
    color: var(--accent-color);
    font-weight: 400;
    margin-top: 4px;
    margin-bottom: 10px;
}

.main-col h2 {
    font-size: 11.5pt;
    color: var(--primary-color);
    text-transform: uppercase;
    letter-spacing: 1px;
    border-bottom: 2px solid var(--primary-color);
    margin-top: 16px;
    margin-bottom: 8px;
    padding-bottom: 3px;
}

.experience-item {
    margin-bottom: 8px;
}

.experience-item h3 {
    font-size: 10.5pt;
    margin-top: 8px;
    margin-bottom: 2px;
    color: #000;
}

.experience-item .meta {
    display: flex;
    justify-content: space-between;
    font-size: 9pt;
    color: var(--text-muted);
    font-style: italic;
    margin-bottom: 3px;
}

.experience-item ul {
    padding-left: 18px;
    margin-top: 3px;
    margin-bottom: 0;
}

.date {
    font-weight: bold;
    color: var(--primary-color);
    font-style: normal;
}

@media print {
    @page { 
        margin: 0; 
        size: A4;
    }
    body {
        margin: 0;
        -webkit-print-color-adjust: exact;
    }
    .cv-wrapper {
        min-height: 297mm;
        height: 297mm; /* Forzamos altura A4 */
    }
}
</style>

<div class="cv-wrapper">

<div class="sidebar">

### CONTACT

- [mamcer@proton.me](mailto:mamcer@proton.me)
- [linkedin.com/in/mamcer](https://www.linkedin.com/in/mamcer)
- [github.com/mamcer](https://github.com/mamcer)
- [mamcer.github.io](https://mamcer.github.io/)
- Buenos Aires, Argentina

### CORE EXPERTISE

- Software Architecture
- Distributed Systems
- Engineering Leadership
- AI-assisted Development
- Fintech & Payments

### TECH STACK

**Languages:**
Go, Java, SQL (MySQL).

**Architecture:**
DDD, Hexagonal, Event-Driven.

**Platform:**
Docker, Kubernetes, Azure, CI/CD, Prometheus, Grafana, OpenTelemetry.

**AI tools:**
Claude Code, Gemini CLI.

### LANGUAGES

- **Spanish:** Native
- **English:** Full Professional
- **Portuguese:** Professional

</div>

<div class="main-col">

# MARIO MORENO
<div class="subtitle">Hands-on Engineering Leader | Software Architecture · Go · Distributed Systems | AI-assisted development | Fintech (Mercado Pago) · EV charging (VEMO)</div>

## SUMMARY

Systems engineer with 20+ years in software, most of them leading teams without leaving the technical work. Led engineering for Mercado Pago's Treasury & FX platform (daily FX volume from $50K to $6M USD, cross-border expansion from 2 to 5 countries). Now leading technology at VEMO (EV charging, Mexico): monolith modernization and AI-assisted development in day-to-day delivery.

## EXPERIENCE

<div class="experience-item">

### Senior Engineering Manager | VEMO
<div class="meta"><span>Technology Lead, VEMO Charging Network (EV charging, Mexico)</span> <span class="date">Sep 2025 – Present</span></div>

- Own the end-to-end architecture, scalability and availability of the VCN platform; leading the migration from a monolith to a modular hexagonal/clean architecture.
- Brought Claude Code into the team's daily development workflow.
- Shipped a new card payment experience (100% of users) and a discount engine built from scratch, with a team 36% smaller than the previous semester.
</div>

<div class="experience-item">

### Senior Engineering Manager | Mercado Libre
<div class="meta"><span>Mercado Pago Treasury & FX platform</span> <span class="date">Aug 2019 – May 2025</span></div>

- Scaled daily FX operations from $50K to **$6M USD avg** (120x); made the platform the company-wide source of truth for exchange rates, with direct Citi and JP Morgan settlement integrations.
- Led the re-architecture of the cross-border platform, enabling expansion from 2 to 5 countries.
- Operated high-traffic microservices for Crypto and Dollar MEP operations. Stack: Go, Java, MySQL, on Fury.
- Grew the team from 6 to 30+ engineers across Argentina, Brazil and Mexico.
</div>

<div class="experience-item">

### Senior Technical Lead | In All Media / DataArt
<div class="meta"><span>US energy and financial-services clients</span> <span class="date">Sep 2017 – Aug 2019</span></div>

- Technical lead and architect for distributed remote teams, from definition through delivery (.NET, SQL Server, PostgreSQL).
</div>

<div class="experience-item">

### Architect & Subject Matter Expert | Globant
<div class="meta"><span>Corporate Architecture Team</span> <span class="date">Oct 2013 – Aug 2017</span></div>

- Defined the company-wide CI/CD, code review and continuous inspection strategy; led design reviews across studios.
</div>

## PROJECTS

**Poor Man's Fury** (2026): an internal developer platform built from scratch on a single home server (K3s, Vault, CI/CD, Prometheus, Grafana, Loki, Tempo, OpenTelemetry, Backstage), documented in a 5-part series at mamcer.github.io.

## EDUCATION

**Systems Engineer (Software Engineering)**, UNICEN (UNCPBA), Argentina

</div>

</div>

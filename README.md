<p align="center">
  <img src="assets/header.svg" alt="Witchakorn Thokul - Full-Stack Developer" width="100%"/>
</p>

<p align="center">
  <a href="https://readme-typing-svg.demolab.com"><img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=18&duration=3200&pause=900&color=94A3B8&center=true&vCenter=true&width=720&lines=Building+internal+platforms+used+daily+by+operations+teams;Moved+5+production+systems+from+Vercel+to+Cloudflare+in+3+days;Realtime+over+polling.+Less+CPU%2C+faster+screens." alt="Summary"/></a>
</p>

<p align="center">
  <a href="https://witchakorn-web.vercel.app"><img src="https://img.shields.io/badge/Portfolio-witchakorn--web.vercel.app-0f172a?style=for-the-badge&labelColor=38bdf8&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:art992398@email.com"><img src="https://img.shields.io/badge/Email-Contact-0f172a?style=for-the-badge&logo=gmail&logoColor=white&labelColor=334155" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Status-Open_to_opportunities-0f172a?style=for-the-badge&labelColor=16a34a" alt="Open to opportunities"/>
</p>

<br/>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>About</h3>
      <p>Full-stack developer building the internal systems a manufacturing and logistics business runs on: transport planning, KPI dashboards, document workflows and ESG disclosure.</p>
      <p>I care about systems that stay fast and cheap to run, ship in small safe steps through DEMO and PRD environments, and replace spreadsheets people have outgrown.</p>
    </td>
    <td width="50%" valign="top">
      <h3>At a glance</h3>
      <table>
        <tr><td><b>6</b></td><td>production systems maintained</td></tr>
        <tr><td><b>230+</b></td><td>commits on one platform in Nov 2026</td></tr>
        <tr><td><b>1</b></td><td>central sign-on across every app</td></tr>
        <tr><td><b>3</b></td><td>branches visualized in a 3D yard view</td></tr>
      </table>
    </td>
  </tr>
</table>

## What I am building

Six systems under one company domain with a single sign-on portal in front. Five moved from Vercel to Cloudflare in November 2026.

```mermaid
flowchart LR
    U([Staff]) --> P{{Central Portal<br/>SSO}}
    P --> L[Smart Logistics]
    P --> D[DocAlert]
    P --> K[Business Dashboard]
    P --> M[Mini Dashboard]
    P --> E[ESG Disclosure]
    L -->|Realtime| S[(Supabase<br/>PostgreSQL)]
    D --> S
    K --> G[(Automated<br/>collectors)]
    M --> G
    E --> X[(Google Sheets)]

    classDef hub fill:#0f172a,stroke:#38bdf8,color:#f8fafc,stroke-width:2px;
    classDef app fill:#111827,stroke:#475569,color:#e2e8f0;
    classDef data fill:#1e293b,stroke:#818cf8,color:#e2e8f0;
    class P hub;
    class L,D,K,M,E app;
    class S,G,X data;
```

| System | What it does | Built with |
|---|---|---|
| **Smart Logistics Platform** | Transport planning from sales orders, vehicle booking calendar, weighbridge ticket matching, shipment tracking | Cloudflare Workers, Supabase Realtime |
| **Central Portal (SSO)** | One sign-in and launcher for every internal app | Cloudflare Pages |
| **DocAlert** | Contract and document renewals with approvals and email alerts | Cloudflare Pages, Supabase |
| **Smart Business Dashboard** | Company KPIs, task-first navigation, collector health view | Cloudflare Pages |
| **Mini Business Dashboard** | Lightweight KPI view with role-based overrides | Cloudflare Pages |
| **ESG Disclosure Site** | Bilingual Thai / English ESG reporting across five categories | React, Vite, Google Sheets |

<details>
<summary><b>Recent engineering notes from the Smart Logistics Platform</b></summary>
<br/>

- **Platform migration.** Moved DEMO and PRD from Vercel to Cloudflare Workers and Pages, including scheduled jobs, with the legacy app redirecting users to the new one.
- **Performance.** Replaced 30-second polling with Supabase Realtime, throttled shared-data refresh to once a minute, and batched notification queries into a single round trip.
- **Planning.** Plan directly from sales orders with over-quantity warnings, provisional loading dates and storage jobs that do not need an order.
- **Operations.** Automatic weighbridge ticket matching, per-trip shipment numbers with attachments, weekly summaries and bulk cancellation with reasons.
- **Security.** Least-privilege database role for the web app, access logging and rotated SSO secrets.

</details>

## Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/WitchakornThokul/Smart-Cow-Tracker"><img src="https://res.cloudinary.com/dgh4ndaru/image/upload/c_fill,g_north,w_800,h_500/v1778949911/Witchakorn_Poster_jbtl7j.jpg" alt="Smart Cow Tracker" width="100%"/></a>
      <h3>Smart Cow Tracker</h3>
      <p>Dairy farm management app with real-time health tracking, records, appointments and assistant management.</p>
      <p><code>React Native</code> <code>Expo</code> <code>Firebase</code></p>
      <p><a href="https://youtu.be/uTIGElkRXKc">Demo video</a> · <a href="https://drive.google.com/file/d/1XQKEonFqFlDZqEPxyeqIkxalqGy50DhL/view?usp=drive_link">Poster</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/WitchakornThokul/PQS"><img src="https://res.cloudinary.com/dgh4ndaru/image/upload/c_fill,g_north,w_800,h_500/v1778949911/InternshipPoster_Witchakorn_tunckf.jpg" alt="PQS Logistics v1" width="100%"/></a>
      <h3>PQS Logistics (v1)</h3>
      <p>The original planning and vehicle booking tool, with approvals and reports, that grew into the Smart Logistics Platform.</p>
      <p><code>Google Apps Script</code> <code>Google Sheets</code></p>
      <p><a href="https://drive.google.com/file/d/1HeC-MrxZyF2orxr88V_linuolvKyxozl/view?usp=drive_link">Poster</a></p>
    </td>
  </tr>
</table>

## Tech stack

<table>
  <tr>
    <td width="150"><b>Languages</b></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=ts" width="44" height="44" alt="TypeScript"/><br/><sub>TypeScript</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=js" width="44" height="44" alt="JavaScript"/><br/><sub>JavaScript</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=py" width="44" height="44" alt="Python"/><br/><sub>Python</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=php" width="44" height="44" alt="PHP"/><br/><sub>PHP</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=html" width="44" height="44" alt="HTML"/><br/><sub>HTML</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=css" width="44" height="44" alt="CSS"/><br/><sub>CSS</sub></td>
  </tr>
  <tr>
    <td width="150"><b>Frontend</b></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=react" width="44" height="44" alt="React"/><br/><sub>React</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=nextjs" width="44" height="44" alt="Next.js"/><br/><sub>Next.js</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=vite" width="44" height="44" alt="Vite"/><br/><sub>Vite</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=tailwind" width="44" height="44" alt="Tailwind CSS"/><br/><sub>Tailwind CSS</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=angular" width="44" height="44" alt="Angular"/><br/><sub>Angular</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=bootstrap" width="44" height="44" alt="Bootstrap"/><br/><sub>Bootstrap</sub></td>
  </tr>
  <tr>
    <td width="150"><b>Mobile</b></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=react" width="44" height="44" alt="React Native"/><br/><sub>React Native</sub></td>
    <td align="center" width="96"><img src="assets/icons/expo.svg" width="44" height="44" alt="Expo"/><br/><sub>Expo</sub></td>
  </tr>
  <tr>
    <td width="150"><b>Backend and Data</b></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=nodejs" width="44" height="44" alt="Node.js"/><br/><sub>Node.js</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=supabase" width="44" height="44" alt="Supabase"/><br/><sub>Supabase</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=postgres" width="44" height="44" alt="PostgreSQL"/><br/><sub>PostgreSQL</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=firebase" width="44" height="44" alt="Firebase"/><br/><sub>Firebase</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=mysql" width="44" height="44" alt="MySQL"/><br/><sub>MySQL</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=mongodb" width="44" height="44" alt="MongoDB"/><br/><sub>MongoDB</sub></td>
  </tr>
  <tr>
    <td width="150"><b>Cloud and DevOps</b></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=cloudflare" width="44" height="44" alt="Cloudflare"/><br/><sub>Cloudflare</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=vercel" width="44" height="44" alt="Vercel"/><br/><sub>Vercel</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=git" width="44" height="44" alt="Git"/><br/><sub>Git</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=github" width="44" height="44" alt="GitHub"/><br/><sub>GitHub</sub></td>
  </tr>
  <tr>
    <td width="150"><b>Automation and Tools</b></td>
    <td align="center" width="96"><img src="assets/icons/googleappsscript.svg" width="44" height="44" alt="Apps Script"/><br/><sub>Apps Script</sub></td>
    <td align="center" width="96"><img src="assets/icons/googlesheets.svg" width="44" height="44" alt="Google Sheets"/><br/><sub>Google Sheets</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=postman" width="44" height="44" alt="Postman"/><br/><sub>Postman</sub></td>
    <td align="center" width="96"><img src="https://skillicons.dev/icons?theme=dark&i=figma" width="44" height="44" alt="Figma"/><br/><sub>Figma</sub></td>
  </tr>
</table>

## Contact

<p>
  <a href="mailto:art992398@email.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://witchakorn-web.vercel.app"><img src="https://img.shields.io/badge/Portfolio-0f172a?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="https://web.facebook.com/tokki.once"><img src="https://img.shields.io/badge/Facebook-1877F2?style=flat-square&logo=facebook&logoColor=white" alt="Facebook"/></a>
  <a href="https://www.instagram.com/mimosa_4103/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white" alt="Instagram"/></a>
</p>

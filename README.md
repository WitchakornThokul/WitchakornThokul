<div align="center">

# Witchakorn Thokul

**Full-Stack Developer · Enterprise Web Systems · Mobile (React Native)**

[![Email](https://img.shields.io/badge/Email-art992398%40email.com-24292F?style=flat-square&logo=gmail&logoColor=white)](mailto:art992398@email.com)
[![GitHub followers](https://img.shields.io/github/followers/WitchakornThokul?style=flat-square&color=24292F&label=Followers)](https://github.com/WitchakornThokul?tab=followers)

</div>

---

## About

Full-stack developer building internal business systems for a manufacturing and logistics organization, from planning and transport operations to KPI dashboards and ESG disclosure.

- Design, build and operate production web applications used daily by operations, sales and management teams
- Lead migration of six production systems from Vercel to Cloudflare (Pages and Workers) under a single company domain with central sign-on
- Focus on reliability and cost: realtime updates in place of polling, reduced database load, staged DEMO and PRD environments
- Background in mobile development with React Native and Expo

---

## Current Work: Enterprise Systems Portfolio

Six production systems, all running on Cloudflare as of November 2026.

| System | Purpose | Platform |
|---|---|---|
| **Smart Logistics Platform** | Transport planning from sales orders, vehicle booking calendar, weighbridge ticket matching, shipment status tracking | Cloudflare Workers + Pages, Supabase |
| **DocAlert** | Document and contract renewal tracking with approval workflow and email notifications | Cloudflare Pages, Supabase |
| **Smart Business Dashboard** | Company KPI dashboard with task-oriented navigation and automated data collectors | Cloudflare Pages |
| **Mini Business Dashboard** | Lightweight KPI view with role-based manual overrides for automated metrics | Cloudflare Pages |
| **Central Portal (SSO)** | Single sign-on entry point for all internal applications | Cloudflare Pages |
| **ESG Disclosure Site** | Bilingual (Thai / English) ESG reporting across five categories | React, Vite |

### Smart Logistics Platform

Replaced a Google Apps Script tool with a full web application; 230+ commits in November 2026 alone.

- **Platform migration** — moved DEMO and PRD from Vercel to Cloudflare Workers and Pages, including scheduled jobs; legacy app redirects users to the new system
- **Performance** — replaced 30-second polling with Supabase Realtime, throttled shared-data refresh, and batched notification queries to cut CPU usage
- **Planning** — plan directly from sales orders with over-quantity warnings, provisional loading dates, and storage jobs without an order
- **Weighbridge** — automatic ticket matching and monthly product summaries
- **Operations** — per-trip and per-step shipment numbers with attachments, weekly calendar summaries, bulk cancellation with reasons
- **Reporting** — logistics and sales reports aligned to updated business rules
- **Visualization** — 3D yard layout for three branches
- **Security** — dedicated least-privilege database role for the web application and access logging

### Central Portal (SSO)

- Redesigned sign-in page and unified application launcher
- Rotated SSO secrets during the Cloudflare migration and verified sign-in to every connected application
- Per-application sign-out that keeps the central session intact

### DocAlert

- Feature parity with the legacy system: renewals, approvals, automatic status, deep links from email, and legacy data import

### Business Dashboards

- Reorganized navigation by task, a home page that surfaces items needing attention, and an admin view of data collector health
- Role-based editing of automatically collected KPI values for admin, manager and QA users

---

## Featured Projects

### Smart Cow Tracker

Dairy farm management mobile app with real-time health tracking.

- **Stack:** React Native, Expo, Firebase
- **Features:** cow tracking, health records, appointments, assistant management
- [Demo video](https://youtu.be/uTIGElkRXKc) · [Poster](https://drive.google.com/file/d/1XQKEonFqFlDZqEPxyeqIkxalqGy50DhL/view?usp=drive_link)

### PQS Logistics (v1)

The original logistics planning and booking tool that preceded the Smart Logistics Platform.

- **Stack:** Google Apps Script, Google Sheets
- **Features:** planning calendar, vehicle booking, user approval, reports, notifications
- [Poster](https://drive.google.com/file/d/1HeC-MrxZyF2orxr88V_linuolvKyxozl/view?usp=drive_link)

---

## Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Frontend and Mobile**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)

**Backend, Data and Cloud**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Automation and Tools**

![Google Apps Script](https://img.shields.io/badge/Google_Apps_Script-4285F4?style=flat-square&logo=google&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=flat-square&logo=googlesheets&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

---

## GitHub Activity

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=WitchakornThokul&theme=github_dark" height="165" alt="GitHub stats"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=WitchakornThokul&theme=github_dark" height="165" alt="Most used languages"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=WitchakornThokul&bg_color=0d1117&color=c9d1d9&line=58a6ff&point=c9d1d9&area=true&area_color=58a6ff&hide_border=true" width="100%" alt="Contribution graph"/>

</div>

---

## Contact

[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:art992398@email.com)
[![GitHub](https://img.shields.io/badge/GitHub-24292F?style=flat-square&logo=github&logoColor=white)](https://github.com/WitchakornThokul)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=flat-square&logo=facebook&logoColor=white)](https://web.facebook.com/tokki.once)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/mimosa_4103/)

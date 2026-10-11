<p align="center">
  <img src="assets/header.svg" width="100%" alt="Andrew Tanui, Full-Stack and Power Platform Developer" />
</p>

<p align="center">
  <a href="https://ke.linkedin.com/in/kibettanuiandrew"><img src="https://img.shields.io/badge/LinkedIn-161B22?style=flat-square&logo=linkedin&logoColor=E8A33D" alt="LinkedIn" /></a>
  <a href="https://twitter.com/tanuilelan"><img src="https://img.shields.io/badge/X_/_Twitter-161B22?style=flat-square&logo=x&logoColor=E8A33D" alt="X / Twitter" /></a>
  <a href="https://instagram.com/tanuilelan"><img src="https://img.shields.io/badge/Instagram-161B22?style=flat-square&logo=instagram&logoColor=E8A33D" alt="Instagram" /></a>
  <a href="https://kaggle.com/tanuilelan"><img src="https://img.shields.io/badge/Kaggle-161B22?style=flat-square&logo=kaggle&logoColor=E8A33D" alt="Kaggle" /></a>
</p>

## <img src="assets/icons/user.svg" width="22" height="22" align="top" /> About

I build systems that replace spreadsheets, paper and email chains with **one source of truth**: web platforms in **Next.js, TypeScript and Postgres**, business apps on **Microsoft Power Platform**, and AI assistants grounded in real data instead of guesswork.

<table>
  <tr>
    <td><img src="assets/icons/briefcase.svg" width="16" height="16" align="top" /> <b>Now</b></td>
    <td>Power Apps Developer at <b>Pathways Technologies</b></td>
  </tr>
  <tr>
    <td><img src="assets/icons/pin.svg" width="16" height="16" align="top" /> <b>Based in</b></td>
    <td>Kenya, building for East Africa and beyond</td>
  </tr>
  <tr>
    <td><img src="assets/icons/book.svg" width="16" height="16" align="top" /> <b>Learning</b></td>
    <td>Flutter and React Native</td>
  </tr>
  <tr>
    <td><img src="assets/icons/compass.svg" width="16" height="16" align="top" /> <b>Open to</b></td>
    <td>govtech, fintech, agritech and anything that solves real problems for real people</td>
  </tr>
</table>

> I've written more RLS policies than I've had hot meals this week.

<p align="center"><img src="assets/divider.svg" width="100%" /></p>

## <img src="assets/icons/briefcase.svg" width="22" height="22" align="top" /> Selected work

### <img src="assets/icons/coffee.svg" width="22" height="22" align="top" /> Stock Take &amp; Reconciliation Suite

Power Platform solution that replaces paper count sheets and month-end Excel reconciliation in a coffee exporter's warehouses.

<table>
  <tr>
    <td align="center"><b>2</b><br/><sub>code apps</sub></td>
    <td align="center"><b>20</b><br/><sub>Dataverse tables</sub></td>
    <td align="center"><b>7</b><br/><sub>security roles</sub></td>
    <td align="center"><b>12</b><br/><sub>Power Automate flows</sub></td>
    <td align="center"><b>12</b><br/><sub>live reports</sub></td>
  </tr>
</table>

<details>
<summary><b>How it works</b></summary>
<br/>

- **Counter phone app**: outturn-first, *blind* counting (counters never see system quantities, so counts stay honest), one-pocket-per-lot rule, tag photos, offline queueing, stack checklist and floor map
- **Management hub**: ERP stock import with validation checks, count-sheet approvals, a variance engine that suggests the likely cause of every difference, exceptions with SLA escalation, mapping approvals, a 4-gate sign-off, and reports exported to Excel
- **Dataverse back end**: ERP data locked against edits, full auditing, photos stored as attachments
- **Automation**: Teams alerts to supervisors and counters, Finance approvals, daily exception escalation, a sign-off chain that emails the month-end pack, and a count report the morning after every count
- **Infrastructure as code**: schema, roles, seed data and flows rebuilt from Node scripts over the Dataverse Web API

</details>

`Power Apps code apps` · `React` · `TypeScript` · `Vite` · `Dataverse` · `Power Automate` · `Teams` · `Approvals`

### <img src="assets/icons/globe.svg" width="22" height="22" align="top" /> Kenya Trade Intelligence Platform (KTIP)

Trade decision-support platform for Kenya's State Department for Trade, pulling fragmented trade data into one view where every figure traces back to its source agency.

<table>
  <tr>
    <td align="center"><b>2.7M+</b><br/><sub>transaction rows</sub></td>
    <td align="center"><b>8</b><br/><sub>analysis tools</sub></td>
    <td align="center"><b>7</b><br/><sub>scoring dimensions, in SQL</sub></td>
    <td align="center"><b>1</b><br/><sub>read-only AI analyst</sub></td>
  </tr>
</table>

<details>
<summary><b>How it works</b></summary>
<br/>

- **Tools**: product and market explorer, landed-cost estimator, market opportunity engine, barrier monitor, exporter capacity map, step-by-step procedures, live trade news, embedded BI dashboards
- **AI Trade Analyst**: Claude with a single hardened, read-only SQL tool, so every answer comes from a query it actually ran (streaming, prompt caching, rate limiting)
- **Data**: Neon Postgres, BI views for Apache Superset, World Bank WITS tariff sync and NewsAPI ingestion on GitHub Actions
- **Accounts**: self-hosted NextAuth (email/password, Google, LinkedIn, GitHub, Facebook), watchlists, in-app and email notifications

</details>

`Next.js 16` · `React 19` · `TypeScript` · `PostgreSQL (Neon)` · `Drizzle ORM` · `Tailwind` · `Claude API` · `NextAuth` · `GitHub Actions`

<!-- Replace YOUR-KTIP-REPO with the real repo name, or delete this card -->
<a href="https://github.com/Andrewtanui/YOUR-KTIP-REPO"><img src="https://github-readme-stats.vercel.app/api/pin/?username=Andrewtanui&repo=YOUR-KTIP-REPO&bg_color=0D1117&title_color=E8A33D&icon_color=E8A33D&text_color=C9D1D9&border_color=30363D&hide_border=false&border_radius=10" /></a>

### <img src="assets/icons/shield.svg" width="22" height="22" align="top" /> NSIF South Sudan

Government-grade social insurance platform for the National Social Insurance Fund of the Republic of South Sudan.

<details>
<summary><b>How it works</b></summary>
<br/>

- **Public website** with Sanity CMS, English and Arabic, and full accessibility
- **Member self-registration** with a multi-step form, document upload and email verification
- **Employer portal** with Pesapal payments for monthly contributions
- **Staff CRM** with role-based access, document verification through Supabase Storage signed URLs, automated NSIF number generation (Luhn check digit) and full audit logging

</details>

`Next.js 16` · `TypeScript` · `Supabase` · `PostgreSQL` · `Tailwind` · `Sanity` · `Nodemailer` · `Pesapal`

### <img src="assets/icons/layers.svg" width="22" height="22" align="top" /> Also building

<table>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/icons/layout.svg" width="18" height="18" align="top" /> <b>Northlink Consulting</b><br/>
      <sub>Website revamp for a consulting firm working across East and Central Africa: a design system built from scratch, a Next.js component library, an editorial page set and a 3-slide hero.</sub><br/><br/>
      <code>Next.js</code> <code>TypeScript</code> <code>CSS Modules</code>
    </td>
    <td width="50%" valign="top">
      <img src="assets/icons/sprout.svg" width="18" height="18" align="top" /> <b>KALRO-WEB</b><br/>
      <sub>Official website for the Kenya Agricultural and Livestock Research Organization.</sub><br/><br/>
      <a href="https://github.com/Andrewtanui/KALRO-WEB"><img src="https://github-readme-stats.vercel.app/api/pin/?username=Andrewtanui&repo=KALRO-WEB&bg_color=0D1117&title_color=E8A33D&icon_color=E8A33D&text_color=C9D1D9&border_color=30363D&hide_border=false&border_radius=10" /></a>
    </td>
  </tr>
</table>

<p align="center"><img src="assets/divider.svg" width="100%" /></p>

## <img src="assets/icons/layers.svg" width="22" height="22" align="top" /> Stack

<table>
<tr><td width="200"><img src="assets/icons/layers.svg" width="16" height="16" align="top" /> <b>Languages</b></td><td><img src="https://img.shields.io/badge/TypeScript-161B22?style=flat-square&logo=typescript&logoColor=E8A33D" alt="TypeScript" /> <img src="https://img.shields.io/badge/JavaScript-161B22?style=flat-square&logo=javascript&logoColor=E8A33D" alt="JavaScript" /> <img src="https://img.shields.io/badge/Python-161B22?style=flat-square&logo=python&logoColor=E8A33D" alt="Python" /> <img src="https://img.shields.io/badge/C%23-161B22?style=flat-square&logo=c-sharp&logoColor=E8A33D" alt="C#" /> <img src="https://img.shields.io/badge/SQL-161B22?style=flat-square&logo=postgresql&logoColor=E8A33D" alt="SQL" /></td></tr>
<tr><td width="200"><img src="assets/icons/layout.svg" width="16" height="16" align="top" /> <b>Frontend</b></td><td><img src="https://img.shields.io/badge/Next.js-161B22?style=flat-square&logo=next.js&logoColor=E8A33D" alt="Next.js" /> <img src="https://img.shields.io/badge/React-161B22?style=flat-square&logo=react&logoColor=E8A33D" alt="React" /> <img src="https://img.shields.io/badge/Tailwind_CSS-161B22?style=flat-square&logo=tailwindcss&logoColor=E8A33D" alt="Tailwind CSS" /> <img src="https://img.shields.io/badge/HTML5-161B22?style=flat-square&logo=html5&logoColor=E8A33D" alt="HTML5" /> <img src="https://img.shields.io/badge/CSS3-161B22?style=flat-square&logo=css3&logoColor=E8A33D" alt="CSS3" /></td></tr>
<tr><td width="200"><img src="assets/icons/package.svg" width="16" height="16" align="top" /> <b>Power Platform</b></td><td><img src="https://img.shields.io/badge/Power_Apps-161B22?style=flat-square&logo=powerapps&logoColor=E8A33D" alt="Power Apps" /> <img src="https://img.shields.io/badge/Dataverse-161B22?style=flat-square&logo=microsoft&logoColor=E8A33D" alt="Dataverse" /> <img src="https://img.shields.io/badge/Power_Automate-161B22?style=flat-square&logo=powerautomate&logoColor=E8A33D" alt="Power Automate" /> <img src="https://img.shields.io/badge/Teams_%26_Approvals-161B22?style=flat-square&logo=microsoftteams&logoColor=E8A33D" alt="Teams & Approvals" /></td></tr>
<tr><td width="200"><img src="assets/icons/chart.svg" width="16" height="16" align="top" /> <b>Backend & data</b></td><td><img src="https://img.shields.io/badge/PostgreSQL-161B22?style=flat-square&logo=postgresql&logoColor=E8A33D" alt="PostgreSQL" /> <img src="https://img.shields.io/badge/Supabase-161B22?style=flat-square&logo=supabase&logoColor=E8A33D" alt="Supabase" /> <img src="https://img.shields.io/badge/Neon-161B22?style=flat-square&logo=neon&logoColor=E8A33D" alt="Neon" /> <img src="https://img.shields.io/badge/Drizzle_ORM-161B22?style=flat-square&logo=drizzle&logoColor=E8A33D" alt="Drizzle ORM" /> <img src="https://img.shields.io/badge/Node.js-161B22?style=flat-square&logo=node.js&logoColor=E8A33D" alt="Node.js" /> <img src="https://img.shields.io/badge/Flask-161B22?style=flat-square&logo=flask&logoColor=E8A33D" alt="Flask" /> <img src="https://img.shields.io/badge/MySQL-161B22?style=flat-square&logo=mysql&logoColor=E8A33D" alt="MySQL" /></td></tr>
<tr><td width="200"><img src="assets/icons/link.svg" width="16" height="16" align="top" /> <b>CMS & integrations</b></td><td><img src="https://img.shields.io/badge/Sanity-161B22?style=flat-square&logo=sanity&logoColor=E8A33D" alt="Sanity" /> <img src="https://img.shields.io/badge/NextAuth-161B22?style=flat-square&logo=auth0&logoColor=E8A33D" alt="NextAuth" /> <img src="https://img.shields.io/badge/Nodemailer-161B22?style=flat-square&logo=gmail&logoColor=E8A33D" alt="Nodemailer" /> <img src="https://img.shields.io/badge/Pesapal-161B22?style=flat-square" alt="Pesapal" /></td></tr>
<tr><td width="200"><img src="assets/icons/spark.svg" width="16" height="16" align="top" /> <b>AI & data science</b></td><td><img src="https://img.shields.io/badge/Claude_API-161B22?style=flat-square&logo=anthropic&logoColor=E8A33D" alt="Claude API" /> <img src="https://img.shields.io/badge/TensorFlow-161B22?style=flat-square&logo=tensorflow&logoColor=E8A33D" alt="TensorFlow" /> <img src="https://img.shields.io/badge/PyTorch-161B22?style=flat-square&logo=pytorch&logoColor=E8A33D" alt="PyTorch" /> <img src="https://img.shields.io/badge/scikit--learn-161B22?style=flat-square&logo=scikit-learn&logoColor=E8A33D" alt="scikit-learn" /> <img src="https://img.shields.io/badge/Pandas-161B22?style=flat-square&logo=pandas&logoColor=E8A33D" alt="Pandas" /></td></tr>
<tr><td width="200"><img src="assets/icons/compass.svg" width="16" height="16" align="top" /> <b>Tooling</b></td><td><img src="https://img.shields.io/badge/Docker-161B22?style=flat-square&logo=docker&logoColor=E8A33D" alt="Docker" /> <img src="https://img.shields.io/badge/Git-161B22?style=flat-square&logo=git&logoColor=E8A33D" alt="Git" /> <img src="https://img.shields.io/badge/GitHub_Actions-161B22?style=flat-square&logo=githubactions&logoColor=E8A33D" alt="GitHub Actions" /> <img src="https://img.shields.io/badge/Linux-161B22?style=flat-square&logo=linux&logoColor=E8A33D" alt="Linux" /> <img src="https://img.shields.io/badge/Postman-161B22?style=flat-square&logo=postman&logoColor=E8A33D" alt="Postman" /> <img src="https://img.shields.io/badge/Figma-161B22?style=flat-square&logo=figma&logoColor=E8A33D" alt="Figma" /> <img src="https://img.shields.io/badge/Photoshop-161B22?style=flat-square&logo=adobe-photoshop&logoColor=E8A33D" alt="Photoshop" /></td></tr>
</table>

<p align="center"><img src="assets/divider.svg" width="100%" /></p>

## <img src="assets/icons/chart.svg" width="22" height="22" align="top" /> On GitHub

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Andrewtanui&show_icons=true&include_all_commits=true&count_private=true&bg_color=0D1117&title_color=E8A33D&icon_color=E8A33D&text_color=C9D1D9&border_color=30363D&hide_border=false&border_radius=10" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Andrewtanui&layout=compact&langs_count=8&bg_color=0D1117&title_color=E8A33D&icon_color=E8A33D&text_color=C9D1D9&border_color=30363D&hide_border=false&border_radius=10" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Andrewtanui&background=0D1117&border=30363D&stroke=30363D&ring=E8A33D&fire=E8A33D&currStreakLabel=E8A33D&sideLabels=C9D1D9&currStreakNum=F0F6FC&sideNums=F0F6FC&dates=8B949E&border_radius=10" />
</p>

<p align="center"><img src="assets/divider.svg" width="100%" /></p>

## <img src="assets/icons/send.svg" width="22" height="22" align="top" /> Get in touch

Working on something in govtech, fintech or agritech across Africa? I'd like to hear about it.

<p align="center">
  <a href="https://ke.linkedin.com/in/kibettanuiandrew"><img src="https://img.shields.io/badge/LinkedIn-161B22?style=for-the-badge&logo=linkedin&logoColor=E8A33D" alt="LinkedIn" /></a>
  <a href="https://twitter.com/tanuilelan"><img src="https://img.shields.io/badge/X_/_Twitter-161B22?style=for-the-badge&logo=x&logoColor=E8A33D" alt="X / Twitter" /></a>
  <a href="https://instagram.com/tanuilelan"><img src="https://img.shields.io/badge/Instagram-161B22?style=for-the-badge&logo=instagram&logoColor=E8A33D" alt="Instagram" /></a>
  <a href="https://kaggle.com/tanuilelan"><img src="https://img.shields.io/badge/Kaggle-161B22?style=for-the-badge&logo=kaggle&logoColor=E8A33D" alt="Kaggle" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Andrewtanui&color=E8A33D&style=flat-square&label=profile+views" alt="Profile views" />
</p>

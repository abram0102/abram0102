<p align="center">
  <img src="./assets/banner.svg" alt="Abulamu Abulajiang — Software Engineer" width="100%" />
</p>

<p align="center">
  <a href="https://abulamu-personal-website.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://linkedin.com/in/abulamu">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:abulajiang.a@northeastern.edu">
    <img src="https://img.shields.io/badge/Email-6D5DFB?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/abram0102?tab=repositories">
    <img src="https://img.shields.io/badge/Repositories-0B1020?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" />
  </a>
</p>

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=8B91FF&center=true&vCenter=true&width=800&lines=Full-stack+%26+Backend+Software+Engineer;Production+systems+%7C+APIs+%7C+Search+%7C+AI;Next.js+%7C+Spring+Boot+%7C+FastAPI+%7C+AWS"
    alt="Typing introduction"
  />
</p>

## About

I build reliable software across **full-stack products, backend APIs, search systems, and AI-enabled workflows**. I am pursuing an **M.S. in Computer Science at Northeastern University** and expect to graduate in **May 2027**.

My recent work spans **Next.js, Express.js, Spring Boot, FastAPI, MongoDB, MySQL, Redis, AWS, Docker, automated testing, and CI/CD**.

## Impact at a glance

<table>
  <tr>
    <td align="center" width="25%">
      <strong>1,000+</strong><br />
      <sub>registered brands served</sub>
    </td>
    <td align="center" width="25%">
      <strong>50K+</strong><br />
      <sub>products supported by search APIs</sub>
    </td>
    <td align="center" width="25%">
      <strong>23%</strong><br />
      <sub>average query-latency reduction</sub>
    </td>
    <td align="center" width="25%">
      <strong>90%</strong><br />
      <sub>coverage on assigned backend modules</sub>
    </td>
  </tr>
</table>

## Engineering experience

### Fashion Index · Full Stack Developer Intern

- Collaborated within a team of 4 developers paired with a senior developer mentor to launch the new Fashion Index 3.0 web platform, owning the B2B advertising module across **Next.js, Express.js, MongoDB, and AWS S3** so advertisers on a platform with 1,000+ registered brands could upload campaigns and admins could review submissions before live serving.
- Designed the ad campaign lifecycle state machine with 6 statuses using centralized backend transition guards, role-aware moderation controls, unread admin queues, scheduled expiry jobs, and **MongoDB TTL cleanup** to support review and retention workflows.
- Diagnosed and resolved a longstanding **JWT authentication** defect blocking authorized ad uploads through tracing browser network requests and API logs by utilizing Chrome’s network tracer; hardened backend authorization and eliminated the recurring upload-failure path for authenticated advertisers through user-id unique-identifier matching at runtime.
- Independently built and shipped a standalone product-discovery application webpage which supports minimum of 50K+ MongoDB product records using **React.js, Vite.js, FastAPI, and MongoDB**.
- Designed tokenized multi-field search, aggregation-based faceted filtering with dynamic counts, supplier grouping, and pagination alongside asynchronous progressive loading to enable users to search and refine tens of thousands of SKUs in a single interface with minimal latency.
- Shipped the platform’s first end-to-end commenting system as embedded webpage section, implementing threaded replies, likes, edits, notifications, reporting, and admin moderation through **10 RESTful API endpoints**.
- Instantiated per-user rate limiting and a 3-report auto-hide pipeline, automating first-line abuse moderation, through querying recent records based on user ID through MongoDB; to be integrated with Redis in the future.

### Wanglan General Technology · Software Engineer Intern

- Developed **RESTful APIs** using **Java and Spring Boot** for factory management modules including work orders, inventory, and purchasing, implementing authentication, validation, pagination, and API documentation for reliable service integration.
- Optimized **MySQL and Redis** data access with indexing, batch operations, Redis caching, and query path refactoring, **reducing average query latency by 23%** across frequently used factory management workflows.
- Implemented backend logic through **DTO validation, service layer orchestration, and DAO query methods** powering React based factory management dashboards that enabled different user groups to monitor production orders, work in progress, and inventory in real time.
- Improved software quality through **JUnit testing, integration testing, CI/CD pipelines, Docker deployments, GitHub Actions**, peer code reviews, and production issue troubleshooting in an **Agile team of six**, maintaining **90% coverage** across assigned service modules.

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 Task Tracker Agent

Transforms text and voice input into structured tasks with due time, category, priority, people, location, and status.

**Highlights**

- FastAPI service and SQLite persistence
- OpenAI API and LangChain prompt workflows
- Rule-based validation and missing-field inference
- Search, CRUD, completion tracking, and task history

**Stack:** `Python` `FastAPI` `LangChain` `OpenAI API` `SQLite`

<p>
  <a href="https://github.com/abram0102/Task-Tracker-Agent">
    <img src="https://img.shields.io/badge/View_Repository-111827?style=flat-square&logo=github&logoColor=white" alt="Task Tracker Agent repository" />
  </a>
</p>

</td>
<td width="50%" valign="top">

### 🐾 Pet Adoption Platform

A full-stack adoption platform covering browsing, filtering, favorites, adoption records, authentication, and cloud release.

**Highlights**

- Released to **200+ Northeastern student users**
- Improved page responsiveness by **27%**
- Cached search results and normalized favorites state
- Indexed MongoDB collections for common workflows

**Stack:** `React` `Node.js` `Express.js` `MongoDB` `Redux Toolkit Query` `GCP`

<p>
  <a href="https://github.com/abram0102/PetAdoption">
    <img src="https://img.shields.io/badge/View_Repository-111827?style=flat-square&logo=github&logoColor=white" alt="Pet Adoption Platform repository" />
  </a>
</p>

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 💰 Saving App

An Android application built with modern Kotlin tooling, combining a declarative interface, structured application architecture, local persistence, asynchronous operations, and cloud integration.

**Highlights**

- MVVM architecture
- Jetpack Compose interface
- Room-based local persistence
- Kotlin Coroutines and AWS Amplify integration

**Stack:** `Kotlin` `Jetpack Compose` `Room` `Coroutines` `AWS Amplify`

<p>
  <a href="https://github.com/abram0102/Saving-App">
    <img src="https://img.shields.io/badge/View_Repository-111827?style=flat-square&logo=github&logoColor=white" alt="Saving App repository" />
  </a>
</p>

</td>
<td width="50%" valign="top">

### 🌐 Personal Portfolio

A public portfolio for presenting engineering experience, projects, and technical skills.

<p>
  <a href="https://abulamu-personal-website.vercel.app/">
    <img src="https://img.shields.io/badge/Live_Demo-6D5DFB?style=flat-square&logo=vercel&logoColor=white" alt="Discover" />
  </a>
</p>

**Focus:** responsive presentation, project discovery, and a clear recruiter-facing overview of my work.

</td>
</tr>
</table>


## Technology stack

<p>
  <strong>Languages</strong><br /><br />
  <img src="https://skillicons.dev/icons?i=java,js,ts,python,cpp,html,css&perline=10" alt="Languages" />
</p>

<p>
  <strong>Frontend and backend</strong><br /><br />
  <img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,express,spring,fastapi,tailwind&perline=10" alt="Frameworks" />
</p>

<p>
  <strong>Data, cloud, and delivery</strong><br /><br />
  <img src="https://skillicons.dev/icons?i=mysql,mongodb,redis,sqlite,aws,gcp,docker,githubactions,git&perline=10" alt="Data cloud and delivery tools" />
</p>

## GitHub activity

<p align="center">
  <img
    src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=abram0102&theme=github_dark"
    alt="GitHub contribution summary"
    width="98%"
  />
</p>

<p align="center">
  <img
    src="https://streak-stats.demolab.com?user=abram0102&theme=tokyonight&hide_border=true&background=0B1020"
    alt="GitHub contribution streak"
    height="170"
  />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/abram0102/abram0102/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/abram0102/abram0102/output/github-contribution-grid-snake.svg" />
    <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/abram0102/abram0102/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

---

<p align="center">
  <sub>Open to 2027 new-grad Software Engineering, Backend, and Full-stack opportunities.</sub>
</p>

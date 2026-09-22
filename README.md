## Hi! I'm Santiago Sandoval <img src="https://raw.githubusercontent.com/iampavangandhi/iampavangandhi/master/gifs/Hi.gif" width="40" />

⚡ **Full-Stack Software Engineer** · TypeScript · React · Node.js · Bogotá, Colombia 🇨🇴

I've spent nearly three years building production applications used by **800+ people across four industrial companies**. I like owning modules end to end: gathering requirements with finance, HR and purchasing teams, modeling the data, implementing, deploying and supporting it in production. My focus is making software do the tedious work so people don't have to.

- 💼 Until August 2026 I was a Full-Stack Software Engineer at **Dromos Pavimentos S.A.S.**, on a engineers team serving Dromos Pavimentos, Incominería, Laboratorio Ingestrac and Drominc.
- 🎓 Studying Software Engineering.
- 🤖 Into applied AI: structured document extraction, tool calling and internal assistants with cost and latency telemetry.
- 🌎 Spanish · English

<br>

### 📊 Production impact

| Workflow | Before | After |
| --- | --- | --- |
| 🧾 Invoice processing (multi-company) | 10–15 days | **3–4 days** |
| 🧮 Accounting task time per invoice | 2–3 hours | **4–5 minutes** |
| 💸 Cash advances: request to payment | 2–3 days | **30–60 minutes** |
| 🤝 Supplier and customer onboarding | 10–20 days | **2–3 days** |
| 🚌 Employee transportation costs | — | **−40%** |

<br>

### 🧰 What I've built

- **Multi-company invoice workflow**: Microsoft Graph email ingestion, DIAN XML parsing, role-based reviews and payment tracking.
- **Cash advances and petty cash**: approvals, disbursements, balances, reversals and invoice reconciliation, with idempotent operations.
- **Supplier and customer onboarding**: autosaved forms, signatures, risk assessments, conditional documents and parallel reviews, integrated with **SIESA ERP**.
- **Biometric middleware** in Python/FastAPI connecting **ZKTeco** devices to staff schedules: overnight shifts, duplicate punches, tolerances and overtime.
- **Inventory sync**: scheduled, incremental sync of 100,000+ records per company from SIESA/SQL Server to PostgreSQL.
- **Applied AI**: an LLM pipeline that extracts structured data from Colombian RUT tax documents, and an internal assistant on **OpenRouter** with streaming, tool calling, model selection and token, cost and latency telemetry.

<br>

### 🚀 Featured project

<table>
  <tr>
    <td>
      <h4>🧾 <a href="https://github.com/sxntixgxs/lab-trxckin">Lab Trxckin</a></h4>
      <p>A public, demo-data version of a finance operations platform for a group of Colombian companies. It pulls DIAN e-invoices straight from Microsoft 365 mailboxes, routes them through an approval workflow with SLA tracking, and hands them to accounting. It also runs cash advances and petty cash.</p>
      <ul>
        <li>📥 Scheduled ingestion with <b>Microsoft Graph</b> and UBL XML parsing (DIAN <code>AttachedDocument</code>)</li>
        <li>✅ Approvals with returns, credit notes and business-hours SLAs (Colombian holidays)</li>
        <li>💸 Cash advances: request → direct manager → accounting → management → treasury → legalization</li>
        <li>🔐 Role- and route-based permissions, multi-company access and admin impersonation</li>
        <li>🧪 Tests with Vitest and <code>convex-test</code>, CI on GitHub Actions</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
        <img src="https://img.shields.io/badge/Convex-EE342F?style=flat-square&logoColor=white" />
        <img src="https://img.shields.io/badge/NestJS_11-E0234E?style=flat-square&logo=nestjs&logoColor=white" />
        <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" />
        <img src="https://img.shields.io/badge/Postgres-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/WorkOS-6363F1?style=flat-square&logoColor=white" />
        <img src="https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

<br>

### 🛠️ Tech I use most

**Languages**
<div align="center">
  <!-- TypeScript -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript" width="40" height="40"/>
  <!-- Python -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="40" height="40"/>
  <!-- SQL (Azure SQL icon as a stand-in) -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azuresqldatabase/azuresqldatabase-original.svg" alt="SQL" width="40" height="40"/>
  <!-- JavaScript -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40"/>
</div>

**Frontend**
<div align="center">
  <!-- React -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React" width="40" height="40"/>
  <!-- Next.js -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" alt="Next.js" width="40" height="40"/>
  <!-- Tailwind CSS -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind CSS" width="40" height="40"/>
</div>

**Backend and databases**
<div align="center">
  <!-- Node.js -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" width="40" height="40"/>
  <!-- NestJS -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nestjs/nestjs-original.svg" alt="NestJS" width="40" height="40"/>
  <!-- FastAPI -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" alt="FastAPI" width="40" height="40"/>
  <!-- PostgreSQL -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" width="40" height="40"/>
  <!-- SQL Server -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/microsoftsqlserver/microsoftsqlserver-original.svg" alt="SQL Server" width="40" height="40"/>
  <!-- Prisma -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/prisma/prisma-original.svg" alt="Prisma" width="40" height="40"/>
</div>

**Infrastructure and delivery**
<div align="center">
  <!-- Docker -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" width="40" height="40"/>
  <!-- Linux -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux" width="40" height="40"/>
  <!-- Git -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" width="40" height="40"/>
  <!-- GitHub -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" width="40" height="40"/>
  <!-- GitHub Actions -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/githubactions/githubactions-original.svg" alt="GitHub Actions" width="40" height="40"/>
</div>

<br>

<div align="center">
  <img src="https://img.shields.io/badge/Convex-EE342F?style=for-the-badge&logoColor=white" alt="Convex" />
  <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white" alt="TanStack Query" />
  <img src="https://img.shields.io/badge/Coolify-6B16ED?style=for-the-badge&logoColor=white" alt="Coolify" />
  <img src="https://img.shields.io/badge/Microsoft_Graph-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" alt="Microsoft Graph" />
  <img src="https://img.shields.io/badge/SIESA_ERP-1F4E79?style=for-the-badge&logoColor=white" alt="SIESA ERP" />
  <img src="https://img.shields.io/badge/DIAN_XML-005EB8?style=for-the-badge&logoColor=white" alt="DIAN XML" />
  <img src="https://img.shields.io/badge/ZKTeco-00A651?style=for-the-badge&logoColor=white" alt="ZKTeco" />
  <img src="https://img.shields.io/badge/OpenRouter-111111?style=for-the-badge&logo=openrouter&logoColor=white" alt="OpenRouter" />
</div>

<br>

### 🫂 Let's connect
<div align="center">
  <a href="https://www.linkedin.com/in/santiagosandovalt/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:santiagosandovalt@hotmail.com"><img src="https://img.shields.io/badge/-Email-%230078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white"></a>
  <a href="https://github.com/sxntixgxs" target="_blank"><img src="https://img.shields.io/badge/-GitHub-%23181717?style=for-the-badge&logo=github&logoColor=white"></a>
</div>

<br>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=sxntixgxs&label=Profile%20views&color=bd93f9&style=flat" alt="Profile views" />
</div>

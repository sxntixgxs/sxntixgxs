## Buenas! Soy Santiago Sandoval <img src="https://raw.githubusercontent.com/iampavangandhi/iampavangandhi/master/gifs/Hi.gif" width="40" />

⚡ **Full-Stack Software Engineer** · TypeScript · React · Node.js · Bogotá, Colombia 🇨🇴

Llevo casi tres años construyendo aplicaciones en producción que usan **800+ personas en cuatro empresas industriales**. Me gusta ser dueño de los módulos de principio a fin: levantar requerimientos con los usuarios de finanzas, RR. HH. o compras, modelar los datos, implementar, desplegar y dar soporte en producción. Mi foco está en que el software haga el trabajo aburrido para que la gente no tenga que hacerlo.

- 💼 Hasta agosto de 2026 fui Full-Stack Software Engineer en **Dromos Pavimentos S.A.S.**, en un equipo de tres desarrolladores atendiendo a Dromos Pavimentos, Incominería, Laboratorio Ingestrac y Drominc.
- 🎓 Estudiando Ingeniería de Software en la Corporación Universitaria Iberoamericana.
- 🤖 Me interesa la IA aplicada: extracción estructurada de documentos, tool calling y asistentes internos con telemetría de costo y latencia.
- 🌎 Español · English

<br>

### 📊 Impacto en producción

| Flujo | Antes | Después |
| --- | --- | --- |
| 🧾 Procesamiento de facturas (multi-empresa) | 10–15 días | **3–4 días** |
| 🧮 Tiempo de tarea contable por factura | 2–3 horas | **4–5 minutos** |
| 💸 Anticipos: de la solicitud al pago | 2–3 días | **30–60 minutos** |
| 🤝 Vinculación de proveedores y clientes | 10–20 días | **2–3 días** |
| 🚌 Costos de transporte de empleados | — | **−40%** |

<br>

### 🧰 Qué he construido

- **Flujo de facturas multi-empresa**: ingesta de correos con Microsoft Graph, parseo de XML de la DIAN, revisiones por rol y seguimiento de pagos.
- **Anticipos y cajas menores**: aprobaciones, desembolsos, saldos, reversiones y conciliación con facturas, con operaciones idempotentes.
- **Vinculación de proveedores y clientes**: formularios con autoguardado, firmas, evaluación de riesgo, documentos condicionales y revisiones en paralelo, integrado con **SIESA ERP**.
- **Middleware biométrico** en Python/FastAPI que conecta dispositivos **ZKTeco** con los horarios del personal: turnos nocturnos, marcaciones duplicadas, tolerancias y horas extra.
- **Sincronización de inventario**: 100.000+ registros por empresa de SIESA/SQL Server a PostgreSQL, incremental y programada.
- **IA aplicada**: pipeline con LLM para extraer datos del RUT colombiano y un asistente interno vía **OpenRouter** con streaming, tool calling, selección de modelo y telemetría de tokens, costo y latencia.

<br>

### 🚀 Proyecto destacado

<table>
  <tr>
    <td>
      <h4>🧾 <a href="https://github.com/sxntixgxs/lab-trxckin">Lab Trxckin</a></h4>
      <p>Versión pública, con datos de demostración, de una plataforma de operaciones financieras para un grupo de empresas colombianas. Lee facturas electrónicas de la DIAN directamente desde buzones de Microsoft 365, las pasa por un flujo de aprobación con control de SLA y se las entrega a contabilidad para causación. También gestiona anticipos y cajas menores.</p>
      <ul>
        <li>📥 Ingesta programada con <b>Microsoft Graph</b> y parseo de XML UBL (<code>AttachedDocument</code> de la DIAN)</li>
        <li>✅ Aprobaciones con devoluciones, notas crédito y SLA en horas hábiles (festivos de Colombia)</li>
        <li>💸 Anticipos: solicitud → jefe directo → contabilidad → gerencia → tesorería → legalización</li>
        <li>🔐 Permisos por rol y ruta, multi-empresa e impersonación de administradores</li>
        <li>🧪 Tests con Vitest y <code>convex-test</code>, CI en GitHub Actions</li>
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

### 📈 Mis stats en GitHub
<br>

<div align="center">
  <img height="150em" src="https://github-readme-stats-sigma-five.vercel.app/api?username=sxntixgxs&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
  <img height="150em" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=sxntixgxs&layout=compact&langs_count=7&theme=dracula&include_all_commits=true&count_private=true"/>
</div>

<br>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=sxntixgxs&theme=dracula&hide_border=true" alt="GitHub streak" />
</div>

<br>

### 🛠️ Tecnologías y Herramientas que más uso

**Lenguajes**
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

**Backend y bases de datos**
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

**Infraestructura y entrega**
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

### 🫂 Conectemos
<div align="center">
  <a href="https://www.linkedin.com/in/santiagosandovalt/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:santiagosandovalt@hotmail.com"><img src="https://img.shields.io/badge/-Email-%230078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white"></a>
  <a href="https://github.com/sxntixgxs" target="_blank"><img src="https://img.shields.io/badge/-GitHub-%23181717?style=for-the-badge&logo=github&logoColor=white"></a>
</div>

<br>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=sxntixgxs&label=Visitas%20al%20perfil&color=bd93f9&style=flat" alt="Visitas al perfil" />
</div>

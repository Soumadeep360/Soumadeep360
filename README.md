<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Soumadeep%20Sarkar&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Backend%20Engineer%20%40%20Razorpay%20%E2%80%A2%20Go%20%E2%80%A2%20gRPC%20%E2%80%A2%20Distributed%20Systems&descAlignY=58&descSize=18&animation=fadeIn" width="100%" alt="Soumadeep Sarkar banner"/>
</p>

<p align="center">
  <a href="https://github.com/Soumadeep360">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3200&pause=900&color=38BDF8&center=true&vCenter=true&width=720&lines=Backend+Engineer+%E2%80%A2+Distributed+Systems;Building+systems+that+don%27t+page+you+at+3+AM;Idempotent+by+default.+Observable+by+design.;learn()+%E2%86%92+build()+%E2%86%92+ship()+%E2%86%92+repeat()" alt="Typing intro"/>
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/soumadeepsarkar/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:soumadeepsarkar4@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://leetcode.com/NebulaNomad/"><img src="https://img.shields.io/badge/LeetCode-1837-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
  <a href="https://www.codechef.com/users/agnition"><img src="https://img.shields.io/badge/CodeChef-3%E2%98%85%201631-5B4638?style=for-the-badge&logo=codechef&logoColor=white" alt="CodeChef"/></a>
</p>

---

## 👋 About me

I'm a **Software Development Engineer (Backend)** at **[Razorpay](https://razorpay.com)**, Bangalore, on the RazorpayX Payroll platform. I build the systems that compute and pay salaries for **10,000+ merchants** and **13M+ payslips** a year: durable workflow engines, gRPC microservices, large migrations, and the on-call tooling that keeps them healthy.

- 🏗️ I like owning a system end to end: design doc, build, rollout, alerts, on-call
- 🤖 Lately: agentic workflows that take a PRD all the way to tested code
- 🏆 Razorpay **AI Hackathon 2025, 1st place** · **Best Performer** · **AI Adoption Award**
- 🎓 B.E. Computer Science, Ramaiah Institute of Technology (2025)
- 💬 Open to backend roles in any domain. Say hi on [LinkedIn](https://www.linkedin.com/in/soumadeepsarkar/)

---

## 🏢 What I've shipped at Razorpay

> My Razorpay code lives in private company repositories, so it doesn't appear as public repos here.
> The green squares and the stats below do include that work (counted anonymously by GitHub), and this is what it adds up to.

<table>
  <tr>
    <td align="center"><h3>10,000+</h3><sub>merchants on the payroll platform</sub></td>
    <td align="center"><h3>13M+</h3><sub>payslips a year</sub></td>
    <td align="center"><h3>700+</h3><sub>merchants migrated, zero downtime</sub></td>
    <td align="center"><h3>50+</h3><sub>Sev-1/Sev-2 incidents closed</sub></td>
  </tr>
  <tr>
    <td align="center"><h3>230+</h3><sub>pull requests in private org repos</sub></td>
    <td align="center"><h3>13 teams</h3><sub>use my agentic workflows</sub></td>
    <td align="center"><h3>1–2 days → ~15 min</h3><sub>test-env setup time</sub></td>
    <td align="center"><h3>45%</h3><sub>of payroll merchants on the Jify lending integration</sub></td>
  </tr>
</table>

| Area | What I did |
|---|---|
| ⚙️ **Durable workflows** | Architected a **Temporal**-based workflow engine for payroll finalization from scratch: parent-child orchestration, parallel batches, retry/timeout/rollback, idempotent request tracking and a scheduled stuck-event detector, running **10,000+ payroll runs per cycle** with Prometheus observability. |
| 🚨 **Incident response** | Root-caused a production monetary-loss incident (PF contribution mismatches) and shipped auto-skip protection across sync, async and auto-payroll paths in **1 business day**, before the next run. Publicly recognized. |
| ☁️ **Cell architecture cutover** | Moved **4 payroll microservices** to a new isolated AWS account under Razorpay's cell-based architecture: made each service cell-ready, ran the DB migrations, set up canary deployments and tested every workflow end to end. **1 month, zero downtime.** |
| 🔁 **Monolith → microservices** | Migration and reverse-migration of **700+ merchants** over **gRPC**, with idempotent configurable batching and safe rollback. |
| 🤝 **Lending integration** | Two-way integration with **Jify**, an external fintech partner: their APIs in, new APIs (incl. bulk endpoints) out, EMIs deducted at source before payouts. **200K+ requests** served. |
| 🤖 **Agentic engineering** | Agentic SDLC workflows (PRD → reviewed tech spec → TDD plan → parallel sub-agents → browser-automated E2E tests), a devstack workflow that deploys any team's services to Kubernetes and self-heals crash-looping pods, and an on-call resolver that produces a documented RCA from code, Coralogix, Grafana and Redash in **under 20 minutes**. |
| 📊 **Platform (intern)** | A report-rendering framework adopted as the team standard (**20+ reports**, new report time **3–5 days → under 1 day**) and an RBAC permission middleware covering every report. |

---

## 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,php,python,cpp,java,c,js&perline=7" alt="Languages"/><br/><br/>
  <img src="https://skillicons.dev/icons?i=laravel,nodejs,express,postgres,mysql,mongodb&perline=6" alt="Frameworks and databases"/><br/><br/>
  <img src="https://skillicons.dev/icons?i=docker,aws,prometheus,grafana,git&perline=5" alt="Infra and tools"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white" alt="gRPC"/>
  <img src="https://img.shields.io/badge/Protocol_Buffers-4285F4?style=flat-square&logo=google&logoColor=white" alt="Protocol Buffers"/>
  <img src="https://img.shields.io/badge/Temporal-000000?style=flat-square&logo=temporal&logoColor=white" alt="Temporal"/>
  <img src="https://img.shields.io/badge/GORM-00ADD8?style=flat-square&logo=go&logoColor=white" alt="GORM"/>
  <img src="https://img.shields.io/badge/REST_APIs-009688?style=flat-square&logo=fastapi&logoColor=white" alt="REST"/>
  <img src="https://img.shields.io/badge/Coralogix-3A4CDE?style=flat-square" alt="Coralogix"/>
  <img src="https://img.shields.io/badge/Redash-FF7964?style=flat-square&logo=redash&logoColor=white" alt="Redash"/>
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code"/>
  <img src="https://img.shields.io/badge/LLM_Agents-7C3AED?style=flat-square&logo=openaigym&logoColor=white" alt="LLM Agents"/>
</p>

**Distributed systems:** durable workflows · microservices · idempotency · multi-tenant isolation · zero-downtime migrations · observability (p99/p95 alerting)

---

## 🚀 Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧲 <a href="https://github.com/Soumadeep360/torrent-client">BitTorrent Client</a></h3>
      <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/> <img src="https://img.shields.io/badge/Concurrency-555?style=flat-square"/><br/><br/>
      A BitTorrent client from scratch in Go: bencode parsing, tracker announce, TCP peer handshake, SHA-1 piece verification and resumable downloads. A <b>50-goroutine</b> worker pool with unbuffered-channel backpressure keeps memory bounded. Tested on a <b>754 MB</b> Debian ISO (3,000+ pieces) from <b>40+ live peers</b>.
    </td>
    <td width="50%" valign="top">
      <h3>🏆 Agentic Payroll Customization (BYOP)</h3>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/LLM_Agents-7C3AED?style=flat-square"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/><br/><br/>
      <b>1st place, Razorpay AI Hackathon 2025.</b> Admins describe a payroll customization in plain English and an AI agent writes, tests and ships a working module (schema, migrations, APIs) in about <b>11 minutes</b>. Least-privilege, multi-tenant design: a sandboxed agent, a read-only ASGI host and schema-per-module PostgreSQL. <i>(Internal, no public code.)</i>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🌐 <a href="https://github.com/Soumadeep360/multi-threaded-proxy-server">Multi-threaded Proxy Server</a></h3>
      <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/> <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black"/><br/><br/>
      A concurrent HTTP proxy with an LRU cache, written in Go (plus an earlier <a href="https://github.com/Soumadeep360/MultiThreadedProxyServerClient">version in C</a>).
    </td>
    <td width="50%" valign="top">
      <h3>🌱 Open source</h3>
      Merged PRs to <a href="https://github.com/mattjegan/awesome-hacktoberfest">awesome-hacktoberfest</a>, <a href="https://github.com/yashpapa6969/erp-crm">erp-crm</a> (quarterly lead analytics, date-range queries) and <a href="https://github.com/avinashvrm/dev-onboarding-ai-hackathon">dev-onboarding-ai-hackathon</a>.
    </td>
  </tr>
</table>

---

## 📈 GitHub activity

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Soumadeep360&theme=tokyonight&hide_border=true&background=0D1117&ring=38BDF8&fire=38BDF8&currStreakLabel=38BDF8" alt="Contribution streak" height="170"/>
</p>


<p align="center">
  <img src="https://ghchart.rshah.org/38BDF8/Soumadeep360" alt="Contribution heatmap" width="100%"/>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Soumadeep360/Soumadeep360/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Soumadeep360/Soumadeep360/output/github-snake.svg"/>
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/Soumadeep360/Soumadeep360/output/github-snake-dark.svg" width="100%"/>
  </picture>
</p>

---

## 🧠 Competitive programming

<p align="center">
  <a href="https://leetcode.com/NebulaNomad/"><img src="https://leetcard.jacoblin.cool/NebulaNomad?theme=dark&font=Fira%20Code&ext=contest&border=0&radius=10" alt="LeetCode stats" width="480"/></a>
</p>

<p align="center">
  LeetCode max <b>1837</b> · <b>580+</b> problems · Global rank 1866 in Weekly Contest 374<br/>
  CodeChef <b>3★</b> max <b>1631</b> · top 30 globally in Starters 111 (Div. 3)
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" width="100%" alt="footer"/>
</p>

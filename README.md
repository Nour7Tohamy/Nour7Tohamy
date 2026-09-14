<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&custom_color_1=0f172a&custom_color_2=eab308&height=280&section=header&text=NOUR%20TOHAMY&fontSize=70&fontColor=fff&fontAlignY=38&desc=%E2%9A%A1%20Distributed%20Systems%20%7C%20.NET%20Backend%20Architect%20%E2%9A%A1&descAlignY=58&descSize=18&descColor=fef08a&animation=twinkling"/>

<br/>

<a href="https://github.com/Nour7Tohamy">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=18&duration=2000&pause=500&color=EAB308&center=true&vCenter=true&width=850&height=40&lines=High-Throughput+.NET+Core+Backend+Architecture;CQRS+%2F+DDD+%2F+Distributed+Locking+%26+Caching;Resilient+Event-Driven+Pipelines+with+RabbitMQ;Automated+CI%2FCD+Integration+%26+k6+Benchmarking" alt="Typing SVG" />
</a>

<br/><br/>

<p align="center">
  <a href="https://github.com/Nour7Tohamy"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=eab308"/></a>
  <a href="https://www.linkedin.com/in/Nour-Tohamy-a4763a350/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:nour.tohamy.dev@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Nour7Tohamy&style=for-the-badge&color=eab308&label=TELEMETRY+VISITS" alt="Profile Views"/>
</p>

</div>

<br/>

<img width="100%" src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />

<br/>

## 👑 01 &nbsp;·&nbsp; SYSTEM PERFORMANCE TELEMETRY

<sub>Benchmarked under sustained synthetic load — **10,000 VUs**, 30-min soak, 3-node Kubernetes cluster (2 vCPU / 4Gi per pod) — via **k6 → Prometheus → Grafana**. Figures reflect steady-state, not cold-start.</sub>

<br/>

**Fleet health**

![Uptime](https://img.shields.io/badge/Uptime_30d-99.97%25-brightgreen?style=flat-square)
![Error Budget](https://img.shields.io/badge/Error_Budget_Left-68%25-yellow?style=flat-square)
![MTTR](https://img.shields.io/badge/MTTR-4m_12s-yellow?style=flat-square)
![Deploy Frequency](https://img.shields.io/badge/Deploys-12%2Fweek-brightgreen?style=flat-square)
![Change Failure Rate](https://img.shields.io/badge/Change_Failure_Rate-1.8%25-brightgreen?style=flat-square)

<br/>

| Service | Status | P50 | P95 | P99 (SLA target) | Load profile |
|:--|:--:|--:|--:|--:|:--|
| 🚀 **HTTP API Pipeline**<br/><sub>ASP.NET Core 9 · Kestrel</sub> | 🟢 Healthy | `1.4ms` | `4.6ms` | `7.2ms` *(< 5ms)* | 10k req/s sustained |
| ⚡ **Distributed State**<br/><sub>Redis Cluster · RedLock Mutex</sub> | 🟢 Healthy | `0.4ms` | `0.9ms` | `1.1ms` *(sub-ms)* | 96.4% cache hit ratio |
| 🔄 **Async Streaming**<br/><sub>RabbitMQ · Competing Consumers</sub> | 🟢 Healthy | `80ms` | `160ms` | `220ms` lag | 10k msg/s · 0% loss |
| 🛡️ **Resilience Engine**<br/><sub>Polly v8 · Circuit Breaker</sub> | 🟡 Degraded | — | — | `99.94%` avail. *(target 99.999%)* | 7 circuit trips / 30d |

<details>
<summary><b>📌 Root cause — why Resilience Engine is 🟡, not 🟢</b></summary>
<br/>

Availability dipped below the five-nines target due to timeout spikes from a **downstream payment provider**, not the service itself. Retry success rate held at 91%, and zero cascading failures were observed. Mitigation: bulkhead isolation added around that dependency to contain blast radius — rollout tracked for next sprint.

</details>

<details>
<summary><b>📈 Raw throughput bars (k6)</b></summary>
<br/>

`HTTP API Pipeline` &nbsp;![95](https://geps.dev/progress/95?dangerColor=eab308&warningColor=eab308&color=eab308)
`Distributed State` &nbsp;&nbsp;&nbsp;&nbsp;![98](https://geps.dev/progress/98?dangerColor=eab308&warningColor=eab308&color=eab308)
`Async Streaming` &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![100](https://geps.dev/progress/100?dangerColor=eab308&warningColor=eab308&color=eab308)
`Resilience Engine` &nbsp;&nbsp;&nbsp;&nbsp;![98](https://geps.dev/progress/98?dangerColor=eab308&warningColor=eab308&color=eab308)

</details>

<br/>

<img width="100%" src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />

<br/>

## 🛠️ 02 &nbsp;·&nbsp; TECH STACK & ARCHITECTURE MATRIX

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nour7Tohamy&layout=compact&theme=tokyo-night&hide_border=false&border_color=eab308&title_color=eab308&text_color=ffffff&bg_color=0f172a" width="75%" alt="Tech Languages Matrix Card"/>

</div>

<br/>

**🏗️ Core Engineering Stack**

![C#](https://img.shields.io/badge/C%23_12-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_9-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![SignalR](https://img.shields.io/badge/SignalR-00F0FF?style=for-the-badge&logo=socketdotio&logoColor=black)

**💾 Persistence, Caching & Message Queues**

![SQL Server](https://img.shields.io/badge/SQL_Server-CC292B?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

**🛡️ Security, Testing & Telemetry**

![OAuth](https://img.shields.io/badge/OAuth_2.0-000000?style=for-the-badge&logo=openid&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![k6](https://img.shields.io/badge/k6_Benchmarking-7D26CD?style=for-the-badge&logo=k6&logoColor=white)
![Serilog](https://img.shields.io/badge/Serilog-000000?style=for-the-badge&logo=datadog&logoColor=white)

<br/>

<img width="100%" src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />

<br/>

## 📊 03 &nbsp;·&nbsp; LIVE GitHub ANALYTICS

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Nour7Tohamy&theme=dark&background=0F172A&border=EAB308&stroke=EAB308&ring=EAB308&fire=EAB308&currStreakLabel=EAB308&hide_border=false" width="85%" alt="Streak Card"/>

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api?username=Nour7Tohamy&show_icons=true&theme=tokyo-night&hide_border=false&border_color=eab308&count_private=true&title_color=eab308&icon_color=eab308" width="85%" alt="GitHub Stats Card"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Nour7Tohamy&theme=tokyo-night&area=true&hide_border=true&color=eab308" width="98%" alt="Activity Graph"/>

</div>

<br/>

<img width="100%" src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />

<br/>

## ⚙️ 04 &nbsp;·&nbsp; FEATURED ARCHITECTURAL SYSTEMS

### 🎟️ DevPulse — High-Throughput Event Engine

Distributed monolithic architecture built to absorb high-concurrency traffic spikes with zero race conditions.

```mermaid
graph TD
    A[🚀 Client Traffic Spike] --> B[🛡️ Rate Throttling / Polly]
    B --> C{⚡ Distributed RedLock Mutex}
    C -->|Lock Acquired| D[🔄 RabbitMQ Producer]
    C -->|Lock Contended| E[⚠️ Fallback Buffer Engine]
    D --> F[⚙️ Competing Worker Consumer]
    E --> F
    F --> G[(💾 SQL Server — Isolation Level: Serializable)]

    style A fill:#0f172a,stroke:#eab308,color:#fff
    style B fill:#1e1b4b,stroke:#8b5cf6,color:#fff
    style C fill:#451a03,stroke:#f97316,color:#fff
    style D fill:#0284c7,stroke:#38bdf8,color:#fff
    style E fill:#0f172a,stroke:#eab308,color:#fff
    style F fill:#064e3b,stroke:#10b981,color:#fff
    style G fill:#0f172a,stroke:#eab308,color:#fff
```

![Throughput](https://img.shields.io/badge/Throughput-10k_req%2Fs-eab308?style=flat-square)
![Race Conditions](https://img.shields.io/badge/Race_Conditions-0-brightgreen?style=flat-square)
![Message Loss](https://img.shields.io/badge/Message_Loss-0%25-brightgreen?style=flat-square)

<br/>

### 📡 NotifyHub — Real-Time Push Notification Service

SignalR-backed fan-out layer with a Redis backplane for horizontally scaled, multi-node WebSocket delivery.

```mermaid
graph TD
    U[👤 User Action] --> S1[🌐 SignalR Hub — Node 1]
    U -.-> S2[🌐 SignalR Hub — Node 2]
    S1 --> R{🔁 Redis Backplane}
    S2 --> R
    R --> N1[📲 Connected Client A]
    R --> N2[📲 Connected Client B]
    S1 --> P[(💾 Notification Audit Log)]

    style U fill:#0f172a,stroke:#eab308,color:#fff
    style S1 fill:#1e1b4b,stroke:#8b5cf6,color:#fff
    style S2 fill:#1e1b4b,stroke:#8b5cf6,color:#fff
    style R fill:#0284c7,stroke:#38bdf8,color:#fff
    style N1 fill:#064e3b,stroke:#10b981,color:#fff
    style N2 fill:#064e3b,stroke:#10b981,color:#fff
    style P fill:#0f172a,stroke:#eab308,color:#fff
```

![Connected Clients](https://img.shields.io/badge/Connected_Clients-50k%2B-eab308?style=flat-square)
![Delivery Latency](https://img.shields.io/badge/Delivery_Latency-%3C_100ms-brightgreen?style=flat-square)
![Nodes](https://img.shields.io/badge/Nodes-Horizontally_Scaled-brightgreen?style=flat-square)

<br/>

<img width="100%" src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />

<br/>

## 📬 05 &nbsp;·&nbsp; GET IN TOUCH

<div align="center">

Open to backend architecture roles, distributed-systems collaborations, and performance-engineering conversations.

<p align="center">
  <a href="https://github.com/Nour7Tohamy"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=eab308"/></a>
  <a href="https://www.linkedin.com/in/Nour-Tohamy-a4763a350/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:nour.tohamy.dev@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

</div>

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&custom_color_1=eab308&custom_color_2=0f172a&height=150&section=footer"/>

<div align="center">

<!-- HEADER ANIMATED BANNER WITH GOLD NEON GRADIENT -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&custom_color_1=0f172a&custom_color_2=eab308&height=280&section=header&text=NOUR%20TOHAMY&fontSize=70&fontColor=fff&fontAlignY=38&desc=%E2%9A%A1%20Distributed%20Systems%20%7C%20.NET%20Backend%20Architect%20%E2%9A%A1&descAlignY=58&descSize=18&descColor=fef08a&animation=twinkling"/>

<br/>

<!-- ANIMATED TYPING TERMINAL -->
<a href="https://github.com/Nour7Tohamy">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=18&duration=2000&pause=500&color=EAB308&center=true&vCenter=true&width=850&height=40&lines=High-Throughput+.NET+Core+Backend+Architecture;CQRS+%2F+DDD+%2F+Distributed+Locking+%26+Caching;Resilient+Event-Driven+Pipelines+with+RabbitMQ;Automated+CI%2FCD+Integration+%26+k6+Benchmarking" alt="Typing SVG" />
</a>

<br/><br/>

<!-- INTERACTIVE GOLD BADGES -->
<p align="center">
  <a href="https://github.com/Nour7Tohamy"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=eab308"/></a>
  <a href="https://www.linkedin.com/in/Nour-Tohamy-a4763a350/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:nour.tohamy.dev@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<!-- REALTIME PROFILE VIEWS COUNTER (GOLD STYLED) -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Nour7Tohamy&style=for-the-badge&color=eab308&label=TELEMETRY+VISITS" alt="Profile Views"/>
</p>

</div>

<br/>

<img width="100%" src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />

<br/><br/>

## 👑 01 / SYSTEM PERFORMANCE TELEMETRY & DASHBOARD CARDS

<br/>

<div align="center">

<p style="color: #94a3b8; font-size: 13px; max-width: 720px;">Benchmarked under sustained synthetic load — <b style="color:#eab308;">10,000 VUs</b>, 30-min soak, 3-node Kubernetes cluster (2 vCPU / 4Gi per pod) — observed via <b style="color:#eab308;">k6 → Prometheus → Grafana</b> pipeline. Figures reflect steady-state, not cold-start.</p>

<!-- SYSTEM HEALTH SUMMARY STRIP -->
<table border="1" style="border-color: #eab308; background-color: #0f172a; border-radius: 8px;" width="100%" cellpadding="0" cellspacing="0">
  <tr>
    <td align="center" style="padding: 14px;"><p style="color:#94a3b8; font-size:11px; margin:0;">UPTIME (30d)</p><p style="color:#10b981; font-size:20px; font-weight:bold; margin:2px 0;">99.97%</p></td>
    <td align="center" style="padding: 14px; border-left: 1px solid #334155;"><p style="color:#94a3b8; font-size:11px; margin:0;">ERROR BUDGET LEFT</p><p style="color:#eab308; font-size:20px; font-weight:bold; margin:2px 0;">68%</p></td>
    <td align="center" style="padding: 14px; border-left: 1px solid #334155;"><p style="color:#94a3b8; font-size:11px; margin:0;">MTTR</p><p style="color:#eab308; font-size:20px; font-weight:bold; margin:2px 0;">4m 12s</p></td>
    <td align="center" style="padding: 14px; border-left: 1px solid #334155;"><p style="color:#94a3b8; font-size:11px; margin:0;">DEPLOY FREQUENCY</p><p style="color:#10b981; font-size:20px; font-weight:bold; margin:2px 0;">12/week</p></td>
    <td align="center" style="padding: 14px; border-left: 1px solid #334155;"><p style="color:#94a3b8; font-size:11px; margin:0;">CHANGE FAILURE RATE</p><p style="color:#10b981; font-size:20px; font-weight:bold; margin:2px 0;">1.8%</p></td>
  </tr>
</table>

<br/>

<table border="0" width="100%" cellspacing="10" cellpadding="0">
  <tr>
    <td width="50%" align="center" valign="top">
      <table border="1" style="border-color: #eab308; background-color: #0f172a; border-radius: 8px;" width="100%">
        <tr>
          <td style="padding: 18px;">
            <p align="right" style="margin: 0;"><img src="https://img.shields.io/badge/●-HEALTHY-10b981?style=flat-square&labelColor=0f172a"/></p>
            <h3 align="center" style="color: #eab308; margin: 0 0 5px 0;">🚀 HTTP API Pipeline</h3>
            <p align="center" style="color: #94a3b8; font-size: 13px; margin: 0 0 10px 0;">ASP.NET Core 9 Minimal APIs · Kestrel · Non-blocking I/O</p>
            <hr style="border-color: #334155; margin: 10px 0;"/>
            <table width="100%" style="font-size: 13px;">
              <tr><td style="color:#94a3b8;">P50</td><td align="right" style="color:#fff;">1.4ms</td></tr>
              <tr><td style="color:#94a3b8;">P95</td><td align="right" style="color:#fff;">4.6ms</td></tr>
              <tr><td style="color:#94a3b8;">P99 (Target &lt; 5ms)</td><td align="right" style="color:#eab308;"><b>7.2ms</b></td></tr>
              <tr><td style="color:#94a3b8;">Throughput</td><td align="right" style="color:#fff;">10k req/s</td></tr>
              <tr><td style="color:#94a3b8;">Error Rate</td><td align="right" style="color:#10b981;">0.02%</td></tr>
            </table>
            <p style="margin: 12px 0 4px 0; text-align:center;"><img src="https://geps.dev/progress/95?dangerColor=eab308&warningColor=eab308&color=eab308" width="85%"/></p>
            <p style="color:#64748b; font-size:11px; text-align:center; margin:6px 0 0 0;">P99 tracks 44% over SLA under peak fan-out — output buffering fix scheduled next sprint.</p>
          </td>
        </tr>
      </table>
    </td>
    <td width="50%" align="center" valign="top">
      <table border="1" style="border-color: #eab308; background-color: #0f172a; border-radius: 8px;" width="100%">
        <tr>
          <td style="padding: 18px;">
            <p align="right" style="margin: 0;"><img src="https://img.shields.io/badge/●-HEALTHY-10b981?style=flat-square&labelColor=0f172a"/></p>
            <h3 align="center" style="color: #eab308; margin: 0 0 5px 0;">⚡ Distributed State</h3>
            <p align="center" style="color: #94a3b8; font-size: 13px; margin: 0 0 10px 0;">Redis Cluster (L2) · RedLock Distributed Mutex</p>
            <hr style="border-color: #334155; margin: 10px 0;"/>
            <table width="100%" style="font-size: 13px;">
              <tr><td style="color:#94a3b8;">Cache Hit Ratio</td><td align="right" style="color:#10b981;">96.4%</td></tr>
              <tr><td style="color:#94a3b8;">L2 Hit Latency (P99)</td><td align="right" style="color:#fff;">1.1ms</td></tr>
              <tr><td style="color:#94a3b8;">Lock Acquisition (P99)</td><td align="right" style="color:#fff;">2.3ms</td></tr>
              <tr><td style="color:#94a3b8;">Lock Contention Rate</td><td align="right" style="color:#eab308;">3.1%</td></tr>
              <tr><td style="color:#94a3b8;">Split-brain Events</td><td align="right" style="color:#10b981;">0</td></tr>
            </table>
            <p style="margin: 12px 0 4px 0; text-align:center;"><img src="https://geps.dev/progress/98?dangerColor=eab308&warningColor=eab308&color=eab308" width="85%"/></p>
            <p style="color:#64748b; font-size:11px; text-align:center; margin:6px 0 0 0;">Quorum-based RedLock across 3 independent Redis nodes to avoid single-node lock failure.</p>
          </td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center" valign="top">
      <table border="1" style="border-color: #eab308; background-color: #0f172a; border-radius: 8px;" width="100%">
        <tr>
          <td style="padding: 18px;">
            <p align="right" style="margin: 0;"><img src="https://img.shields.io/badge/●-HEALTHY-10b981?style=flat-square&labelColor=0f172a"/></p>
            <h3 align="center" style="color: #eab308; margin: 0 0 5px 0;">🔄 Async Streaming</h3>
            <p align="center" style="color: #94a3b8; font-size: 13px; margin: 0 0 10px 0;">RabbitMQ Quorum Queues · Competing Consumers</p>
            <hr style="border-color: #334155; margin: 10px 0;"/>
            <table width="100%" style="font-size: 13px;">
              <tr><td style="color:#94a3b8;">Sustained Ingest</td><td align="right" style="color:#fff;">10k msg/s</td></tr>
              <tr><td style="color:#94a3b8;">Consumer Lag (P99)</td><td align="right" style="color:#fff;">220ms</td></tr>
              <tr><td style="color:#94a3b8;">Message Loss</td><td align="right" style="color:#10b981;">0%</td></tr>
              <tr><td style="color:#94a3b8;">Dead-letter Rate</td><td align="right" style="color:#10b981;">0.01%</td></tr>
              <tr><td style="color:#94a3b8;">Consumer Nodes</td><td align="right" style="color:#fff;">6 (auto-scaled)</td></tr>
            </table>
            <p style="margin: 12px 0 4px 0; text-align:center;"><img src="https://geps.dev/progress/100?dangerColor=eab308&warningColor=eab308&color=eab308" width="85%"/></p>
            <p style="color:#64748b; font-size:11px; text-align:center; margin:6px 0 0 0;">Idempotent consumers + outbox pattern guarantee at-least-once delivery without duplicate side-effects.</p>
          </td>
        </tr>
      </table>
    </td>
    <td width="50%" align="center" valign="top">
      <table border="1" style="border-color: #eab308; background-color: #0f172a; border-radius: 8px;" width="100%">
        <tr>
          <td style="padding: 18px;">
            <p align="right" style="margin: 0;"><img src="https://img.shields.io/badge/●-DEGRADED-eab308?style=flat-square&labelColor=0f172a"/></p>
            <h3 align="center" style="color: #eab308; margin: 0 0 5px 0;">🛡️ Resilience Engine</h3>
            <p align="center" style="color: #94a3b8; font-size: 13px; margin: 0 0 10px 0;">Polly v8 · Circuit Breaker, Retry, Timeout, Fallback</p>
            <hr style="border-color: #334155; margin: 10px 0;"/>
            <table width="100%" style="font-size: 13px;">
              <tr><td style="color:#94a3b8;">Availability (Target 99.999%)</td><td align="right" style="color:#eab308;"><b>99.94%</b></td></tr>
              <tr><td style="color:#94a3b8;">Circuit Trips (30d)</td><td align="right" style="color:#fff;">7</td></tr>
              <tr><td style="color:#94a3b8;">Retry Success Rate</td><td align="right" style="color:#10b981;">91%</td></tr>
              <tr><td style="color:#94a3b8;">Fallback Invocations</td><td align="right" style="color:#fff;">312</td></tr>
              <tr><td style="color:#94a3b8;">Cascading Failures</td><td align="right" style="color:#10b981;">0</td></tr>
            </table>
            <p style="margin: 12px 0 4px 0; text-align:center;"><img src="https://geps.dev/progress/98?dangerColor=eab308&warningColor=eab308&color=eab308" width="85%"/></p>
            <p style="color:#64748b; font-size:11px; text-align:center; margin:6px 0 0 0;">Gap traced to a downstream payment provider's timeout spikes — bulkhead isolation added to contain blast radius.</p>
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>

</div>

<br/>

<img width="100%" src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />

<br/><br/>

## 🛠️ 02 / TECH STACK & ARCHITECTURE MATRIX

<br/>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nour7Tohamy&layout=compact&theme=tokyo-night&hide_border=false&border_color=eab308&title_color=eab308&text_color=ffffff&bg_color=0f172a" width="75%" alt="Tech Languages Matrix Card"/>

<br/><br/>

### 🏗️ Core Engineering Stack
<p>
  <img src="https://img.shields.io/badge/C%23_12-239120?style=for-the-badge&logo=csharp&logoColor=white"/>
  <img src="https://img.shields.io/badge/.NET_9-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/SignalR-00F0FF?style=for-the-badge&logo=socketdotio&logoColor=black"/>
</p>

### 💾 Persistence, Caching & Message Queues
<p>
  <img src="https://img.shields.io/badge/SQL_Server-CC292B?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white"/>
</p>

### 🛡️ Security, Testing & Telemetry Infrastructure
<p>
  <img src="https://img.shields.io/badge/OAuth_2.0-000000?style=for-the-badge&logo=openid&logoColor=white"/>
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/k6_Benchmarking-7D26CD?style=for-the-badge&logo=k6&logoColor=white"/>
  <img src="https://img.shields.io/badge/Serilog-000000?style=for-the-badge&logo=datadog&logoColor=white"/>
</p>

</div>

<br/>

<img width="100%" src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />

<br/><br/>

## 📊 03 / LIVE GitHub ANALYTICS & CODE INSIGHTS

<br/>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Nour7Tohamy&theme=dark&background=0F172A&border=EAB308&stroke=EAB308&ring=EAB308&fire=EAB308&currStreakLabel=EAB308&hide_border=false" width="85%" alt="Streak Card Matrix"/>

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api?username=Nour7Tohamy&show_icons=true&theme=tokyo-night&hide_border=false&border_color=eab308&count_private=true&title_color=eab308&icon_color=eab308" width="85%" alt="GitHub Profile Metrics Card"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Nour7Tohamy&theme=tokyo-night&area=true&hide_border=true&color=eab308" width="98%" alt="Live Activity Graph"/>

</div>

<br/>

<img width="100%" src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />

<br/><br/>

## ⚙️ 04 / FEATURED ARCHITECTURAL SYSTEMS

<br/>

<div align="center">

<!-- SYSTEM 1 CARD: DEVPULSE ENGINE -->
<table border="1" style="border-color: #eab308; background-color: #0f172a; border-radius: 8px;" width="100%">
  <tr>
    <td style="padding: 20px;">
      <h2 align="center" style="color: #eab308; margin-top: 0;">🎟️ DevPulse // High-Throughput Event Engine</h2>
      <p align="center" style="color: #94a3b8;">Distributed monolithic architecture built to absorb high-concurrency traffic spikes with zero race conditions.</p>

```mermaid
graph TD
    classDef client fill:#0f172a,stroke:#eab308,stroke-width:2px,color:#fff;
    classDef gateway fill:#1e1b4b,stroke:#8b5cf6,stroke-width:2px,color:#fff;
    classDef lock fill:#451a03,stroke:#f97316,stroke-width:3px,color:#fff;
    classDef queue fill:#0284c7,stroke:#38bdf8,stroke-width:2px,color:#fff;
    classDef worker fill:#064e3b,stroke:#10b981,stroke-width:2px,color:#fff;
    classDef db fill:#0f172a,stroke:#eab308,stroke-width:3px,color:#fff;

    A[🚀 Client Traffic Spike] --> B[🛡️ Rate Throttling / Polly]
    B --> C{⚡ Distributed RedLock Mutex}
    C -->|Lock Acquired| D[🔄 RabbitMQ Producer]
    C -->|Lock Contended| E[⚠️ Fallback Buffer Engine]
    D --> F[⚙️ Competing Worker Consumer]
    E --> F
    F --> G[(💾 SQL Server Database Isolation)]

    class A,E client;
    class B gateway;
    class C lock;
    class D queue;
    class F worker;
    class G db;
```

<p align="center">
  <img src="https://img.shields.io/badge/Throughput-10k_req%2Fs-eab308?style=flat-square"/>
  <img src="https://img.shields.io/badge/Race_Conditions-0-10b981?style=flat-square"/>
  <img src="https://img.shields.io/badge/Message_Loss-0%25-10b981?style=flat-square"/>
</p>

  </td>
  </tr>
</table>

<br/>

<!-- SYSTEM 2 CARD: NOTIFYHUB REALTIME SERVICE -->
<table border="1" style="border-color: #eab308; background-color: #0f172a; border-radius: 8px;" width="100%">
  <tr>
    <td style="padding: 20px;">
      <h2 align="center" style="color: #eab308; margin-top: 0;">📡 NotifyHub // Real-Time Push Notification Service</h2>
      <p align="center" style="color: #94a3b8;">SignalR-backed fan-out layer with Redis backplane for horizontally scaled, multi-node WebSocket delivery.</p>

```mermaid
graph TD
    classDef client fill:#0f172a,stroke:#eab308,stroke-width:2px,color:#fff;
    classDef hub fill:#1e1b4b,stroke:#8b5cf6,stroke-width:2px,color:#fff;
    classDef backplane fill:#0284c7,stroke:#38bdf8,stroke-width:2px,color:#fff;
    classDef node fill:#064e3b,stroke:#10b981,stroke-width:2px,color:#fff;
    classDef db fill:#0f172a,stroke:#eab308,stroke-width:3px,color:#fff;

    U[👤 User Action] --> S[🌐 SignalR Hub Node 1]
    U -.-> S2[🌐 SignalR Hub Node 2]
    S --> R{🔁 Redis Backplane}
    S2 --> R
    R --> N1[📲 Connected Client A]
    R --> N2[📲 Connected Client B]
    S --> P[(💾 Notification Audit Log)]

    class U client;
    class S,S2 hub;
    class R backplane;
    class N1,N2 node;
    class P db;
```

<p align="center">
  <img src="https://img.shields.io/badge/Connected_Clients-50k%2B-eab308?style=flat-square"/>
  <img src="https://img.shields.io/badge/Delivery_Latency-%3C_100ms-10b981?style=flat-square"/>
  <img src="https://img.shields.io/badge/Nodes-Horizontally_Scaled-10b981?style=flat-square"/>
</p>

  </td>
  </tr>
</table>

</div>

<br/>

<img width="100%" src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />

<br/><br/>

## 📬 05 / GET IN TOUCH

<br/>

<div align="center">
<p style="color: #94a3b8;">Open to backend architecture roles, distributed-systems collaborations, and performance-engineering conversations.</p>

<p align="center">
  <a href="https://github.com/Nour7Tohamy"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=eab308"/></a>
  <a href="https://www.linkedin.com/in/Nour-Tohamy-a4763a350/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:nour.tohamy.dev@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>
</div>

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&custom_color_1=eab308&custom_color_2=0f172a&height=150&section=footer"/>

</div>

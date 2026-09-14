from pathlib import Path

readme = r'''<div align="center">

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

<!-- GOLD GRADIENT SEPARATOR -->
<img width="100%" src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />

<br/><br/>

## 👑 01 / SYSTEM PERFORMANCE TELEMETRY & DASHBOARD CARDS

<br/>

<div align="center">

<!-- CARDS DASHBOARD CONTAINER GRID -->
<table border="0" width="100%">
  <tr>
    <td width="50%" align="center">
      <!-- DASHBOARD CARD 1: HTTP API PIPELINE -->
      <table border="1" style="border-color: #eab308; background-color: #0f172a;" width="95%">
        <tr>
          <td align="center" style="padding: 15px;">
            <h3 style="color: #eab308; margin: 0;">🚀 HTTP API Pipeline</h3>
            <p style="color: #94a3b8; font-size: 13px;">ASP.NET Core Kestrel + Non-blocking I/O</p>
            <hr style="border-color: #334155;"/>
            <p><b>Target SLA:</b> <code style="color: #10b981;">&lt; 5ms P99</code></p>
            <p><b>Actual Load (k6):</b> <code style="color: #eab308;">7.2ms P99</code></p>
            <img src="https://geps.dev/progress/95?dangerColor=eab308&warningColor=eab308&color=eab308" width="80%"/>
          </td>
        </tr>
      </table>
    </td>
    <td width="50%" align="center">
      <!-- DASHBOARD CARD 2: DISTRIBUTED STATE -->
      <table border="1" style="border-color: #eab308; background-color: #0f172a;" width="95%">
        <tr>
          <td align="center" style="padding: 15px;">
            <h3 style="color: #eab308; margin: 0;">⚡ Distributed State</h3>
            <p style="color: #94a3b8; font-size: 13px;">Redis L2 Cache + RedLock Distributed Mutex</p>
            <hr style="border-color: #334155;"/>
            <p><b>Target SLA:</b> <code style="color: #10b981;">Sub-ms Latency</code></p>
            <p><b>Actual Load (k6):</b> <code style="color: #eab308;">1.1ms (L2 Hit)</code></p>
            <img src="https://geps.dev/progress/98?dangerColor=eab308&warningColor=eab308&color=eab308" width="80%"/>
          </td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <!-- DASHBOARD CARD 3: ASYNC STREAMING -->
      <table border="1" style="border-color: #eab308; background-color: #0f172a;" width="95%">
        <tr>
          <td align="center" style="padding: 15px;">
            <h3 style="color: #eab308; margin: 0;">🔄 Async Streaming</h3>
            <p style="color: #94a3b8; font-size: 13px;">RabbitMQ Event Bus + Competing Consumers</p>
            <hr style="border-color: #334155;"/>
            <p><b>Target SLA:</b> <code style="color: #10b981;">0% Message Loss</code></p>
            <p><b>Actual Load (k6):</b> <code style="color: #eab308;">0% Loss (10k req/s)</code></p>
            <img src="https://geps.dev/progress/100?dangerColor=eab308&warningColor=eab308&color=eab308" width="80%"/>
          </td>
        </tr>
      </table>
    </td>
    <td width="50%" align="center">
      <!-- DASHBOARD CARD 4: RESILIENCE ENGINE -->
      <table border="1" style="border-color: #eab308; background-color: #0f172a;" width="95%">
        <tr>
          <td align="center" style="padding: 15px;">
            <h3 style="color: #eab308; margin: 0;">🛡️ Resilience Engine</h3>
            <p style="color: #94a3b8; font-size: 13px;">Polly (Circuit Breaker, Retry, Fallback)</p>
            <hr style="border-color: #334155;"/>
            <p><b>Target SLA:</b> <code style="color: #10b981;">99.999% SLA</code></p>
            <p><b>Actual Load (k6):</b> <code style="color: #eab308;">99.94% Availability</code></p>
            <img src="https://geps.dev/progress/98?dangerColor=eab308&warningColor=eab308&color=eab308" width="80%"/>
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>

</div>

<br/>

<!-- GOLD GRADIENT SEPARATOR -->
<img width="100%" src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />

<br/><br/>

## 🛠️ 02 / TECH STACK & ARCHITECTURE MATRIX

<br/>

<div align="center">

<!-- TECH METRICS STAT CARD -->
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

<!-- GOLD GRADIENT SEPARATOR -->
<img width="100%" src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />

<br/><br/>

## 📊 03 / LIVE GitHub ANALYTICS & CODE INSIGHTS

<br/>

<div align="center">

<!-- STREAK CARD EXACT MATCH FROM IMAGE -->
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Nour7Tohamy&theme=dark&background=0F172A&border=EAB308&stroke=EAB308&ring=EAB308&fire=EAB308&currStreakLabel=EAB308&hide_border=false" width="85%" alt="Streak Card Matrix"/>

<br/><br/>

<!-- GITHUB OVERALL PROFILE STATS CARD -->
<img src="https://github-readme-stats.vercel.app/api?username=Nour7Tohamy&show_icons=true&theme=tokyo-night&hide_border=false&border_color=eab308&count_private=true&title_color=eab308&icon_color=eab308" width="85%" alt="GitHub Profile Metrics Card"/>

<br/><br/>

<!-- ANIMATED ACTIVITY GRAPH CARDS -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Nour7Tohamy&theme=tokyo-night&area=true&hide_border=true&color=eab308" width="98%" alt="Live Activity Graph"/>

</div>

<br/>

<!-- GOLD GRADIENT SEPARATOR -->
<img width="100%" src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />

<br/><br/>

## ⚙️ 04 / FEATURED ARCHITECTURAL SYSTEMS CARDS

<br/>

<div align="center">

<!-- SYSTEM 1 CARD: DEVPULSE ENGINE -->
<table border="1" style="border-color: #eab308; background-color: #0f172a;" width="100%">
  <tr>
    <td style="padding: 20px;">
      <h2 align="center" style="color: #eab308; margin-top: 0;">🎟️ DevPulse // High-Throughput Event Engine</h2>
      <p align="center" style="color: #94a3b8;">Distributed Monolithic Architecture to absorb high concurrency traffic spikes with zero race conditions.</p>

```mermaid
graph TD
    classDef client fill:#0f172a,stroke:#eab308,stroke-width:2px,color:#fff;
    classDef gateway fill:#1e1b4b,stroke:#8b5cf6,stroke-width:2px,color:#fff;
    classDef lock fill:#451a03,stroke:#f97316,stroke-width:3px,color:#fff;
    classDef queue fill:#0284c7,stroke:#38bdf8,stroke-width:2px,color:#fff;
    classDef worker fill:#064e3b,stroke:#10b981,stroke-width:2px,color:#fff;
    classDef db fill:#0f172a,stroke:#eab308,stroke-width:3px,color:#fff;

    A[🚀 Client Traffic Spike] ::: client --> B[🛡️ Rate Throttling / Polly] ::: gateway
    B --> C{⚡ Distributed RedLock Mutex} ::: lock
    C -->|Lock Acquired| D[🔄 RabbitMQ Producer] ::: queue
    C -->|Lock Contented| E[⚠️ Fallback Buffer Engine] ::: client

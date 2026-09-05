<img src="https://github.com/user-attachments/assets/6487b8f0-7ee9-41ce-8312-f366fbcdf58d" alt="Kawsar Akando" width="100%" />
</p>

<h1 align="center">Hi 👋, I'm Kawsar Akando</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=26&duration=3000&pause=800&color=2563EB&center=true&vCenter=true&width=650&lines=Interested+in+System+Architecture+%26+API+Design" alt="Typing SVG" />
</p>

---

- 👋 Hi, I'm [@kawsar-codes](https://github.com/kawsar-codes)
- 🖥️ I'm currently working with **React, JavaScript and TypeScript** for frontend development.
- 🗄️ Using **Node.js, Express.js, Nest.js, PostgreSQL and MongoDB** for the backend.
- 🐍 Also working with **Python and FastAPI**.
- 🌱 I'm currently learning **System Architecture, API Design and Docker**.
- 💬 Ask me about **Full-Stack (React, Node, Express, PostgreSQL, MongoDB)**.
- 📫 Feel free to reach me out: **mdkawsarakando@gmail.com**
- 📍 Based in **Seoul, South Korea**

---

<h2 align="center">🚀 Technology Stack</h2>

<h4 align="center">Languages:</h4>
<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,python" />
</p>

<h4 align="center">CSS Frameworks & Libraries:</h4>
<p align="center">
  <img src="https://skillicons.dev/icons?i=tailwind,bootstrap,materialui" />
</p>

<h4 align="center">JavaScript Frameworks & Libraries:</h4>
<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,redux,nodejs,express,nestjs" />
</p>

<h4 align="center">Backend & API:</h4>
<p align="center">
  <img src="https://skillicons.dev/icons?i=fastapi,graphql,prisma" />
</p>

<h4 align="center">Database:</h4>
<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql,supabase,redis" />
</p>

<h4 align="center">Deployment Platform:</h4>
<p align="center">
  <img src="https://skillicons.dev/icons?i=vercel,netlify,firebase" />
</p>

<h4 align="center">Design & Graphics:</h4>
<p align="center">
  <img src="https://skillicons.dev/icons?i=figma,ai,ps" />
</p>

<h4 align="center">Tools & Technologies:</h4>
<p align="center">
  <img src="https://skillicons.dev/icons?i=git,github,vscode,postman,docker,notion,linux,androidstudio&perline=4" />
</p>


---

<h2 align="center">🏗️ How I Think About Backend Systems</h2>

```mermaid
flowchart TB
    Client([Client Apps])

    subgraph Edge["🌐 Edge Layer"]
        LB[Load Balancer]
        RL[Rate Limiter]
    end

    subgraph App["⚙️ Application Layer"]
        direction TB
        Auth[Auth Middleware<br/>JWT / Session]
        Valid[Validation<br/>Schema / DTO]
        Ctrl[Controllers]
        Svc[Service Layer<br/>Business Logic]
        Repo[Repository<br/>Data Access]
    end

    subgraph Async["📨 Async Layer"]
        Queue[Job Queue]
        Worker[Background Workers]
    end

    subgraph Data["💾 Persistence"]
        DB[(PostgreSQL<br/>Source of Truth)]
        Cache[(Redis<br/>Cache + Sessions)]
        Store[/Object Storage/]
    end

    Obs[[📊 Logging & Monitoring]]

    Client --> LB --> RL --> Auth
    Auth --> Valid --> Ctrl --> Svc
    Svc --> Repo --> DB
    Svc --> Cache
    Svc -.enqueue.-> Queue
    Queue --> Worker
    Worker --> DB
    Worker --> Store

    App -.metrics.-> Obs
    Async -.metrics.-> Obs

    style Client fill:#2563EB,stroke:#1e40af,color:#fff
    style DB fill:#336791,stroke:#254a68,color:#fff
    style Cache fill:#DC382D,stroke:#a42a22,color:#fff
    style Obs fill:#1e293b,stroke:#475569,color:#fff
```
---
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1240 1650" width="1240" height="1650" role="img" aria-label="Production backend architecture: edge, application, async, data and delivery layers" xmlns:c2pa="http://c2pa.org/manifest"><metadata><c2pa:manifest>AAAWgmp1bWIAAAAeanVtZGMycGEAEQAQgAAAqgA4m3EDYzJwYQAAABZcanVtYgAAAEdqdW1kYzJtYQARABCAAACqADibcQN1cm46YzJwYTphZjlmYzQxYy1jYzRmLTQ1YWMtOGM1YS1kOTE2NmY1MzU3ZmYAAAADl2p1bWIAAAApanVtZGMyYXMAEQAQgAAAqgA4m3EDYzJwYS5hc3NlcnRpb25zAAAAALxqdW1iAAAARGp1bWRjYm9yABEAEIAAAKoAOJtxE2MycGEuaW5ncmVkaWVudC52MwAAAAAYYzJzaIJ8RLQ07OJmX04pHXwM3BMAAABwY2JvcqNpZGM6Zm9ybWF0bWltYWdlL3N2Zyt4bWxqaW5zdGFuY2VJRHgseG1wOmlpZDozYjViM2U4Yi0xMTBlLTRkOTUtOWYxOS0zMWY2YThjM2IwMTdscmVsYXRpb25zaGlwaHBhcmVudE9mAAAB4mp1bWIAAABBanVtZGNib3IAEQAQgAAAqgA4m3ETYzJwYS5hY3Rpb25zLnYyAAAAABhjMnNoo0Q1j6WYKij6AM3bJliSaQAAAZljYm9yomdhY3Rpb25zgqJmYWN0aW9ua2MycGEub3BlbmVkanBhcmFtZXRlcnOha2luZ3JlZGllbnRzgaJjdXJseC1zZWxmI2p1bWJmPWMycGEuYXNzZXJ0aW9ucy9jMnBhLmluZ3JlZGllbnQudjNkaGFzaFggWWWfVk+8uOdnpTFqlTxQOc1IiMTMBt3v9aebNmivFYCkZmFjdGlvbngdY29tLmFudGhyb3BpYy5jbGF1ZGUucHJvdmlkZWRqcGFyYW1ldGVyc6F4H2NvbS5hbnRocm9waWMub3JpZ2luLWNvbmZpZGVuY2VndW5rbm93bmtkZXNjcmlwdGlvbnhmQ2xhdWRlIHByb3ZpZGVkIHRoaXMgZmlsZSBhdCB0aGUgcmVxdWVzdCBvZiBhIHVzZXIgYW5kIG1heSBoYXZlIGNyZWF0ZWQgb3IgbW9kaWZpZWQgdGhlIGZpbGUgY29udGVudHMubXNvZnR3YXJlQWdlbnShZG5hbWVmQ2xhdWRlcmFsbEFjdGlvbnNJbmNsdWRlZPUAAADIanVtYgAAAEBqdW1kY2JvcgARABCAAACqADibcRNjMnBhLmhhc2guZGF0YQAAAAAYYzJzaBMwaihKJaaYbpXXSA9DmuIAAACAY2JvcqVjYWxnZnNoYTI1NmNwYWRMAAAAAAAAAAAAAAAAZGhhc2hYIKhegCPPCiB6INxy0xGszR10ZjIxFVaDiQdQcGucEqgoZG5hbWVuanVtYmYgbWFuaWZlc3RqZXhjbHVzaW9uc4GiZXN0YXJ0GQEGZmxlbmd0aBkeBAAAAj5qdW1iAAAAJ2p1bWRjMmNsABEAEIAAAKoAOJtxA2MycGEuY2xhaW0udjIAAAACD2Nib3KlY2FsZ2ZzaGEyNTZpc2lnbmF0dXJleE1zZWxmI2p1bWJmPS9jMnBhL3VybjpjMnBhOmFmOWZjNDFjLWNjNGYtNDVhYy04YzVhLWQ5MTY2ZjUzNTdmZi9jMnBhLnNpZ25hdHVyZWppbnN0YW5jZUlEeCx4bXA6aWlkOmQwZWZlNjAzLTdmNmEtNDVhNS04YmE5LTBlZGIxZTYwNDU2Y3JjcmVhdGVkX2Fzc2VydGlvbnODomN1cmx4LXNlbGYjanVtYmY9YzJwYS5hc3NlcnRpb25zL2MycGEuaW5ncmVkaWVudC52M2RoYXNoWCBZZZ9WT7y452elMWqVPFA5zUiIxMwG3e/1p5s2aK8VgKJjdXJseCpzZWxmI2p1bWJmPWMycGEuYXNzZXJ0aW9ucy9jMnBhLmFjdGlvbnMudjJkaGFzaFggeAcqjZ4ufk9KK9btr2r/iQCOuUuZvfPh9dsTuT9Rkr+iY3VybHgpc2VsZiNqdW1iZj1jMnBhLmFzc2VydGlvbnMvYzJwYS5oYXNoLmRhdGFkaGFzaFggEpE5fgMQP8NON9rum/EpWIpkxliy8gkJTofZ0fSVYW10Y2xhaW1fZ2VuZXJhdG9yX2luZm+jZG5hbWVvQW50aHJvcGljIEZpbGVzZ3ZlcnNpb25lMS4wLjBrc3BlY1ZlcnNpb25lMi40LjAAABA4anVtYgAAAChqdW1kYzJjcwARABCAAACqADibcQNjMnBhLnNpZ25hdHVyZQAAABAIY2JvctKEWQISogEmGCFZAgowggIGMIIBjaADAgECAhRA5aAK7sI50L64g/oGQgU9Z1UTADAKBggqhkjOPQQDAzBJMRcwFQYDVQQKEw5BbnRocm9waWMsIFBCQzEuMCwGA1UEAxMlQW50aHJvcGljIENvbnRlbnQgQ3JlZGVudGlhbHMgUm9vdCBDQTAeFw0yNjA4MDcxODQzNTZaFw0yODA4MDYxOTQzNTZaMEQxFzAVBgNVBAoTDkFudGhyb3BpYywgUEJDMSkwJwYDVQQDEyBBbnRocm9waWMgQ2xhdWRlIENvbnRlbnQgU2lnbmluZzBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABJh6CmvLUBgFFNU0vUKlOVtE6djd17L5SuwX0LemFisBM3dkd/3cyjxFA3Qo5S46fX0/ihY0VZ7mfb9KF703t5OjWDBWMA4GA1UdDwEB/wQEAwIHgDAVBgNVHSUEDjAMBgorBgEEAYPoXgIBMAwGA1UdEwEB/wQCMAAwHwYDVR0jBBgwFoAUzlHiBIFOZFsj+OPEz5o+nMHXXMIwCgYIKoZIzj0EAwMDZwAwZAIwMXMdFJ4BetLLVY7ORuE9noqbbAZOZn/aArXyTwFAZfKrPzxF2vPoJNf1+UCdg1XGAjBwX1zd9WGqYkqmL5SFqw1QySjr1zJfpJM9+1rdDwSPLMOPOjKuiXjoU/pUUeG9RwmhY3BhZFkNngAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA
AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA
AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAPZYQBK/iTZahLsz/2asomn+pSB4P7QBRAtDXMRyOuMkwqgZnRJ2J8xkN7qJ6e82QeZh7krV7vpXc7XU0cs7yKRp1EY=</c2pa:manifest></metadata>
  <defs>
    <style>
      .bg    { fill: #05070a; }
      .panel { fill: #090c11; stroke: #1a2230; stroke-width: 1.5; }
      .card  { fill: #0e131b; stroke: #26313f; stroke-width: 1.5; }
      .h1    { fill: #f2f6fb; font-family: "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; font-size: 30px; font-weight: 700; }
      .sub   { fill: #66707e; font-family: ui-monospace, "SF Mono", Menlo, Consolas, monospace; font-size: 12.5px; letter-spacing: 1.4px; }
      .lname { font-family: ui-monospace, "SF Mono", Menlo, Consolas, monospace; font-size: 12px; font-weight: 600; letter-spacing: 1.8px; }
      .t     { fill: #e9eff7; font-family: "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; font-size: 14.5px; font-weight: 600; }
      .ts    { fill: #e9eff7; font-family: "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; font-size: 13px; font-weight: 600; }
      .m     { fill: #78828f; font-family: ui-monospace, "SF Mono", Menlo, Consolas, monospace; font-size: 10.5px; }
      .num   { fill: #8a94a2; font-family: ui-monospace, "SF Mono", Menlo, Consolas, monospace; font-size: 10px; font-weight: 700; }
      .e     { fill: none; stroke: #38465b; stroke-width: 1.6; }
      .ed    { fill: none; stroke: #333f52; stroke-width: 1.4; stroke-dasharray: 3 5; }
      .tag   { fill: #9a7b2a; font-family: ui-monospace, "SF Mono", Menlo, Consolas, monospace; font-size: 10px; }
      .foot  { fill: #4b5563; font-family: ui-monospace, "SF Mono", Menlo, Consolas, monospace; font-size: 11px; }
    </style>

    <marker id="a" viewBox="0 0 10 10" refX="9" refY="5" markerWidth="6.5" markerHeight="6.5" orient="auto-start-reverse">
      <path d="M0,1 L9,5 L0,9 z" fill="#4c5c74"/>
    </marker>

    <filter id="g" x="-70%" y="-70%" width="240%" height="240%">
      <feGaussianBlur stdDeviation="4.5" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>

    <linearGradient id="cl" x1="0" y1="0" x2="1" y2="1">

<h2 align="center">📊 GitHub Statistics & Analysis</h2>


<h4 align="center">GitHub Contributions:</h4>
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=kawsar-codes&theme=github-compact&hide_border=true" width="95%" />
</p>

<h4 align="center">GitHub Statistics:</h4>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kawsar-codes&show_icons=true&theme=tokyonight&hide_border=true" height="180" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kawsar-codes&layout=compact&theme=tokyonight&hide_border=true" height="180" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=kawsar-codes&theme=tokyonight&hide_border=true" height="180" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=kawsar-codes&theme=tokyonight&no-frame=true&column=7" />
</p>

---
<h2 align="center">🌐 Connect With Me</h2>

<p align="center">
  <a href="https://linkedin.com/in/your-linkedin">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:mdkawsarakando@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.facebook.com/share/1DQmZXPrtk/">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" />
  </a>
  <a href="https://x.com/KawsarAkando77">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=kawsar-codes&label=Profile+Views&color=2563EB&style=flat" />
</p>

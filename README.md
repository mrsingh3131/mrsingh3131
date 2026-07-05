<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:241A3D,100:4A3A78&height=230&section=header&text=Jaskaran%20Singh&fontSize=62&fontColor=EDE7FB&fontAlignY=38&animation=fadeIn&desc=public%20data%20infrastructure%20%C2%B7%20national%20scale%20%C2%B7%20and%20I%20still%20ship%20code&descSize=17&descAlignY=60">
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:EDE7FB,100:CBBEF1&height=230&section=header&text=Jaskaran%20Singh&fontSize=62&fontColor=241A3D&fontAlignY=38&animation=fadeIn&desc=public%20data%20infrastructure%20%C2%B7%20national%20scale%20%C2%B7%20and%20I%20still%20ship%20code&descSize=17&descAlignY=60">
  <img width="100%" alt="Jaskaran Singh — building public data infrastructure at national scale" src="https://capsule-render.vercel.app/api?type=waving&color=0:241A3D,100:4A3A78&height=230&section=header&text=Jaskaran%20Singh&fontSize=62&fontColor=EDE7FB&fontAlignY=38&animation=fadeIn&desc=public%20data%20infrastructure%20%C2%B7%20national%20scale%20%C2%B7%20and%20I%20still%20ship%20code&descSize=17&descAlignY=60">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=900&color=B49BF5&center=true&vCenter=true&width=920&height=62&lines=Assistant+Director+%40+NIC+%C2%B7+MeitY%2C+Govt+of+India;I+build+India%27s+Open+Government+Data+platform;PhD+candidate+%40+IIT+Delhi+%E2%80%94+geospatial+ML;Data+pipelines+at+national+scale...+and+I+still+ship+code;Now+shipping+an+air-gapped+RAG+stack+%E2%80%94+zero+egress">
  <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=900&color=6D48D7&center=true&vCenter=true&width=920&height=62&lines=Assistant+Director+%40+NIC+%C2%B7+MeitY%2C+Govt+of+India;I+build+India%27s+Open+Government+Data+platform;PhD+candidate+%40+IIT+Delhi+%E2%80%94+geospatial+ML;Data+pipelines+at+national+scale...+and+I+still+ship+code;Now+shipping+an+air-gapped+RAG+stack+%E2%80%94+zero+egress">
  <img alt="rotating roles" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=900&color=B49BF5&center=true&vCenter=true&width=920&height=62&lines=Assistant+Director+%40+NIC+%C2%B7+MeitY%2C+Govt+of+India;I+build+India%27s+Open+Government+Data+platform;PhD+candidate+%40+IIT+Delhi+%E2%80%94+geospatial+ML;Data+pipelines+at+national+scale...+and+I+still+ship+code;Now+shipping+an+air-gapped+RAG+stack+%E2%80%94+zero+egress">
</picture>

<a href="https://karan98.in"><img alt="profile views" src="https://komarev.com/ghpvc/?username=sudo-karan&style=for-the-badge&color=6D48D7&label=DATA+STREAMS" /></a>
<img alt="open to collaboration and research" src="https://img.shields.io/badge/%E2%97%89%20open%20to-collab%20%2B%20research-6D48D7?style=for-the-badge&labelColor=241A3D" />
<img alt="location New Delhi" src="https://img.shields.io/badge/New%20Delhi-IN%20%C2%B7%20UTC%2B5%3A30-5B3DBF?style=for-the-badge&labelColor=241A3D" />

</div>

---

> I build public infrastructure — the kind that has to stay up at national scale and stay *boring* to operate. National-scale data platforms by day, air-gapped side projects by night; if a thing **can** run offline, I make it run offline. Everything below is meant to be cloned and read, not admired from a distance.

```bash
❯ whoami --verbose
┌────────────────────────────────────────────────────────────────┐
  name       Jaskaran Singh  ·  @sudo-karan
  loc        New Delhi, India  ·  UTC+05:30
  role       Assistant Director · NIC (MeitY, Govt of India)
  tenure     Mar 2022 → present  ·  4+ years, still counting
  mission    ship & scale data.gov.in — India's national OGD platform
  team       lead the build; mentor state partners onto the stack
  research   PhD · Computer Science @ IIT Delhi · geospatial ML
  stack      python · data pipelines · elasticsearch · earth-engine · cloud-native
  langs      Punjabi (native) · Hindi · English
  status     still ships code between meetings
└────────────────────────────────────────────────────────────────┘

# you landed on the profile of someone who reads logs for fun.
# every line below links to a repo you can actually clone and run.
```

<div align="center">

<img alt="4+ years at NIC" src="https://img.shields.io/badge/NIC%20%C2%B7%20Govt%20of%20India-4%2B%20years-5B3DBF?style=for-the-badge&labelColor=241A3D" />
<img alt="M.Tech CGPA 9.60" src="https://img.shields.io/badge/M.Tech%20CGPA-9.60%2F10-6D48D7?style=for-the-badge&labelColor=241A3D" />
<img alt="OGD platform national scale" src="https://img.shields.io/badge/OGD%20platform-national%20scale-5B3DBF?style=for-the-badge&labelColor=241A3D" />
<img alt="20+ projects shipped" src="https://img.shields.io/badge/shipped-20%2B%20projects-6D48D7?style=for-the-badge&labelColor=241A3D" />

</div>

---

### ▚ 01 · currently_building()

> The flagship in flight: a retrieval stack for **data.gov.in** that answers questions about India's Open Government Data policy — and **never once touches the network at runtime.** No API keys, no telemetry, no "please wait while we call a cloud." It runs in an air-gapped room or on a plane.

```yaml
# ~/rag_chatbot/deploy.manifest    →    https://github.com/sudo-karan/rag_chatbot
service:            offline-rag-for-data.gov.in
network_at_runtime: none                # air-gapped · zero egress · zero external calls
inference:          ollama              # local LLM, on-device
embeddings:         sentence-transformers
vector_store:       chromadb            # persisted, warm across restarts
api:                rest + sse          # server-sent events → tokens stream as they generate
packaging:          docker
runtime:            hardware-adaptive   # same image: laptop → 32-core box → GPU cloud, no code change
grounding:          strict              # answers ONLY from official OGD policy docs — refuses to hallucinate
status:             SHIPPING ▓▓▓▓▓▓▓▓░░
```

<div align="center">

**[▶ read the code](https://github.com/sudo-karan/rag_chatbot)** &nbsp;·&nbsp; the interesting bit is the hardware-adaptive runtime: one container decides its own batch / threads / device at boot.

</div>

---

### ▚ 02 · featured_streams[]

| project | the interesting bit (not the marketing blurb) | links |
|---------|-----------------------------------------------|-------|
| **fmu** · Forest Management Units | Fuses **Sentinel-2 optical + Sentinel-1 radar + canopy height + terrain** into an **11-stage Google Earth Engine pipeline** that delineates forest stands from open satellite data. This is the doctoral research. | [code](https://github.com/sudo-karan/phd-code) |
| **pdf-to-markdown** | The PDF never leaves the browser tab. **PDF.js** extracts images, vector diagrams *and* captions client-side — airplane mode is a valid runtime. 100% offline. | [live](https://sudo-karan.github.io/pdf-to-markdown/) · [code](https://github.com/sudo-karan/pdf-to-markdown) |
| **boyle-bingo** | The rules live in **Postgres RLS**, not the client — so nobody can cheat by editing state. Realtime voting + live leaderboard, shipped as an installable **PWA**. React / TS / Supabase. | [live](https://sudo-karan.github.io/boyle-bingo/) · [code](https://github.com/sudo-karan/boyle-bingo) |
| **claude-usage** | Dark-first Android app that surfaces your Claude usage limits via a **Glance home-screen widget** and pings you on reset. Kotlin · Compose · WorkManager. | [code](https://github.com/sudo-karan/claude-usage) |
| **goal_tracker** | Reminders that **survive a reboot** — Room-backed live countdowns + a home widget, fully offline. Kotlin. | [code](https://github.com/sudo-karan/goal_tracker) |
| **family-dashboard** | Tracks fixed deposits across banks *and* people, with maturity alerts + CSV export. Boring problem, tidy solution. | [live](https://sudo-karan.github.io/family-dashboard/) · [code](https://github.com/sudo-karan/family-dashboard) |

---

### ▚ 03 · stack.load()

<div align="center">

| layer | modules |
|:-----:|:-------:|
| `languages` | <picture><source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=python,java,kotlin,ts,js,c,cpp&theme=light"><img alt="languages" src="https://skillicons.dev/icons?i=python,java,kotlin,ts,js,c,cpp&theme=dark" /></picture> |
| `ai · ml · nlp` | <picture><source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=tensorflow,sklearn&theme=light"><img alt="ai and ml" src="https://skillicons.dev/icons?i=tensorflow,sklearn&theme=dark" /></picture> |
| `backend · cloud` | <picture><source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=docker,fastapi,elasticsearch,postgres,supabase,azure,gcp&theme=light"><img alt="backend and cloud" src="https://skillicons.dev/icons?i=docker,fastapi,elasticsearch,postgres,supabase,azure,gcp&theme=dark" /></picture> |
| `web · mobile` | <picture><source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=react,vite,androidstudio,gradle&theme=light"><img alt="web and mobile" src="https://skillicons.dev/icons?i=react,vite,androidstudio,gradle&theme=dark" /></picture> |
| `tooling` | <picture><source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=git,github,linux&theme=light"><img alt="tooling" src="https://skillicons.dev/icons?i=git,github,linux&theme=dark" /></picture> |

<sub>+ CUDA · SQL · Google Earth Engine · Drupal · microservices · offline-first · data engineering · team leadership</sub>

</div>

---

### ▚ 04 · telemetry — live data streams

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=sudo-karan&theme=react-dark&bg_color=0D1117&color=CBBEF1&line=B49BF5&point=EDE7FB&area=true&hide_border=true&radius=12">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=sudo-karan&theme=github-light&bg_color=FBFAFE&color=241A3D&line=6D48D7&point=4A3A78&area=true&hide_border=true&radius=12">
  <img width="100%" alt="contribution activity graph" src="https://github-readme-activity-graph.vercel.app/graph?username=sudo-karan&theme=react-dark&bg_color=0D1117&color=CBBEF1&line=B49BF5&point=EDE7FB&area=true&hide_border=true&radius=12">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-streak-stats.herokuapp.com/?user=sudo-karan&hide_border=true&background=0D1117&border=0D1117&stroke=4A3A78&ring=B49BF5&fire=B49BF5&currStreakNum=EDE7FB&sideNums=EDE7FB&currStreakLabel=B49BF5&sideLabels=B8ADD9&dates=8B8299">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-streak-stats.herokuapp.com/?user=sudo-karan&hide_border=true&background=FBFAFE&border=FBFAFE&stroke=CBBEF1&ring=6D48D7&fire=6D48D7&currStreakNum=241A3D&sideNums=241A3D&currStreakLabel=6D48D7&sideLabels=5B5170&dates=6E6484">
  <img alt="commit streak" src="https://github-readme-streak-stats.herokuapp.com/?user=sudo-karan&hide_border=true&background=0D1117&border=0D1117&stroke=4A3A78&ring=B49BF5&fire=B49BF5&currStreakNum=EDE7FB&sideNums=EDE7FB&currStreakLabel=B49BF5&sideLabels=B8ADD9&dates=8B8299">
</picture>

<br />

<sub>the snake below eats my contribution graph on every push — a literal data stream:</sub>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sudo-karan/sudo-karan/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sudo-karan/sudo-karan/output/github-snake.svg">
  <img width="100%" alt="contribution snake animation" src="https://raw.githubusercontent.com/sudo-karan/sudo-karan/output/github-snake-dark.svg">
</picture>

</div>

---

### ▚ 05 · career.log — git log --oneline --graph

```bash
* 2025  research   PhD · Computer Science · IIT Delhi · geospatial ML     (HEAD)
* 2022  work       Assistant Director · NIC / MeitY · scaling data.gov.in
* 2021  work       Data Scientist · McKinsey & Company · Document AI
|                    └─ shipped a layout-extraction algorithm for knowledge-extraction tooling
* 2020  intern     Data Science · Sabudh Foundation
* 2019  intern     Systems Engineer · Infosys
|                    └─ mail server from scratch: AES-256 + salted hashing + QR admin
```

```bash
$ education --degrees
2025 ──► now    PhD, Computer Science · IIT Delhi
2019 ──► 2021   M.Tech CSE · Punjab Engineering College, Chandigarh   · CGPA 9.60/10
2015 ──► 2019   B.Tech CSE · Punjabi University, Patiala              · CGPA 8.21/10
```

<details>
<summary><code>❯ cat ~/certs/*.pem &amp;&amp; ls ~/archive</code></summary>

<br>

**Certifications** &nbsp;·&nbsp; Microsoft Certified: Azure Data Fundamentals · ML with Python · Using Databases with Python · Data with Python (Honors) · Cloud Core

**Also in the archive** &nbsp;·&nbsp; **Breast Cancer Detection** — CNN over mammography + GAN augmentation (TensorFlow) · **Intelligent Help Desk** — NLP + Smart Document Understanding on IBM Watson · **CUDA Parallel Computing** — GPU-accelerated algorithms in CUDA / C

**Languages spoken** &nbsp;·&nbsp; Punjabi (native) · Hindi · English

</details>

---

### ▚ 06 · open_channel()

<div align="center">

```bash
❯ sudo make friends
[ ok ] handshake complete — socket open, say hi below
```

<a href="https://karan98.in"><img alt="portfolio karan98.in" src="https://img.shields.io/badge/karan98.in-portfolio-6D48D7?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=241A3D" /></a>
<a href="https://www.linkedin.com/in/karan98"><img alt="linkedin" src="https://img.shields.io/badge/LinkedIn-karan98-6D48D7?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=241A3D" /></a>
<a href="mailto:jaskaran.pta@gmail.com"><img alt="email" src="https://img.shields.io/badge/Email-jaskaran.pta-6D48D7?style=for-the-badge&logo=gmail&logoColor=white&labelColor=241A3D" /></a>
<a href="https://github.com/sudo-karan"><img alt="github" src="https://img.shields.io/badge/GitHub-sudo--karan-241A3D?style=for-the-badge&logo=github&logoColor=white&labelColor=241A3D" /></a>

<br /><br />

<sub><code># yes, the handle is a sudo pun. no, I won't apologize. it stays.</code></sub>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:4A3A78,50:372A5A,100:241A3D&height=150&section=footer&reversal=true&text=%24%20sudo%20karan%20--ship%20public-infrastructure&fontSize=26&fontColor=EDE7FB&animation=twinkling&descAlignY=62">
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:CBBEF1,50:DCD2F6,100:EDE7FB&height=150&section=footer&reversal=true&text=%24%20sudo%20karan%20--ship%20public-infrastructure&fontSize=26&fontColor=241A3D&animation=twinkling&descAlignY=62">
  <img width="100%" alt="footer" src="https://capsule-render.vercel.app/api?type=waving&color=0:4A3A78,50:372A5A,100:241A3D&height=150&section=footer&reversal=true&text=%24%20sudo%20karan%20--ship%20public-infrastructure&fontSize=26&fontColor=EDE7FB&animation=twinkling&descAlignY=62">
</picture>

</div>

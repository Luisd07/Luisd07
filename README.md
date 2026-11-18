<div align="center">

<img
  width="100%"
  src="https://capsule-render.vercel.app/api?type=waving&height=190&color=0:111111,100:E10600&text=Luis%20Diaz&fontColor=ffffff&fontAlign=50&fontAlignY=35&fontSize=48&desc=Live%20Broadcast%20Software%20%E2%80%A2%20Race%20Timing%20%E2%80%A2%20Miami%2C%20FL&descAlign=50&descAlignY=58&animation=fadeIn"
  alt="Luis Diaz banner"
/>

<a href="https://git.io/typing-svg">
  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=2800&pause=900&color=E10600&center=true&vCenter=true&width=800&lines=Development+Director+at+KartChaser;Building+real-time+race+timing;Software+for+live+karting+broadcasts;IT+%40+FIU%2C+Class+of+2027"
    alt="Typing intro"
  />
</a>

Development Director at **KartChaser** · IT student at **FIU** · Miami, FL

[![LinkedIn](https://img.shields.io/badge/LinkedIn-luisd07-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luisd07)

</div>

---

## 🏁 About Me

I'm the Development Director at KartChaser, where we produce live broadcasts of professional karting races. I write most of the software that runs behind the scenes, and on race weekends I'm usually at the track making sure it all holds together.

Most of my time goes into our timing system, which turns the raw feed from the track into laps, positions and results as they happen and puts them on screen. Before KartChaser, I spent three summers interning at Chevron.

## 📡 From the track to the screen

```mermaid
flowchart LR
    T["Track timing"] --> F["Trackside forwarder"]
    F --> S{{"Timing service"}}

    subgraph DATA["Race data"]
        direction TB
        RES["Results"]
        GRID["Grids"]
        PTS["Points"]
        PEN["Penalties"]
        ROS["Roster management"]
    end

    S --> DATA
    S --> G["Live graphics"]
    S -- "live triggers" --> C["Crew controls"]
    C --> G

    classDef hub fill:#E10600,stroke:#E10600,color:#ffffff,font-weight:bold
    class S hub
```

## 🛠️ What I Work With

| | |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white) |
| **Backend & Data** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) |
| **Cloud** | ![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) |
| **Hardware** | ![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white) ![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white) |

## 🏎️ Things I've Built

| | |
|---|---|
| 🎛️ [companion-module-kc-singularlive](https://github.com/Luisd07/companion-module-kc-singularlive) | Runs our broadcast graphics from Companion |
| 🎚️ [companion-module-behringer-x32-kc](https://github.com/Luisd07/companion-module-behringer-x32-kc) | X32 mixer control with live audio meters |
| 🏁 [FSAE-Dashboard](https://github.com/Luisd07/FSAE-Dashboard) | Dash display for FIU's Formula SAE car, straight off the CAN bus |
| 📋 [job-application-tracker](https://github.com/Luisd07/job-application-tracker) | Flask app for keeping a job search organized |

## 📈 Lap Chart

<img
  src="https://github-readme-activity-graph.vercel.app/graph?username=Luisd07&bg_color=0d1117&color=ffffff&line=E10600&point=ffffff&area=true&area_color=E10600&hide_border=true&custom_title=Contributions"
  width="100%"
  alt="Contribution graph"
/>

---

<p align="center">Always happy to talk racing, broadcast tech or code · <a href="https://www.linkedin.com/in/luisd07">LinkedIn</a> 🏁</p>

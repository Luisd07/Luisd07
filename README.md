<div align="center">

<img
  width="100%"
  src="https://capsule-render.vercel.app/api?type=waving&height=190&text=Luis%20Diaz&fontAlign=50&fontAlignY=35&fontSize=48&desc=Live%20Broadcast%20Software%20%E2%80%A2%20Race%20Timing%20%E2%80%A2%20Miami%2C%20FL&descAlign=50&descAlignY=58&animation=fadeIn&color=gradient"
  alt="Luis Diaz banner"
/>

<a href="https://git.io/typing-svg">
  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=2800&pause=900&center=true&vCenter=true&width=800&lines=Development+Director+at+KartChaser;Building+real-time+race+timing;Software+for+live+karting+broadcasts;IT+%40+FIU%2C+Class+of+2027"
    alt="Typing intro"
  />
</a>

<br />

[![KartChaser](https://img.shields.io/badge/KartChaser-kartchaser.com-E10600?style=for-the-badge)](https://kartchaser.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-luisd07-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luisd07)

</div>

---

## About Me

I'm the Development Director at KartChaser, where we produce live broadcasts of professional karting races. I write most of the software that runs behind the scenes, and on race weekends I'm usually at the track making sure it all holds together.

Most of my time goes into our timing system. It takes the raw timing feed from the track, turns it into laps, positions and results as they happen, and sends that out to our on-screen graphics, the website and the app. Track internet is never great, so the Raspberry Pis that carry data from the timing stand to the cloud save everything locally and catch up once the connection comes back.

I'm finishing my IT degree at Florida International University here in Miami (graduating in 2027). Before KartChaser, I spent three summers interning at Chevron, building internal apps with Power Platform, Azure and .NET MAUI.

## How a race gets on screen

```mermaid
flowchart LR
    TRACK["Timing system at the track"] --> PI["Raspberry Pi forwarder<br/>(buffers when offline)"]
    PI --> CLOUD["Timing service<br/>FastAPI + PostgreSQL"]
    CLOUD --> GFX["Live TV graphics<br/>Singular.live"]
    CLOUD --> WEB["KartChaser website and app"]
    CREW["Production crew<br/>Companion + Stream Deck"] --> GFX
```

---

## What I'm Working On

- Real-time race timing and results for live TV graphics
- Trackside hardware that keeps working when the internet doesn't
- Custom Bitfocus Companion modules for our audio mixers and Singular.live graphics
- Automating the boring parts of broadcast day so the crew can focus on the race

## Tools I Reach For

<div align="center">

<img
  src="https://skillicons.dev/icons?i=python,fastapi,postgres,ts,js,nodejs,react,java,cs,docker,gcp,azure,raspberrypi,arduino,git,linux&perline=8"
  alt="Languages and tools"
/>

</div>

## A Few Things I've Made

- [companion-module-kc-singularlive](https://github.com/Luisd07/companion-module-kc-singularlive): runs our broadcast graphics from Companion, up to 8 Singular.live apps at once
- [companion-module-behringer-x32-kc](https://github.com/Luisd07/companion-module-behringer-x32-kc): our take on the X32 module, with live audio meters and show presets for our mics
- [FSAE-Dashboard](https://github.com/Luisd07/FSAE-Dashboard): the dash display for my university's Formula SAE car, reading straight off the car's CAN bus
- [job-application-tracker](https://github.com/Luisd07/job-application-tracker): a Flask app I built to keep my own job search organized

## Activity

<div align="center">

<img
  src="https://streak-stats.demolab.com?user=Luisd07&theme=github-dark-blue&hide_border=true"
  width="49%"
  alt="GitHub contribution streak"
/>
<img
  src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Luisd07&theme=github_dark"
  width="49%"
  alt="Repositories by language"
/>

<img
  src="https://github-readme-activity-graph.vercel.app/graph?username=Luisd07&theme=github-compact&hide_border=true&area=true&custom_title=Contribution%20Activity"
  width="100%"
  alt="Contribution activity graph"
/>

</div>

---

## Contact

I'm always happy to talk racing, broadcast tech or software.

- LinkedIn: [luisd07](https://www.linkedin.com/in/luisd07)
- GitHub: [@Luisd07](https://github.com/Luisd07)
- KartChaser: [kartchaser.com](https://kartchaser.com)

<img
  width="100%"
  src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=gradient"
  alt="Footer"
/>

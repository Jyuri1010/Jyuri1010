<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=32&pause=1000&color=F4A7B9&center=true&vCenter=true&width=800&lines=%F0%9F%91%8B+Hello%2C+I'm+Jyuri+Kalaria+%F0%9F%8C%B8!"
    alt="Animated introduction"
  />
</p>

<p align="center">
  🎓 CSE Student &nbsp;•&nbsp; 🤖 Exploring AI &nbsp;•&nbsp; 💻 Learning C, C++, HTML & CSS
  <br/>
  🔌 Future Arduino Explorer &nbsp;•&nbsp; 🏆 Open to Hackathons and Collaboration
</p>

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=F4A7B9&center=true&vCenter=true&width=1000&lines=Welcome+to+my+little+corner+of+GitHub+%E2%80%94+where+curiosity+turns+into+projects!"
    alt="Welcome message"
  />
</p>

![2026 Goals](https://capsule-render.vercel.app/api?type=waving&color=F4A7B9&height=140&section=header&text=2026%20Goals&fontSize=42&fontColor=FFFFFF&animation=fadeIn)

- 🧱 Building my programming foundations  
- 🤖 Exploring AI and its real-world applications  
- 🌐 Learning web development  
- 🚀 Preparing to create projects and participate in hackathons




![Contribution Goals](https://capsule-render.vercel.app/api?type=waving&color=F4A7B9&height=140&section=header&text=Contribution%20Goals&fontSize=38&fontColor=FFFFFF&animation=fadeIn)

- 📚 Learn something new and share my progress
- 💻 Build beginner-friendly C, C++, and web projects
- 🤝 Collaborate in hackathons and open-source projects
- 🤖 Explore AI through small practical projects
- 🔌 Create Arduino-based hardware projects


## 🛠️ Currently Learning

<p align="center">
  <img src="https://skillicons.dev/icons?i=c,cpp,html,css&theme=light" height="58" />
</p>


## 🛠️ Tools & Technologies

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" width="55" alt="C" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="55" alt="C++" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="55" alt="HTML5" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="55" alt="CSS3" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/arduino/arduino-original.svg" width="55" alt="Arduino" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="55" alt="Git" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="55" alt="GitHub" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="55" alt="VS Code" />
</p>


<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Jyuri1010&color=blueviolet&style=flat-square" alt="Profile Views" />
</p>


## 📈 My GitHub Contributions

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jyuri1010&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>


## 📈 My Contribution Graph

import { useState } from "react";
import "./ContributionGraph.css";

const months = ["Jan", "Feb", "Mar", "Apr", "May", "Jun",
                "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"];

export default function ContributionGraph() {
  const [days] = useState(() =>
    Array.from({ length: 365 }, (_, i) => ({
      id: i,
      level: Math.random() < 0.6 ? 0 : Math.ceil(Math.random() * 4),
    }))
  );

  return (
    <section className="contribution-card">
      <h2>My GitHub contributions</h2>

      <div className="month-labels">
        {months.map((month) => <span key={month}>{month}</span>)}
      </div>

      <div className="contribution-grid">
        {days.map((day) => (
          <div
            key={day.id}
            className={`contribution-day level-${day.level}`}
            title={`${day.level} contributions`}
          />
        ))}
      </div>

      <div className="graph-legend">
        <span>Less</span>
        {[0, 1, 2, 3, 4].map((level) => (
          <span key={level} className={`contribution-day level-${level}`} />
        ))}
        <span>More</span>
      </div>
    </section>
  );
}
## 💡 Fun Facts

- ☕ I enjoy turning ideas into projects
- 🧩 I love learning through hands-on experiments
- 🚀 Always curious about new technology

## 📬 Let’s Connect

> 🌸 Feel free to reach out for hackathons, project ideas, or collaboration!

<p align="center">
  <a href="mailto:jyurikalaria1010@gmail.com">
    <img src="https://img.shields.io/badge/Email-F9A8D4?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://linkedin.com/in/Jyuri K Kalaria">
    <img src="https://img.shields.io/badge/LinkedIn-A6C1EE?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>


## 💌 A Tiny Note

<details>
  <summary>Click here for a message 🌸</summary>

  Thank you for visiting my profile!  
  I’m learning, experimenting, and growing one commit at a time. ✨
</details>

<p align="center">
  <i>✨ Learning today, building tomorrow. ✨</i>
</p>

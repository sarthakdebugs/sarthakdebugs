<!-- ═══════════════════════════════════════════════════════════ -->
<!--              SARTHAK DUBEY — GitHub Profile README         -->
<!-- ═══════════════════════════════════════════════════════════ -->

<!-- ░░░ ANIMATED HEADER BANNER ░░░ -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:8B5CF6,100:3B0764&height=220&section=header&text=Sarthak%20Dubey&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=37&desc=AI%20%26%20Data%20Science%20Engineer%20%7C%20Builder%20%7C%20Problem%20Solver&descAlignY=57&descSize=19&descColor=DDD6FE" />
</div>

<!-- ░░░ ANIMATED TYPING TEXT ░░░ -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=2800&pause=1000&color=A78BFA&center=true&vCenter=true&width=640&height=52&lines=Building+RAG+Systems+%26+LLM+Pipelines...;Python+%7C+Java+Developer;Oracle+%26+Cisco+Certified+Engineer;B.Tech+AI+%26+DS+%40+LNCT+Bhopal+(CGPA%3A+8.0);Campus+Placement+Ready!" alt="Typing SVG" />
</p>

<!-- ░░░ BADGE ROW ░░░ -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sarthakdebugs&style=for-the-badge&color=7c3aed&label=PROFILE+VIEWS" alt="Profile views"/>
  &nbsp;
  <img src="https://img.shields.io/github/followers/sarthakdebugs?label=Followers&style=for-the-badge&color=6d28d9&labelColor=1e1b4b" alt="GitHub Followers"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Focus-AI%20%26%20ML-blueviolet?style=for-the-badge&logo=openai&logoColor=white" />
  &nbsp;
  <img src="https://img.shields.io/badge/Open%20To-Internships%20%26%20Placements-success?style=for-the-badge&logo=handshake&logoColor=white" />
</p>

<br/>

---

## 👨‍💻 &nbsp; About Me

```python
class SarthakDubey:
    def __init__(self):
        self.name        = "Sarthak Dubey"
        self.role        = "AI & Data Science Engineer"
        self.location    = "Bhopal, Madhya Pradesh, India 🇮🇳"
        self.education   = "B.Tech AI & DS @ LNCT Bhopal  |  CGPA: 8.0 / 10"
        self.email       = "sarthakdubey1010@gmail.com"
        self.linkedin    = "linkedin.com/in/sarthak-dubey"   # <-- update with your URL
        self.github      = "github.com/sarthakdebugs"

    @property
    def skills(self):
        return {
            "languages"  : ["Python 🐍", "Java ☕"],
            "ml_ai"      : ["Scikit-Learn", "OpenCV", "FAISS", "Whisper",
                            "LLMs", "RAG Systems", "SentenceTransformers"],
            "cloud_db"   : ["Oracle Cloud Infrastructure", "Salesforce", "SQL"],
            "tools"      : ["Git", "GitHub", "Pandas", "NumPy", "Matplotlib"],
        }

me = SarthakDubey()
print(f"Hi, I'm {me.name} — let's build something impactful! 🚀")
```

---

## 🛠️ &nbsp; Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,java,sklearn,opencv,git,github,linux,vscode&perline=8" />
</p>

<br/>

<div align="center">

**Languages**&emsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**AI / ML**&emsp;
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square&logo=python&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper-412991?style=flat-square&logo=openai&logoColor=white)

**Cloud & DB**&emsp;
![Oracle](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=flat-square&logo=salesforce&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Tools**&emsp;
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)

</div>

---

## 🚀 &nbsp; Featured Project

<table>
<tr>
<td width="100%" valign="top">

### 🤖 RAG-Based AI Teaching Assistant
> *Turns long educational videos into a searchable, hallucination-free AI tutor.*

| Component | Implementation |
|:---|:---|
| 🎬 **Video Pipeline** | MP4 → MP3 → Text transcription via **OpenAI Whisper** |
| 🧠 **Embeddings** | **bge-m3 / SentenceTransformers** → stored in **FAISS** vector DB |
| 🔍 **Query Engine** | Semantic retrieval with exact **timestamp** references |
| 🛡️ **Accuracy** | Hallucination-free answers grounded in indexed video content |
| ⚙️ **Deployment** | Batch video ingestion · Local **CPU / GPU** · JSON structured output |

**Stack:** &nbsp;`Python` &nbsp;`Whisper` &nbsp;`FAISS` &nbsp;`LLMs` &nbsp;`SentenceTransformers` &nbsp;`JSON`

</td>
</tr>
</table>

---

## 💼 &nbsp; Experience

```
🏢  Cisco Systems  |  Virtual Intern
    ├── Duration  :  June 2025 – August 2025
    ├── Focus     :  Networking Fundamentals & Cybersecurity Principles
    ├── Exposure  :  Enterprise-level Technology Solutions
    └── Outcome   :  Industry Best Practices · Cisco Networking Academy Certified
```

---

## 📜 &nbsp; Certifications

<div align="center">

| &nbsp; | Certification | Issuer | Year |
|:---:|:---|:---|:---:|
| ☕ | **Programming using Java** | Infosys Springboard | 2025 |
| 🔐 | **Cyber Security Fundamentals** | Infosys Springboard | 2025 |
| 🌐 | **Cybersecurity Virtual Internship Program** | Cisco Networking Academy · AICTE | 2025 |
| 💡 | **GfG 160 – 160 Days of Problem Solving** | GeeksforGeeks | 2025 |
| ☁️ | **Oracle Cloud Infrastructure AI Foundations Associate** | Oracle *(Valid till Aug 2027)* | 2025 |

</div>

---

## 📈 &nbsp; Contribution Activity

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=sarthakdebugs&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=A78BFA&line=7C3AED&point=DDD6FE&area=true&area_color=3B0764" alt="Contribution Graph" />
</div>

---

## 🤝 &nbsp; Let's Connect

<p align="center">
  <a href="mailto:sarthakdubey1010@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/sarthak-dubey">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://github.com/sarthakdebugs">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://auth.geeksforgeeks.org/user/sarthakdubey">
    <img src="https://img.shields.io/badge/GeeksforGeeks-0F9D58?style=for-the-badge&logo=geeksforgeeks&logoColor=white" />
  </a>
</p>

---

<!-- ░░░ MOTIVATIONAL QUOTE ░░░ -->
<div align="center">
<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:3B0764,100:1e1b4b&height=2&section=header&reversal=false" width="80%"/>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/-%22The%20best%20way%20to%20predict%20the%20future%20is%20to%20create%20it.%22-3B0764?style=for-the-badge&labelColor=0D1117&color=3B0764&logo=data:image/svg%2bxml;base64,"/>
</picture>

> ### *"Code is not just instructions for machines — it is the language in which we sculpt the future."*
>
> — **Sarthak Dubey** &nbsp;|&nbsp; AI & Data Science Engineer &nbsp;🇮🇳

<br/>

![Wave](https://img.shields.io/badge/Thanks%20for%20visiting!-7C3AED?style=for-the-badge&logo=github&logoColor=white)
&nbsp;
![Star](https://img.shields.io/badge/Drop%20a%20⭐%20if%20you%20like%20my%20work!-1e1b4b?style=for-the-badge&logo=github&logoColor=white)

<br/>

</div>

<!-- ░░░ ANIMATED FOOTER ░░░ -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:3B0764,100:8B5CF6&height=140&section=footer&animation=fadeIn" />
</div>

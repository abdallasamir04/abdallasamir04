from pathlib import Path

content = r'''<p align="center"> 
  <img 
    src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&duration=2200&pause=1100&color=00C6FF&width=680&center=true&vCenter=true&repeat=true&lines=👋+Hi,+I'm+Abdalla+Samir;🚀+Software+Engineering+Student;💻+Backend+%26+.NET+Developer;🌍+Enterprise+Architecture+Enthusiast" 
    alt="Typing introduction" 
  /> 
</p> 
 
--- 
 
<div align="center"> 
  <b>Software Engineering student at Assiut University</b> passionate about building <b>scalable backend systems, clean architecture, and enterprise-grade web applications.</b> 
</div> 
 
--- 
 
## 🛠 Featured Projects 
 
### 🎓 **Darabny Platform — Enterprise Mentorship SaaS (Graduation Project)** 
An enterprise-grade platform engineered to bridge the gap between academic education and industry requirements. It connects students with corporate mentors through real-world micro-tasks, utilizing a smart matching algorithm and a double-blind evaluation engine to issue immutable Experience Tokens. 
 
**Tech Stack:**   
`.NET 9` · `ASP.NET Core MVC` · `Entity Framework Core` · `SQL Server` · `Clean N-Tier Architecture` · `AJAX/JS` · `Bootstrap 5` 
 
**Key Features:** 
- 🧠 **AI-Powered Smart Matching:** Cross-references student CVs with task specializations. 
- ⚖️ **Double-Blind Evaluation & Tokens:** Cryptographically verifiable PDF certificates. 
- 🛡️ **Enterprise Security & Governance:** Role-Based Access Control (RBAC) & Database Transactions. 
- 📊 **Dynamic Analytics:** Real-time dashboards with `Chart.js` & AJAX notification polling. 
 
--- 
 
### 🛍 **Electro E-Commerce Platform** 
A robust full-stack e-commerce system designed for selling electronic products, focusing on performance, secure checkout workflows, and relational database integrity. 
 
**Tech Stack:**   
`.NET` · `C#` · `SQL Server` · `LINQ` · `jQuery` · `Bootstrap` 
 
<p align="center"> 
  <strong style="font-size:16px; color:#ff9900;">🏆 🥉 THIRD PLACE — DEPI Full Stack .NET Graduation Projects</strong> 
</p> 
 
--- 
 
### 🖥 **Mini-FAT File System (OS Project)** 
A custom FAT-like file system simulation built from scratch to deeply understand low-level storage mechanics, virtual disk creation, and file allocation tracking. 
 
**Tech Stack:** `C#` · `.NET Core` 
 
--- 
 
### 📝 **Samir List — Task Management Web App** 
A lightweight, fast, and responsive task management web application for organizing daily work with active & completed task views. 
 
**Tech Stack:** `Python` · `Flask` · `SQLAlchemy` · `SQLite` 
 
--- 
 
### 📐 **Core Computer Science Projects** 
- **Geometric Object Calculator:** `Java` `Swing` (OOP, Inheritance, Polymorphism). 
- **Terminal To-Do List:** `C++` (Data Structures, Linked Lists, Dynamic Memory Management). 
 
--- 
 
## 💡 Tech Stack & Tools 
 
<!-- Languages & Frameworks --> 
<p align="center"> 
  <img 
    src="https://skillicons.dev/icons?i=cs,dotnet,cpp,c,java,python,flask,html,css,js,bootstrap&perline=11" 
    alt="Languages and frameworks" 
  /> 
</p> 
 
<!-- Databases & Tools --> 
<p align="center"> 
  <img 
    src="https://skillicons.dev/icons?i=mssql,mysql,postgres,sqlite,git,github,vscode,visualstudio,pycharm,idea,figma&perline=11" 
    alt="Databases and tools" 
  /> 
</p> 
 
--- 
 
## 📊 GitHub Analytics 
 
<p align="center"> 
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=abdallasamir04&show_icons=true&theme=radical&hide_border=true&include_all_commits=true" height="165" alt="GitHub Stats" /> 
  <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=abdallasamir04&layout=compact&theme=radical&hide_border=true&langs_count=8&exclude_repo=github-readme-stats" height="165" alt="Top Languages" /> 
</p> 
 
<p align="center"> 
  <img  
    src="https://github-readme-activity-graph.vercel.app/graph?username=abdallasamir04&theme=react-dark&area=true&hide_border=true"  
    width="845" 
    alt="Contribution Graph"  
  /> 
</p> 
 
--- 
 
## 🐍 Contribution Activity 
 
<p align="center"> 
  <img 
    src="https://raw.githubusercontent.com/abdallasamir04/abdallasamir04/output/snake.svg" 
    alt="GitHub contribution snake" 
  /> 
</p> 
 
--- 
 
## 🌐 Let's Connect 
 
<table align="center"> 
  <tr> 
    <td align="center"> 
      <a href="https://www.linkedin.com/in/abdalla-samir-9264242b6"> 
        <img src="https://img.icons8.com/fluency/48/linkedin-circled.png" width="40" alt="LinkedIn" /> 
      </a> 
    </td> 
    <td align="center"> 
      <a href="mailto:samirovic707@gmail.com"> 
        <img src="https://img.icons8.com/fluency/48/gmail-new.png" width="40" alt="Email" /> 
      </a> 
    </td> 
    <td align="center"> 
      <a href="https://discord.com/users/jupyter_notebook"> 
        <img src="https://img.icons8.com/fluency/48/discord-logo.png" width="40" alt="Discord" /> 
      </a> 
    </td> 
  </tr> 
</table> 
 
--- 
 
<div align="center"> 
  <b>Profile Views</b><br> 
  <img src="https://komarev.com/ghpvc/?username=abdallasamir04&color=blueviolet" alt="Profile Views" />   
</div>
'''

path = "/mnt/data/README.md"
Path(path).write_text(content, encoding="utf-8")
print(path)

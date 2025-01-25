<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Abdalla Samir - Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #1e1e1e;
      color: #ffffff;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .container {
      text-align: center;
    }

    h1 {
      font-size: 3rem;
      margin: 0;
      opacity: 0;
      animation: fadeIn 2s forwards;
    }

    h2 {
      font-size: 1.5rem;
      margin: 10px 0 0;
      opacity: 0;
      animation: fadeIn 2s forwards 1s; /* Delay of 1s */
    }

    .contrast-toggle {
      margin-top: 20px;
    }

    .contrast-toggle button {
      background-color: #007bff;
      color: white;
      border: none;
      padding: 10px 20px;
      font-size: 1rem;
      cursor: pointer;
      border-radius: 5px;
      transition: background-color 0.3s;
    }

    .contrast-toggle button:hover {
      background-color: #0056b3;
    }

    /* High contrast mode */
    .high-contrast {
      background-color: #000000;
      color: #ffffff;
    }

    /* Animations */
    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes fadeOut {
      from {
        opacity: 1;
        transform: translateY(0);
      }
      to {
        opacity: 0;
        transform: translateY(-20px);
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1 id="greeting">👋 Hi, I'm Abdalla Samir</h1>
    <h2 id="tagline">🚀 Software Engineering Student | Passionate Developer | Tech Enthusiast</h2>
    <div class="contrast-toggle">
      <button onclick="toggleContrast()">Toggle High Contrast</button>
    </div>
  </div>

  <script>
    // Function to toggle high contrast mode
    function toggleContrast() {
      document.body.classList.toggle('high-contrast');
    }

    // Optional: Add a fade-out effect after a delay
    setTimeout(() => {
      document.getElementById('greeting').style.animation = 'fadeOut 2s forwards';
      document.getElementById('tagline').style.animation = 'fadeOut 2s forwards';
    }, 10000); // Fades out after 10 seconds
  </script>
</body>
</html>

Welcome to my GitHub profile! I'm a **Software Engineering** student at **Assiut University**, specializing in **Software Engineering** at the **Faculty of Computer Science & Artificial Intelligence (FCAI)**. I'm passionate about coding, building innovative solutions, and contributing to the tech community. Let's create something amazing together! 💻✨

---

## 🌟 About Me

- 🎓 **Software Engineering Student** at **Assiut University**.
- 💻 Passionate about **coding**, **problem-solving**, and **building real-world applications**.
- 🌱 Constantly learning and growing as a developer.
- 🚀 Driven by curiosity and a desire to make an impact through technology.

---

## 🛠️ Projects I'm Working On

Here are some of the exciting projects I'm currently working on:

### 📚 **ATLAS Project**
- **Description**: Developing an **Automated Tracking and Logging Attendance System** using **NFC technology** for efficient attendance management.
- **Tech Stack**: C#, .NET, NFC, Database Management.

### 🚎 **Transportation App**
- **Description**: Designing an app to help users find the **best transportation options**, **costs**, and **schedules**.
- **Tech Stack**: Java, Android Studio, Firebase.

### 💾 **Operating Systems Project**
- **Description**: Creating a **Virtual Disk**, **Directory Structure**, and a **Mini FAT** for a file system.
- **Tech Stack**: C#, File System Design, Data Structures.

### 🌐 **Networking Challenges**
- **Description**: Solving questions from **Computer Networking: A Top-Down Approach** to sharpen my networking skills.
- **Tech Stack**: Networking Protocols, Python, Wireshark.

---

## 💡 Skills & Expertise

### Programming Languages
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

### Tools & Frameworks
![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)

### Databases
![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

---

## 🎯 Goals

- 🌟 Master advanced concepts in **Software Engineering** and **Networking**.
- 🔧 Build **impactful, real-world applications** that solve real problems.
- 🤝 Collaborate with amazing developers on **exciting projects**.
- 📚 Continuously learn and grow as a developer.

---

## 🧠 My Coding Philosophy

- 📖 **"Code is like humor. When you have to explain it, it’s bad."**
- 💡 **Learning through practice**: Solving problems and building real-world projects.
- 💻 **Clean and efficient code** is always the goal!

---

## 🌐 Socials

Let's connect! Feel free to reach out or follow me on these platforms:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/abdalla-mahmoud-9264242b6)
[![X (Twitter)](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/abdallasamir04)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)](https://github.com/abdallasamir04)

---

## 📊 GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=abdallasamir04&theme=dark&hide_border=false&include_all_commits=false&count_private=false)
![](https://github-readme-streak-stats.herokuapp.com/?user=abdallasamir04&theme=dark&hide_border=false)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=abdallasamir04&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---

## 🏆 GitHub Trophies

![](https://github-profile-trophy.vercel.app/?username=abdallasamir04&theme=radical&no-frame=false&no-bg=true&margin-w=4)

---

## ✨ Let’s Collaborate!

Feel free to explore my repositories, fork projects, or reach out for collaboration!  
**Let’s debug life, one line of code at a time.** 🧑‍💻🔥

---

[![](https://visitcount.itsvg.in/api?id=abdallasamir04&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->

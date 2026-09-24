# 👋 Hi, I'm Shivam Kumar Singh

Software Engineer | AI/ML | Full-Stack | System Design

## 🐍 Animated Snake

<div align="center">
  <svg width="700" height="150" viewBox="0 0 700 150" xmlns="http://www.w3.org/2000/svg">
    <style>
      .snake-segment { transition: all 0.3s ease; }
      .snake-head { fill: #39d353; }
      .snake-body { fill: #26a641; }
      .snake-tail { fill: #0e4429; }
      .food { fill: #ff6b6b; animation: pulse 1s infinite; }
      @keyframes pulse { 0%, 100% { transform: scale(1); } 50% { transform: scale(1.2); } }

      /* Snake movement animation */
      @keyframes moveRight { 0% { transform: translateX(0); } 100% { transform: translateX(620px); } }
      @keyframes moveDown { 0% { transform: translateY(0); } 100% { transform: translateY(130px); } }
      @keyframes moveLeft { 0% { transform: translateX(620px); } 100% { transform: translateX(0); } }
      @keyframes moveUp { 0% { transform: translateY(130px); } 100% { transform: translateY(0); } }

      .snake-group {
        animation: moveRight 4s linear, moveDown 4s linear 4s, moveLeft 4s linear 8s, moveUp 4s linear 12s;
        animation-iteration-count: infinite;
      }
    </style>

    <!-- Snake Group with Animation -->
    <g class="snake-group">
      <rect class="snake-segment snake-head" x="0" y="60" width="18" height="18" rx="3"/>
      <rect class="snake-segment snake-body" x="20" y="60" width="18" height="18" rx="3"/>
      <rect class="snake-segment snake-body" x="40" y="60" width="18" height="18" rx="3"/>
      <rect class="snake-segment snake-body" x="60" y="60" width="18" height="18" rx="3"/>
      <rect class="snake-segment snake-body" x="80" y="60" width="18" height="18" rx="3"/>
      <rect class="snake-segment snake-tail" x="100" y="60" width="18" height="18" rx="3"/>
      <rect class="snake-segment snake-tail" x="120" y="60" width="18" height="18" rx="3"/>
    </g>

    <!-- Multiple food items that appear and disappear -->
    <circle class="food" cx="180" cy="69" r="8"/>
    <circle class="food" cx="350" cy="69" r="8" style="animation-delay: 2s"/>
    <circle class="food" cx="520" cy="69" r="8" style="animation-delay: 4s"/>
    <circle class="food" cx="520" cy="129" r="8" style="animation-delay: 6s"/>
    <circle class="food" cx="350" cy="129" r="8" style="animation-delay: 8s"/>
    <circle class="food" cx="180" cy="129" r="8" style="animation-delay: 10s"/>
    <circle class="food" cx="180" cy="9" r="8" style="animation-delay: 12s"/>
    <circle class="food" cx="350" cy="9" r="8" style="animation-delay: 14s"/>
  </svg>
</div>

## 🚀 About Me

I'm a passionate software engineer with expertise in AI/ML, Full-Stack development, and System Design. I love building innovative solutions and exploring cutting-edge technologies.

- 🎓 **IIT Dharwad** - Computer Science & Engineering
- 💼 **Software Engineer** - Specializing in AI/ML and Full-Stack Development
- 🌱 **Continuous Learner** - Always exploring new technologies
- 💡 **Problem Solver** - Enjoy tackling complex challenges

## 🛠️ Tech Stack

### Languages
- **Python** - AI/ML, Backend Development
- **TypeScript/JavaScript** - Frontend Development
- **SQL** - Database Management
- **PL/pgSQL** - PostgreSQL

### Frameworks & Libraries
- **React/Next.js** - Frontend Frameworks
- **Node.js** - Backend Runtime
- **TensorFlow/PyTorch** - Machine Learning
- **Express.js** - Web Framework

### Tools & Platforms
- **Git/GitHub** - Version Control
- **Docker** - Containerization
- **AWS/Cloud** - Cloud Services
- **PostgreSQL** - Database

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=sivammarwar&show_icons=true&theme=dark)

## 🏆 Achievements

- 🌟 **1,348+ contributions** in the last year
- 📁 **31+ public repositories** on GitHub
- 🎯 **Diverse project portfolio** spanning multiple domains

## 🔗 Connect With Me

- **LinkedIn** - [in/shivam-kumar-singh-22964b294](https://www.linkedin.com/in/shivam-kumar-singh-22964b294)
- **GitHub** - [@sivammarwar](https://github.com/sivammarwar)

## 📈 Featured Projects

### [Allora](https://github.com/sivammarwar/Allora)
*TypeScript • AI/ML*
Updated 30 minutes ago

### [GAIA](https://github.com/sivammarwar/GAIA)
*HTML • AI*
Updated 3 weeks ago

### [cyberthistle](https://github.com/sivammarwar/cyberthistle)
*TypeScript • Security*
Updated 3 weeks ago

---

Made with ❤️ and 🐍 by [sivammarwar](https://github.com/sivammarwar)
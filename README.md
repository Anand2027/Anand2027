<h1 align="center">
  Hi 👋, I'm Anand Swaroop Gupta
</h1>

<h3 align="center">
  <span class="typed-text"></span><span class="cursor">&nbsp;</span>
</h3>

<table align="center" width="100%" style="max-width: 900px;">
  <tr>
    <td width="50%" valign="middle" style="padding-right: 20px;">
      <p>
        🔭 I’m currently working on <b>full-stack web apps using React + Node.js</b><br/>
        🌱 I’m currently learning <b>TypeScript, Next.js, and AI integration</b><br/>
        👯 I’m looking to collaborate on <b>frontend-heavy or AI-enhanced web projects</b><br/>
        💬 Ask me about <b>React, Tailwind CSS, Express, MongoDB, APIs</b><br/>
        📫 Reach me via: <a href="https://portfolio-anand-swaroop-guptas-projects.vercel.app/" target="_main" rel="noopener noreferrer">My Portfolio</a><br/>
        ⚡ Fun fact: I love clean UI and coffee ☕ while coding!
      </p>
    </td>
    <td width="50%" align="center" valign="middle">
      <img alt="Developer working" src="https://cdn.dribbble.com/users/199817/screenshots/5517362/media/072559a4706a38ab93fdb74d22029e6f.gif" width="350" style="border-radius: 15px;" />
    </td>
  </tr>
</table>

---

### 🛠️ Tools & Technologies

<p align="center">
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="TailwindCSS" src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img alt="Express.js" src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" />
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img alt="VS Code" src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
</p>

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AnandGuptaDev&show_icons=true&theme=tokyonight" alt="GitHub Stats" />
  <br />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AnandGuptaDev&theme=tokyonight" alt="GitHub Streak" />
</p>

---

### 🔗 Connect with me:

<p align="center">
  <a href="https://www.linkedin.com/in/anand-swaroop-gupta-42b72623b" target="_main" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="mailto:anandgupta020204@gmail.com" target="_main" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Gmail-red?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  &nbsp;
  <a href="https://portfolio-anand-swaroop-guptas-projects.vercel.app/" target="_main" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Portfolio-grey?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
</p>

---

<!-- CSS typing animation (works on GitHub) -->
<style>
  .typed-text {
    font-family: 'Courier New', Courier, monospace;
    white-space: nowrap;
    overflow: hidden;
    border-right: 3px solid #61dafb;
    animation: typing 4s steps(40, end) infinite alternate, blink 0.7s step-end infinite;
  }

  @keyframes typing {
    from { width: 0 }
    to { width: 100% }
  }

  @keyframes blink {
    50% { border-color: transparent }
  }

  .cursor {
    animation: blink 0.7s step-end infinite;
  }
</style>

<script>
  const phrases = [
    "A passionate Frontend-first Full Stack Developer from India",
    "React & Tailwind CSS enthusiast",
    "AI & Next.js learner",
    "Clean UI lover ☕"
  ];

  let currentPhraseIndex = 0;
  let currentText = '';
  let isDeleting = false;
  const typedTextSpan = document.querySelector('.typed-text');

  function type() {
    if (!typedTextSpan) return;

    const fullText = phrases[currentPhraseIndex];

    if (isDeleting) {
      currentText = fullText.substring(0, currentText.length - 1);
    } else {
      currentText = fullText.substring(0, currentText.length + 1);
    }

    typedTextSpan.textContent = currentText;

    let delay = isDeleting ? 100 : 150;

    if (!isDeleting && currentText === fullText) {
      delay = 2000;
      isDeleting = true;
    } else if (isDeleting && currentText === '') {
      isDeleting = false;
      currentPhraseIndex = (currentPhraseIndex + 1) % phrases.length;
      delay = 500;
    }

    setTimeout(type, delay);
  }

  document.addEventListener('DOMContentLoaded', () => {
    type();
  });
</script>


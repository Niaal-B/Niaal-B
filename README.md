<!DOCTYPE html>
<html>
<head>
  <style>
    .format-selector {
      display: flex;
      justify-content: center;
      gap: 10px;
      margin: 20px 0;
    }
    .format-btn {
      padding: 8px 16px;
      border: 2px solid #4B8BBE;
      background: transparent;
      color: #4B8BBE;
      border-radius: 4px;
      cursor: pointer;
      transition: all 0.3s;
    }
    .format-btn.active {
      background: #4B8BBE;
      color: white;
    }
    .format-content {
      display: none;
    }
    .format-content.active {
      display: block;
    }
    .center {
      text-align: center;
    }
  </style>
</head>
<body>

<div class="format-selector">
  <button class="format-btn active" onclick="switchFormat('json')">JSON</button>
  <button class="format-btn" onclick="switchFormat('xml')">XML</button>
  <button class="format-btn" onclick="switchFormat('html')">HTML</button>
</div>

<!-- JSON Format -->
<div id="json-format" class="format-content active">
  <h1>{ "dev": "Nihal" }</h1>
  
  <div class="center">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=4B8BBE&center=true&vCenter=true&width=600&lines=Python+Enthusiast" alt="Typing SVG" />
  </div>

  ```json
  {
    "about": {
      "description": "A passionate developer with a love for creating efficient and scalable solutions",
      "motivation": "Journey in tech driven by curiosity and a constant desire to learn and grow"
    },
    "tech_arsenal": {
      "frontend": ["React", "JavaScript", "HTML", "CSS"],
      "backend": ["Python", "Django", "FastAPI", "PostgreSQL"],
      "devops": ["Kubernetes", "Docker", "Git", "Linux"]
    },
    "quick_facts": {
      "primary_language": "Python",
      "current_focus": "Advanced FastAPI techniques",
      "passion": "Building scalable backend solutions",
      "approach": "Always learning and experimenting"
    }
  }
  ```
</div>

<!-- XML Format -->
<div id="xml-format" class="format-content">
  <h1>&lt;developer&gt;Nihal&lt;/developer&gt;</h1>

  <div class="center">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=4B8BBE&center=true&vCenter=true&width=600&lines=Python+Enthusiast" alt="Typing SVG" />
  </div>

  ```xml
  <?xml version="1.0" encoding="UTF-8"?>
  <profile>
    <about>
      <description>A passionate developer with a love for creating efficient and scalable solutions</description>
      <motivation>Journey in tech driven by curiosity and a constant desire to learn and grow</motivation>
    </about>
    <techArsenal>
      <frontend>
        <skill>React</skill>
        <skill>JavaScript</skill>
        <skill>HTML</skill>
        <skill>CSS</skill>
      </frontend>
      <backend>
        <skill>Python</skill>
        <skill>Django</skill>
        <skill>FastAPI</skill>
        <skill>PostgreSQL</skill>
      </backend>
      <devops>
        <skill>Kubernetes</skill>
        <skill>Docker</skill>
        <skill>Git</skill>
        <skill>Linux</skill>
      </devops>
    </techArsenal>
    <quickFacts>
      <primaryLanguage>Python</primaryLanguage>
      <currentFocus>Advanced FastAPI techniques</currentFocus>
      <passion>Building scalable backend solutions</passion>
      <approach>Always learning and experimenting</approach>
    </quickFacts>
  </profile>
  ```
</div>

<!-- HTML Format -->
<div id="html-format" class="format-content">
  <h1>&lt;h1&gt;Nihal&lt;/h1&gt;</h1>

  <div class="center">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=4B8BBE&center=true&vCenter=true&width=600&lines=Python+Enthusiast" alt="Typing SVG" />
  </div>

  ```html
  <!DOCTYPE html>
  <html>
  <head>
    <title>Nihal - Developer Profile</title>
  </head>
  <body>
    <header>
      <h1>About Me</h1>
      <p>A passionate developer with a love for creating efficient and scalable solutions</p>
      <p>Journey in tech driven by curiosity and a constant desire to learn and grow</p>
    </header>

    <section class="tech-arsenal">
      <h2>Tech Arsenal</h2>
      <div class="frontend">
        <h3>Frontend</h3>
        <ul>
          <li>React</li>
          <li>JavaScript</li>
          <li>HTML</li>
          <li>CSS</li>
        </ul>
      </div>
      <div class="backend">
        <h3>Backend</h3>
        <ul>
          <li>Python</li>
          <li>Django</li>
          <li>FastAPI</li>
          <li>PostgreSQL</li>
        </ul>
      </div>
      <div class="devops">
        <h3>DevOps</h3>
        <ul>
          <li>Kubernetes</li>
          <li>Docker</li>
          <li>Git</li>
          <li>Linux</li>
        </ul>
      </div>
    </section>

    <section class="quick-facts">
      <h2>Quick Facts</h2>
      <ul>
        <li>Primary Language: Python</li>
        <li>Current Focus: Advanced FastAPI techniques</li>
        <li>Passion: Building scalable backend solutions</li>
        <li>Approach: Always learning and experimenting</li>
      </ul>
    </section>
  </body>
  </html>
  ```
</div>

<!-- Common Elements for All Formats -->
<div class="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Niaal-B&theme=radical&column=4&margin-w=15&margin-h=15" alt="GitHub Trophies" />
  <img src="https://github-readme-stats.vercel.app/api?username=Niaal-B&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" width="49%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Niaal-B&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="49%" />
  <a href="https://github.com/Niaal-B/Evara-Ecommerce">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Niaal-B&repo=Evara-Ecommerce&theme=tokyonight" alt="Project Showcase" />
  </a>
</div>

<div class="center">
  <a href="https://linkedin.com/in/Nihal B" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/Niaal-B" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://instagram.com/niaal._" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
</div>

<div class="center">
  <img src="https://komarev.com/ghpvc/?username=Niaal-B&color=blueviolet" alt="Profile Views" />
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Random Developer Quote" />
</div>

<script>
function switchFormat(format) {
  // Hide all formats
  document.querySelectorAll('.format-content').forEach(el => {
    el.classList.remove('active');
  });
  
  // Show selected format
  document.getElementById(`${format}-format`).classList.add('active');
  
  // Update button styles
  document.querySelectorAll('.format-btn').forEach(btn => {
    btn.classList.remove('active');
  });
  document.querySelector(`button[onclick="switchFormat('${format}')"]`).classList.add('active');
}
</script>

</body>
</html>

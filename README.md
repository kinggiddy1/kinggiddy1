
<style>
@import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;500&family=Space+Mono:wght@400;700&display=swap');

* { box-sizing: border-box; margin: 0; padding: 0; }

.readme {
  background: #0d1117;
  color: #e6edf3;
  font-family: 'Fira Code', monospace;
  padding: 2rem 2.5rem;
  border-radius: 12px;
  border: 1px solid #30363d;
  max-width: 860px;
  margin: 0 auto;
}

.top-bar {
  font-size: 12px;
  color: #8b949e;
  margin-bottom: 1.5rem;
  font-family: 'Fira Code', monospace;
}
.top-bar span { color: #58a6ff; }

.name-heading {
  font-size: 2rem;
  font-family: 'Space Mono', monospace;
  font-weight: 700;
  color: #e6edf3;
  margin-bottom: 0.4rem;
  display: flex;
  align-items: center;
  gap: 12px;
}

.wave { font-size: 1.8rem; }

.tagline {
  font-size: 13px;
  color: #8b949e;
  margin-bottom: 0.3rem;
}
.tagline strong { color: #79c0ff; }

.quote {
  font-size: 13px;
  color: #6e7681;
  border-left: 3px solid #388bfd;
  padding-left: 10px;
  margin: 1rem 0 1.5rem;
  font-style: italic;
}

.divider { border: none; border-top: 1px solid #21262d; margin: 1.25rem 0; }

.section-title {
  font-size: 14px;
  font-weight: 700;
  color: #e6edf3;
  font-family: 'Space Mono', monospace;
  margin-bottom: 1rem;
  display: flex;
  align-items: center;
  gap: 8px;
}

.about-text {
  font-size: 13px;
  color: #c9d1d9;
  line-height: 1.8;
  margin-bottom: 0.75rem;
}
.about-text strong { color: #79c0ff; }

.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(0, 1fr));
  gap: 8px;
  margin-bottom: 1.5rem;
}

.skill-cat {
  background: #161b22;
  border: 1px solid #30363d;
  border-radius: 8px;
  padding: 10px 12px;
}

.skill-cat-label {
  font-size: 10px;
  color: #8b949e;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  margin-bottom: 6px;
}

.skill-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 4px;
}

.tag {
  font-size: 10px;
  padding: 2px 7px;
  border-radius: 4px;
  font-family: 'Fira Code', monospace;
}
.tag-fe { background: #0d419d; color: #79c0ff; border: 1px solid #1f6feb; }
.tag-be { background: #3d2214; color: #ffa657; border: 1px solid #d1242f33; }
.tag-db { background: #1a3832; color: #56d364; border: 1px solid #2ea04333; }
.tag-mob { background: #2d1f63; color: #d2a8ff; border: 1px solid #6e40c933; }
.tag-tool { background: #1e2533; color: #8b949e; border: 1px solid #30363d; }

.contact-row {
  display: flex;
  align-items: center;
  gap: 8px;
  font-size: 12px;
  color: #8b949e;
  margin-top: 0.5rem;
}
.contact-row a { color: #58a6ff; text-decoration: none; }

.fun-row {
  font-size: 12px;
  color: #8b949e;
  margin-top: 0.5rem;
}
.fun-row span { color: #ffa657; }

.streak-box {
  background: #161b22;
  border: 1px solid #30363d;
  border-radius: 8px;
  padding: 12px;
  text-align: center;
  margin-top: 1rem;
}
.streak-box img {
  max-width: 100%;
  border-radius: 4px;
}
.streak-label {
  font-size: 11px;
  color: #6e7681;
  margin-bottom: 8px;
}

.icons-row {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 0.75rem 0;
  align-items: center;
}
.icon-badge {
  width: 32px;
  height: 32px;
  background: #161b22;
  border: 1px solid #30363d;
  border-radius: 6px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 18px;
  overflow: hidden;
}
.icon-badge img { width: 22px; height: 22px; object-fit: contain; }

.status-dot {
  width: 8px; height: 8px;
  border-radius: 50%;
  background: #3fb950;
  display: inline-block;
  margin-right: 4px;
}
</style>

<div class="readme">
  <h2 class="sr-only" style="position:absolute;width:1px;height:1px;overflow:hidden;">GitHub README preview for Egide TUYIZERE, Full-Stack Software Engineer</h2>

  <div class="top-bar">kinggiddy1 / <span>README.md</span></div>

  <div class="name-heading">
    <span class="wave">👋</span> Hey, I'm Egide TUYIZERE
  </div>

  <p class="tagline">
    <strong>Full-Stack Engineer</strong> · <strong>Technical Support Engineer</strong> · <strong>Mobile Dev</strong>
  </p>

  <blockquote class="quote">
    I build things that work — frontend, backend, mobile, and everything in between.
  </blockquote>

  <hr class="divider">

  <div class="section-title">🧠 About Me</div>

  <p class="about-text">
    I'm a <strong>Full-Stack Software Engineer</strong> with a love for clean architecture and cross-platform solutions. 
    I work across the entire stack — from pixel-perfect UIs to scalable backends and cloud deployments.
  </p>
  <p class="about-text">
    My stack spans <strong>Angular, React, Node.js, Laravel, PHP, Java</strong> and beyond — 
    with mobile experience in <strong>React Native, Expo, and Ionic</strong> for both Android &amp; iOS.
  </p>
  <p class="about-text">
    Point me at a hard problem and I'll ship something that actually solves it.
  </p>
  <p class="about-text">
    When I step away from the screen, you'll find me with <span style="color:#ffa657">🎸 guitar, 🎹 piano, 🎵 harmonica, or 🥁 drums</span> — 
    music and code share the same logic: structure, rhythm, and knowing when to improvise.
  </p>

  <hr class="divider">

  <div class="section-title">⚙️ Tech Stack</div>

  <div class="skills-grid" style="grid-template-columns: 1fr 1fr;">
    <div class="skill-cat">
      <div class="skill-cat-label">Frontend</div>
      <div class="skill-tags">
        <span class="tag tag-fe">Angular</span>
        <span class="tag tag-fe">React JS</span>
        <span class="tag tag-fe">Tailwind</span>
        <span class="tag tag-fe">Bootstrap</span>
        <span class="tag tag-fe">CSS</span>
        <span class="tag tag-fe">Flowbite</span>
        <span class="tag tag-fe">WordPress</span>
      </div>
    </div>
    <div class="skill-cat">
      <div class="skill-cat-label">Backend</div>
      <div class="skill-tags">
        <span class="tag tag-be">Node JS</span>
        <span class="tag tag-be">Laravel</span>
        <span class="tag tag-be">PHP</span>
        <span class="tag tag-be">Java</span>
        <span class="tag tag-be">TypeScript</span>
        <span class="tag tag-be">JavaScript</span>
        <span class="tag tag-be">Ajax</span>
        <span class="tag tag-be">jQuery</span>
      </div>
    </div>
    <div class="skill-cat">
      <div class="skill-cat-label">Database & Cloud</div>
      <div class="skill-tags">
        <span class="tag tag-db">MySQL</span>
        <span class="tag tag-db">PostgreSQL</span>
        <span class="tag tag-db">DBeaver</span>
        <span class="tag tag-db">cPanel</span>
        <span class="tag tag-db">YAML</span>
        <span class="tag tag-db">Cloud Computing</span>
      </div>
    </div>
    <div class="skill-cat">
      <div class="skill-cat-label">Mobile</div>
      <div class="skill-tags">
        <span class="tag tag-mob">React Native</span>
        <span class="tag tag-mob">Expo</span>
        <span class="tag tag-mob">Ionic</span>
        <span class="tag tag-mob">Android</span>
        <span class="tag tag-mob">iOS</span>
      </div>
    </div>
  </div>

  <div class="skill-cat" style="margin-bottom:1rem;">
    <div class="skill-cat-label">Other Tools</div>
    <div class="skill-tags">
      <span class="tag tag-tool">DevOps</span>
      <span class="tag tag-tool">API Integration</span>
      <span class="tag tag-tool">GitHub</span>
      <span class="tag tag-tool">Cybersecurity</span>
      <span class="tag tag-tool">OOP</span>
      <span class="tag tag-tool">CMS</span>
    </div>
  </div>

  <hr class="divider">

  <div class="section-title">📊 GitHub Stats</div>
  <div class="streak-box">
    <div class="streak-label">contribution streak</div>
    <img src="https://streak-stats.demolab.com?user=kinggiddy1&theme=radical" alt="Egide's GitHub Streak Stats" />
  </div>

  <hr class="divider">

  <div class="contact-row">
    <span class="status-dot"></span>
    <span>Reach me:</span>
    <a href="mailto:kinggiddy@gmail.com">kinggiddy@gmail.com</a>
  </div>
  <div class="fun-row" style="margin-top:8px;">
    ⚡ For fun: <span>guitar · piano · harmonica · drums</span>
  </div>

  <div style="margin-top:1.5rem; text-align:right;">
    <button onclick="sendPrompt('Let\'s work on the next section of my GitHub README — add more sections or improve what we have')" style="font-size:12px; font-family: monospace; background:#161b22; color:#58a6ff; border:1px solid #30363d; padding:6px 14px; border-radius:6px; cursor:pointer;">
      continue building ↗
    </button>
  </div>
</div>


- • Hi, I’m Egide TUYIZERE,
- a Full-Stack Software Engineer | Technical Support Engineer |
- • Frontend:  | Angular | React JS | CSS | Bootstrap | Tailwind | Flowbite | WordPress |
- • Backend:  | Node JS | Laravel | JavaScript | Typescript | PHP| Ajax | Java | jQuery |
- • Database & Cloud: | DBeaver | MySQL | PostgreSQL | Cloud Computing | cPanel | CMS | YAML |
- • Mobile Applications: | React Native | Expo | Ionic Framework for both Android & IOS |
- • Other Tools: |DevOps | API Integration | GitHub | Cybersecurity | OOP |
- • 📫 Reach me out: kinggiddy@gmail.com |
- • ⚡ For fun, I can play guitar, Piano, Harmonica, and Drums :)
  
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/angularjs/angularjs-original.svg" title="Angular" alt="Angular" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React / React Native" alt="React / React Native" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original-wordmark.svg" title="NodeJS" alt="NodeJS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/php/php-original.svg" title="PHP" alt="PHP" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/java/java-original-wordmark.svg" title="Java" alt="Java" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/bootstrap/bootstrap-original.svg" title="Bootstrap" alt="Bootstrap" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/wordpress/wordpress-original.svg" title="WordPress" alt="WordPress" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/yaml/yaml-original.svg" title="YAML" alt="YAML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/postgresql/postgresql-original.svg" title="PostgreSQL" alt="PostgreSQL" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/materialui/materialui-original.svg" title="Material UI" alt="Material UI" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/flutter/flutter-original.svg" title="Flutter" alt="Flutter" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original-wordmark.svg" title="MySQL"  alt="MySQL" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" title="AWS" alt="AWS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" alt="Git" width="40" height="40"/>&nbsp;
  <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/premierepro/premierepro-original.svg" title="Premiere" alt="Premiere" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/photoshop/photoshop-plain.svg" title="Photoshop" alt="Photoshop" width="40" height="40"/>&nbsp; 
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" title="Tailwind CSS" alt="Tailwind CSS" width="40" height="40" />&nbsp; 
   
</div>
<div>
<hr>


![Egide's GitHub Streak Stats](https://streak-stats.demolab.com?user=kinggiddy1&theme=radical) 

<hr>
</div>

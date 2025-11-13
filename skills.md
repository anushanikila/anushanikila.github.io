---
layout: page
title: Skills

---

<style>
/* ===== Skills Grid Styling ===== */
.skills-section {
  text-align: center;
  margin: 2rem auto;
  max-width: 900px;
}

.skills-section h2 {
  margin-top: 2.5rem;
  margin-bottom: 1rem;
  color: var(--text-color, #333);
}

.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
  gap: 25px;
  justify-items: center;
  align-items: center;
  margin-bottom: 2rem;
}

.skill-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  transition: transform 0.25s ease, filter 0.25s ease;
}

.skill-item:hover {
  transform: scale(1.1);
}

.skill-icon {
  width: 50px;
  height: 50px;
  margin-bottom: 6px;
  transition: filter 0.25s ease;
}

.skill-label {
  font-size: 0.85rem;
  color: #555;
}

/* ===== Dark Mode Adjustments ===== */
body.dark-mode .skill-icon {
  filter: brightness(0.85);
}

body.dark-mode .skill-item:hover .skill-icon {
  filter: brightness(1.05);
}

body.dark-mode .skill-label {
  color: #ccc;
}
</style>

<div class="skills-section">
  <h2>Languages</h2>
  <div class="skills-grid">
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" class="skill-icon"><div class="skill-label">Python</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/r/r-original.svg" alt="R" class="skill-icon"><div class="skill-label">R</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" alt="Bash" class="skill-icon"><div class="skill-label">Bash</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" class="skill-icon"><div class="skill-label">JavaScript</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript" class="skill-icon"><div class="skill-label">TypeScript</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matlab/matlab-original.svg" alt="MATLAB" class="skill-icon"><div class="skill-label">MATLAB</div></div>
  </div>

  <h2>Front-End & Back-End</h2>
  <div class="skills-grid">
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React.js" class="skill-icon"><div class="skill-label">React</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" alt="Next.js" class="skill-icon"><div class="skill-label">Next.js</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML" class="skill-icon"><div class="skill-label">HTML</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS" class="skill-icon"><div class="skill-label">CSS</div></div>
    <div class="skill-item">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" 
       alt="TailwindCSS" class="skill-icon">
  <div class="skill-label">TailwindCSS</div>
</div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" class="skill-icon"><div class="skill-label">Node.js</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" alt="Express" class="skill-icon"><div class="skill-label">Express</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" alt="Django" class="skill-icon"><div class="skill-label">Django</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" alt="Flask" class="skill-icon"><div class="skill-label">Flask</div></div>
  </div>

  <h2>Data Science & Visualization</h2>
  <div class="skills-grid">
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tableau/tableau-original.svg" alt="Tableau" class="skill-icon"><div class="skill-label">Tableau</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/powerbi/powerbi-original.svg" alt="Power BI" class="skill-icon"><div class="skill-label">Power BI</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/excel/excel-original.svg" alt="Excel" class="skill-icon"><div class="skill-label">Excel</div></div>
  </div>

  <h2>Databases & Version Control</h2>
  <div class="skills-grid">
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" class="skill-icon"><div class="skill-label">MySQL</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" class="skill-icon"><div class="skill-label">PostgreSQL</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="MongoDB" class="skill-icon"><div class="skill-label">MongoDB</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" alt="Redis" class="skill-icon"><div class="skill-label">Redis</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" class="skill-icon"><div class="skill-label">Git</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" class="skill-icon"><div class="skill-label">GitHub</div></div>
  </div>

  <h2>Cloud & DevOps</h2>
  <div class="skills-grid">
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" class="skill-icon"><div class="skill-label">Docker</div></div>
    <div class="skill-item">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg" 
       alt="AWS" class="skill-icon">
  <div class="skill-label">AWS</div>
</div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" alt="GCP" class="skill-icon"><div class="skill-label">GCP</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" alt="Azure" class="skill-icon"><div class="skill-label">Azure</div></div>
  </div>

  <h2>Libraries & Frameworks</h2>
  <div class="skills-grid">
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" alt="Pandas" class="skill-icon"><div class="skill-label">Pandas</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="NumPy" class="skill-icon"><div class="skill-label">NumPy</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/scikitlearn/scikitlearn-original.svg" alt="Scikit-learn" class="skill-icon"><div class="skill-label">Scikit-learn</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" alt="TensorFlow" class="skill-icon"><div class="skill-label">TensorFlow</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/keras/keras-original.svg" alt="Keras" class="skill-icon"><div class="skill-label">Keras</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" alt="PyTorch" class="skill-icon"><div class="skill-label">PyTorch</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nltk/nltk-original.svg" alt="NLTK" class="skill-icon"><div class="skill-label">NLTK</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spacy/spacy-original.svg" alt="spaCy" class="skill-icon"><div class="skill-label">spaCy</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" alt="Matplotlib" class="skill-icon"><div class="skill-label">Matplotlib</div></div>
  </div>
</div>

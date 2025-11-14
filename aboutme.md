---
layout: page
title: About me

---
<style>
.about-wrapper {
  display: flex;
  align-items: flex-start;
  gap: 40px;
  flex-wrap: nowrap; /* keeps them side-by-side */
  margin-top: 20px;
}

.about-photo {
  width: 380px;        /* increase this */
  max-width: 55%;      /* ensures it scales nicely */
  border-radius: 14px;
}

.about-text {
  flex: 1;
  max-width: 40%;      /* shrink text container */
  font-size: 15px;     /* slightly smaller body text */
  line-height: 1.55;
}

.about-text p {
  margin-top: 0;
}

/* Mobile / tablet view */
@media (max-width: 768px) {
  .about-wrapper {
    flex-direction: column; /* stack vertically */
    align-items: center;    /* center image + text */
    gap: 20px;              /* reduce gap for smaller screens */
  }

  .about-text {
    max-width: 100%;        /* let text take full width */
    text-align: center;     /* optional: nicer layout on small screens */
    font-size: 14px;        /* slightly smaller for mobile */
  }

  .about-photo {
    max-width: 80%;         /* image scales down for small screens */
    width: auto;
  }
}  

.spark {
  display: inline-block;
  animation: sparkle 1s infinite;
  transform-origin: center;
}

@keyframes sparkle {
  0%   { transform: scale(1); opacity: 1; color: gold; }
  25%  { transform: scale(1.2) rotate(10deg); opacity: 0.8; color: #ffdd33; }
  50%  { transform: scale(1); rotate(-10deg); opacity: 1; color: gold; }
  75%  { transform: scale(1.1) rotate(5deg); opacity: 0.9; color: #ffee66; }
  100% { transform: scale(1); rotate(0deg); opacity: 1; color: gold; 
}
  
/* Remove default bullet dots */
.what-i-do ul {
  list-style-type: none;
  padding-left: 0;
  margin-left: 0;
  margin-top: 10px;
  line-height: 1.6;
}

.what-i-do li {
  margin-bottom: 10px;
}

.what-i-do {
  margin-top: 10px;
}

.what-i-do {
  font-size: 15px;
}
</style>

<div class="about-wrapper">
  <img src="/assets/img/IMG_6616.JPG" class="about-photo">

  <div class="about-text">
    <p>Hello there, I’m Nush! I’m a data scientist and biomedical engineer with a passion for building intelligent systems that bridge technology and human experience. My work spans from deploying software solutions in live neurosurgery to exploring machine learning, natural language processing, large language models, generative AI, and agentic AI, always with the goal of making complex systems more intuitive and impactful.</p>

    <p>Growing up across Germany, Singapore, and the U.S. gave me a global perspective and a curiosity about how culture, creativity, and data intersect. I express myself through photography, fashion, painting, writing, poetry, storytelling, singing, and guitar. Each of these passions teaches me something about observation, pattern, and expression, and they shape the way I approach AI and problem-solving. This space is where creativity and analysis come together to inspire new ideas and meaningful work.</p>
  </div>
</div>

<div class="what-i-do">
  <h2>What I Do:</h2>
  <ul>
    <li><span class="spark">⚡</span> Experienced in end-to-end data engineering on AWS and Azure using Databricks, PySpark, Delta Lake, and ADF</li>
    <li><span class="spark">⚡</span> Skilled in workflow orchestration and automation with Airflow, Azure DevOps, GitHub, and Docker</li>
    <li><span class="spark">⚡</span> Transforming raw data into business intelligence using Power BI, Tableau, and Excel</li>
    <li><span class="spark">⚡</span> Applying machine learning and predictive modeling with Scikit-learn, TensorFlow, and PyTorch</li>
    <li><span class="spark">⚡</span> Exploring NLP, large language models, generative AI, and agentic AI to build systems that understand and interact with human language</li>
  </ul>
</div>


<div style="text-align: center; margin: 20px 0;">
  <a href="{{ '/assets/AnushaSivakumar Resume 2025.pdf' | relative_url }}" class="btn btn-secondary" download>
    Download My Résumé
  </a>
</div>

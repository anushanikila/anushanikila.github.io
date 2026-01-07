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
  font-size: 13px;     /* slightly smaller body text */
  line-height: 1.55;
}

.about-text p {
  margin-top: 0;
}

.what-i-do {
  font-size: 13px;
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
  100% { transform: scale(1); rotate(0deg); opacity: 1; color: gold; }
}
  
/* Remove bullets from What I Do section including pseudo-elements */
.what-i-do ul,
.what-i-do li,
.what-i-do li::before,
.what-i-do li::marker {
  list-style: none !important;   /* remove default bullets */
  content: none !important;      /* remove any pseudo-element bullet */
  padding: 0 !important;
  margin: 0 !important;
}

 /* Slide-in animation for bullets */
.what-i-do li {
  display: flex;
  align-items: flex-start;
  gap: 8px;
  margin-bottom: 10px;

  /* Start off invisible and slightly left */
  opacity: 0;
  transform: translateX(-20px);

  /* Animate in */
  animation: slideIn 0.6s forwards;
}

/* Stagger each bullet */
.what-i-do li:nth-child(1) { animation-delay: 0.2s; }
.what-i-do li:nth-child(2) { animation-delay: 0.4s; }
.what-i-do li:nth-child(3) { animation-delay: 0.6s; }
.what-i-do li:nth-child(4) { animation-delay: 0.8s; }
.what-i-do li:nth-child(5) { animation-delay: 1s; }

/* Keyframes for slide-in */
@keyframes slideIn {
  to {
    opacity: 1;
    transform: translateX(0);
  }
} 
  
</style>

<div class="about-wrapper">
  <img src="/assets/img/IMG_6616.JPG" class="about-photo">

  <div class="about-text">
    <p>Hello there, I’m Nush! I’m a data scientist and biomedical engineer who loves building intelligent systems that connect technology and human experience. I earned my Master’s in Data Science & Analytics from UMass Amherst (ML/AI focus) and my Bachelor’s in Biomedical Engineering from Tulane University. I’ve worked cross-functionally across teams to tackle real-world problems—from deploying software in live neurosurgery at Brainlab/UCSF, to creating AI-driven patient adherence models at CareCentra, designing scalable web platforms as a freelance developer with 100Devs, and driving growth strategy at Bhoomi Inc. My work blends collaboration with a focus on making complex systems intuitive, impactful, and human-centered, whether through machine learning, NLP, generative AI, or agentic AI.</p>

    <p>Growing up across Germany, Singapore, and the U.S. gave me a global perspective and a curiosity about how culture, creativity, and data intersect. I express myself through photography, fashion, painting, writing, poetry, storytelling, singing, and guitar—each passion shaping how I approach AI and problem-solving. This is where creativity and analysis meet to inspire new ideas and meaningful work.</p>
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
  <a href="{{ '/assets/Anusha Sivakumar Resume Jan 2026.pdf' | relative_url }}" class="btn btn-secondary" download>
    Download My Résumé
  </a>
</div>

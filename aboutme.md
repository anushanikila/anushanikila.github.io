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
  font-size: 10px;     /* slightly smaller body text */
  line-height: 1.55;
}

.about-text p {
  margin-top: 0;
}

.what-i-do {
  font-size: 10px;
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
    <p>Hello there, I’m Nush! I'm a Product Owner and Biomedical Engineer with 8+ years building clinical AI systems, SaMD platforms, and digital health products at the intersection of technology, data science, and human health. Currently, I'm owning product strategy and agentic AI development at ZTensor — designing autonomous AI systems that make real-time decisions at scale. Before that, I've delivered everything from neurosurgical decision support software in live OR environments at UCSF to AI-driven behavioral health programs at CareCentra -always at the place where clinical evidence meets product execution.</p>

    <p>I hold a Master's in Data Science & Analytics (ML/AI) from UMass Amherst and a Bachelor's in Biomedical Engineering from Tulane University. My edge as a PM is rare: I can speak fluently with engineers, clinicians, data scientists, and executive stakeholders, and translate between all of them to ship products that actually work in regulated, high-stakes environments.</p>
    
    <p>Growing up across Germany, Singapore, and the U.S. shaped how I think about problems, globally, creatively, and always with the end user in mind. I bring that same cross-cultural curiosity to every product I build. Outside of work I express myself through photography, painting, writing, music, and fashion; each one a different way of asking the same question I bring to product work: how do we make something complex feel human?</p>   
  </div>
</div>

<div class="what-i-do">
  <h2>What I Do:</h2>
  <ul>
    <li><span class="spark">⚡</span> Clinical domain depth: SaMD platforms, digital biomarkers, wearable health data, regulated environments</li>
    <li><span class="spark">⚡</span> AI/ML product intuition: from agentic AI pipelines at ZTensor to clinical decision support models, built and shipped in production</li>
    <li><span class="spark">⚡</span> Cross-functional leadership: managing engineers, data scientists, clinicians, and executives toward a shared product vision</li>
    <li><span class="spark">⚡</span> Data-driven decision making: SQL, Snowflake, Power BI, and hands-on ML experience informing every roadmap call</li>
    <li><span class="spark">⚡</span> Global perspective: full professional German, multilingual, experienced on multinational teams</li>
  </ul>
</div>


<div style="text-align: center; margin: 20px 0;">
  <a href="{{ '/assets/AnushaSivakumar_PM_Data_BME.pdf' | relative_url }}" class="btn btn-secondary" download>
    Download My Résumé
  </a>
</div>

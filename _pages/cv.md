---
layout: pages
title: "CV"
permalink: /cv/
---

<style>
  .cv-wrap {
    max-width: 720px;
    margin: 0 auto;
  }
  .cv-header {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    margin-bottom: 15px;
  }
  .cv-header h2 {
    text-align: left;
    margin: 0;
  }
  .cv-download {
    font-size: 15px;
    margin-left: 10px;
  }
  .cv-lang {
    font-size: 15px;
  }
  .cv-embed {
    width: 100%;
    height: 80vh;
    border: 1px solid #d5d5d5;
    border-radius: 8px;
  }
</style>

<div class="cv-wrap">
  <div class="cv-header">
    <h2>Curriculum Vitae
      <a class="cv-download" href="{{ '/files/education-and-experience/adrian_plasencia_cv_eng.pdf' | relative_url }}" target="_blank">Download PDF</a>
    </h2>
    <a class="cv-lang" href="{{ '/files/education-and-experience/adrian_plasencia_cv_esp.pdf' | relative_url }}" target="_blank">[spanish version]</a>
  </div>
  <embed class="cv-embed" src="{{ '/files/education-and-experience/adrian_plasencia_cv_eng.pdf' | relative_url }}#view=FitH" type="application/pdf">
</div>

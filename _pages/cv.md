---
layout: cv
permalink: /cv/
title: CV
nav: true
nav_order: 3
cv_pdf:
cv_format: rendercv # options: rendercv, jsonresume
description: Curriculum vitae.
toc:
  sidebar: left
---

<style>
  .cv .location {
    display: none;
  }
</style>

<script>
  document.addEventListener("DOMContentLoaded", () => {
    const projectsAnchor = document.getElementById("projects");
    if (!projectsAnchor) return;

    const projectsCard = projectsAnchor.nextElementSibling;
    const title = projectsCard?.querySelector(".card-title");
    if (title?.textContent.trim() === "Projects") {
      title.textContent = "Presentations";
    }
  });
</script>

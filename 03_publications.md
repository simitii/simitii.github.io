---
permalink: /publications
title: Publications
layout: page
---

[DBLP](https://dblp.org/pers/hd/d/Demir:Samet) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Google Scholar](https://scholar.google.com/citations?user=VKyOvOYAAAAJ)

<style>
.loading-container {
  width: 100%;
  padding: 20px 0;
  text-align: center;
}

.loading-bar {
  width: 50%;
  height: 4px;
  background-color: #f0f0f0;
  border-radius: 2px;
  margin: 10px auto;
  position: relative;
  overflow: hidden;
}

.loading-bar::after {
  content: '';
  display: block;
  position: absolute;
  left: -200px;
  width: 200px;
  height: 4px;
  background-color: #2196F3;
  animation: loading 2s linear infinite;
}

@keyframes loading {
  from {
    left: -200px;
    width: 30%;
  }
  50% {
    width: 30%;
  }
  70% {
    width: 70%;
  }
  80% {
    left: 50%;
  }
  95% {
    left: 120%;
  }
  to {
    left: 100%;
  }
}

#publications-loading {
  display: block;
}

#publications-content {
  display: none;
}
</style>

<div id="publications-loading" class="loading-container">
  <p>Loading publications...</p>
  <div class="loading-bar"></div>
</div>

<div id="publications-content">
    <script src="https://bibbase.org/show?bib=https://dblp.org/pid/254/1845.bib&noBootstrap=1&jsonp=1"></script>
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  // Function to check if bibbase content is loaded
  function checkBibbaseLoaded() {
    const bibbaseContent = document.querySelector('.bibbase_paper');
    if (bibbaseContent) {
      // Wait 2 more seconds before showing content
      setTimeout(() => {
        document.getElementById('publications-loading').style.display = 'none';
        document.getElementById('publications-content').style.display = 'block';
      }, 2000);
    } else {
      // Check again after a short delay
      setTimeout(checkBibbaseLoaded, 100);
    }
  }

  // Start checking
  checkBibbaseLoaded();
});
</script>
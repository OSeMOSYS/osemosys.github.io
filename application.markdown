---
theme: jekyll-theme-primer
layout: sub-page
title: OSeMOSYS
permalink: /applications/
---
<section class="bg-gray-light container-lg p-responsive py-4 py-md-6 my-lg-6 fade-in-center">
  <div class="text-center fade-in-center">
    <h2 class="alt-h2 mb-4">OSeMOSYS Applications</h2>
  </div>

  <div class="applications-content text-left">
    <p class="lead mb-4">OSeMOSYS is a fundamental building block for a wide range of applications across government, industry, and academia. Several examples include:</p>

    <div class="applications-grid">
      <div class="application-category">
        <h3 class="category-title">Governments</h3>
        <ul class="application-list">
          <li><a href="https://energypedia.info/wiki/LTEM_-_Energy_Department_of_the_Cyprus_Institute">National Energy and Climate Plan in Cyprus</a></li>
          <li><a href="https://www.wri.org/research/costos-y-beneficios-de-la-descarbonizacion-de-la-economia-de-costa-rica-evaluacion-del-plan-nacional-de-descarbonizacion-bajo-incertidumbre.pdf">National Decarbonization Plan in Costa Rica</a></li>
          <li><a href="https://www.afd.fr/es/actualites/ecuador-construye-su-camino-hacia-la-descarbonizacion">National Climate Change Mitigation Plan in Ecuador</a></li>
          <li><a href="https://www.rvo.nl/sites/default/files/2023-06/Report-Final-Draft_Signed-01-1.pdf">Green Hydrogen and Ammonia Roadmap in Lao PDR</a></li>
        </ul>
      </div>

      <div class="application-category">
        <h3 class="category-title">Industry and Think Tanks</h3>
        <ul class="application-list">
          <li><a href="https://www.globalccsinstitute.com/wp-content/uploads/2021/10/genzo1123.pdf">Global CCS Institute</a></li>
          <li><a href="https://www.kapsarc.org/research/projects/kosemosys/">King Abdullah Petroleum Studies and Research Center</a></li>
          <li><a href="https://www.seforall.org/news/driving-to-the-outcomes-with-an-ecosystem-approach">Sustainable Energy for All</a></li>
          <li><a href="https://github.com/transition-zero/tz-osemosys">Transition Zero – TZ-OSeMOSYS</a></li>
        </ul>
      </div>

      <div class="application-category">
        <h3 class="category-title">Academia</h3>
        <ul class="application-list">
          <li><a href="https://kth.diva-portal.org/smash/get/diva2:1576316/FULLTEXT01.pdf">Politecnico di Milano – Long-term energy planning with highly-detailed demand modelling for Egypt</a></li>
          <li><a href="https://kth.diva-portal.org/smash/get/diva2:1576316/FULLTEXT01.pdf">KTH – Hydrogen and electricity system dynamics in the Nordic region</a></li>
          <li><a href="https://www.lboro.ac.uk/research/steer/research/themes/systems-analysis/">Loughborough University – STEER Centre for Sustainable Transitions</a></li>
          <li><a href="https://spiral.imperial.ac.uk/handle/10044/1/104682">Imperial College London – Energy security modelling in Armenia</a></li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section class="container-lg p-responsive py-4 py-md-6 my-lg-6">
  <div class="text-center mb-5">
    <h2 class="alt-h2">Specialist versions of the tool</h2>
  </div>

  <div class="slider-wrapper my-5">
    <div class="arrow arrow-left" onclick="slideTextPrev()">‹</div>

    <div class="slider-container">
      <div class="slider" id="textSlider">
        <div class="slide-card">
          <h3>OSeMOSYS Global</h3>
          <p><a href="https://osemosys-global.readthedocs.io/en/latest/" target="_blank">Open-source global electricity model</a></p>
        </div>

        <div class="slide-card">
          <h3>GENESYS-MOD</h3>
          <p><a href="https://git.tu-berlin.de/genesysmod/genesys-mod-public" target="_blank">Modular European decarbonisation model</a></p>
        </div>

        <div class="slide-card">
          <h3>TEMBA</h3>
          <p><a href="https://zenodo.org/records/3521841" target="_blank">The African electricity model base</a></p>
        </div>

        <div class="slide-card">
          <h3>OSeMBE</h3>
          <p><a href="https://github.com/HauHe/OSeMBE" target="_blank">Open Source energy Model – Base for Europe</a></p>
        </div>

        <div class="slide-card">
          <h3>SAMBA</h3>
          <p><a href="http://www.osemosys.org/samba.html" target="_blank">Southern African Model Base for Analysis</a></p>
        </div>
      </div>
    </div>

    <div class="arrow arrow-right" onclick="slideTextNext()">›</div>
  </div>

  <div class="slider-dots text-center mt-3" id="sliderDots"></div>
</section>

<section class="container-lg p-responsive py-4 py-md-6 my-lg-6">
  <div class="recommended-reading">
    <h2 class="alt-h2 text-center mb-4">Recommended Reading</h2>
    <p class="text-center mb-5">For a broader analysis of applications and advancements in OSeMOSYS, see the following peer-reviewed publications:</p>

    <div class="publications-list">
      {% for publication in site.data.publications %}
      <div class="publication-item mb-4 p-4 border border-gray-200 rounded">
        <h4 class="publication-title mb-2">
          <a href="{{ publication.url }}" target="_blank" class="text-decoration-none">
            {{ publication.title }}
          </a>
        </h4>
        <p class="publication-authors text-muted mb-2">
          {{ publication.authors }} ({{ publication.year }})
        </p>
        <p class="publication-journal mb-2">
          <em>{{ publication.journal }}</em>
        </p>
        <p class="publication-abstract text-justify">
          {{ publication.abstract }}
        </p>
      </div>
      {% endfor %}
    </div>

  </div>
  
</section>

<style>
/* Enhanced Applications Page Styling */
.applications-content {
  max-width: 1200px;
  margin: 0 auto;
}

.applications-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.application-category {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease;
}

.application-category:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
}

.category-title {
  color: #0366d6;
  font-size: 1.3rem;
  font-weight: 600;
  margin-bottom: 1rem;
  padding-bottom: 0.5rem;
  border-bottom: 2px solid #e1e4e8;
}

.application-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.application-list li {
  margin-bottom: 0.8rem;
  padding-left: 1.5rem;
  position: relative;
}

.application-list li::before {
  content: "→";
  position: absolute;
  left: 0;
  color: #0366d6;
  font-weight: bold;
}

.application-list a {
  color: #24292e;
  text-decoration: none;
  transition: color 0.3s ease;
  line-height: 1.5;
}

.application-list a:hover {
  color: #0366d6;
  text-decoration: underline;
}

/* Enhanced Slider Styling */
.slider-wrapper {
  position: relative;
  max-width: 800px;
  margin: 0 auto;
  display: flex;
  align-items: center;
}

.slider-container {
  overflow: hidden;
  width: 100%;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.slider {
  display: flex;
  transition: transform 0.6s ease-in-out;
}

.slide-card {
  min-width: 100%;
  padding: 2.5rem;
  background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
  border-left: 5px solid #0366d6;
  text-align: center;
  transition: all 0.3s ease;
}

.slide-card:hover {
  background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%);
  transform: scale(1.02);
}

.slide-card h3 {
  margin-bottom: 1rem;
  color: #24292e;
  font-size: 1.5rem;
  font-weight: 600;
}

.slide-card a {
  color: #0366d6;
  text-decoration: none;
  font-weight: 500;
  font-size: 1.1rem;
  transition: all 0.3s ease;
}

.slide-card a:hover {
  color: #0056b3;
  text-decoration: underline;
}

.arrow {
  font-size: 2.5rem;
  cursor: pointer;
  user-select: none;
  padding: 0.5rem 1rem;
  color: #0366d6;
  background: rgba(255, 255, 255, 0.9);
  border-radius: 8px;
  transition: all 0.3s ease;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.arrow:hover {
  background: white;
  transform: scale(1.1);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
}

.arrow-left {
  position: absolute;
  left: -50px;
}

.arrow-right {
  position: absolute;
  right: -50px;
}

.slider-dots {
  display: flex;
  justify-content: center;
  gap: 12px;
  margin-top: 1.5rem;
}

.slider-dots .dot {
  width: 12px;
  height: 12px;
  background-color: #d1d5da;
  border-radius: 50%;
  cursor: pointer;
  transition: all 0.3s ease;
}

.slider-dots .dot:hover {
  background-color: #0366d6;
  transform: scale(1.2);
}

.slider-dots .dot.active {
  background-color: #0366d6;
  transform: scale(1.2);
}

/* Enhanced Publications Styling */
.recommended-reading {
  max-width: 1000px;
  margin: 0 auto;
}

.publications-list {
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

.publication-item {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease;
  border-left: 4px solid #0366d6;
}

.publication-item:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
}

.publication-header {
  margin-bottom: 1rem;
}

.publication-title {
  font-size: 1.2rem;
  font-weight: 600;
  color: #24292e;
  margin-bottom: 0.5rem;
  line-height: 1.4;
}

.publication-authors {
  font-weight: 500;
  color: #586069;
  margin-bottom: 0.3rem;
}

.publication-journal {
  font-style: italic;
  color: #586069;
  margin-bottom: 0.5rem;
}

.publication-link {
  color: #0366d6;
  text-decoration: none;
  font-size: 0.9rem;
  word-break: break-all;
}

.publication-link:hover {
  text-decoration: underline;
}

.publication-abstract {
  color: #586069;
  line-height: 1.6;
  font-size: 0.95rem;
  text-align: justify;
}

/* Responsive Design */
@media (max-width: 768px) {
  .applications-grid {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }
  
  .application-category {
    padding: 1.5rem;
  }
  
  .arrow-left {
    left: -30px;
  }
  
  .arrow-right {
    right: -30px;
  }
  
  .slide-card {
    padding: 2rem 1.5rem;
  }
  
  .publication-item {
    padding: 1.5rem;
  }
}

@media (max-width: 480px) {
  .arrow {
    font-size: 2rem;
    padding: 0.3rem 0.8rem;
  }
  
  .arrow-left {
    left: -25px;
  }
  
  .arrow-right {
    right: -25px;
  }
}

/* Enhanced fade-in animations */
.fade-in-center {
  opacity: 0;
  transform: translateY(30px);
  animation: fadeInUp 1.2s ease-out forwards;
}

@keyframes fadeInUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>

<script>
// Enhanced Slider Functionality
let slideIndex = 0;
const textSlider = document.getElementById("textSlider");
const textSlides = textSlider.children.length;
const dotsContainer = document.getElementById("sliderDots");

function updateSlider() {
  textSlider.style.transform = `translateX(-${slideIndex * 100}%)`;
  updateDots();
}

function slideTextNext() {
  slideIndex = (slideIndex + 1) % textSlides;
  updateSlider();
}

function slideTextPrev() {
  slideIndex = (slideIndex - 1 + textSlides) % textSlides;
  updateSlider();
}

function createDots() {
  for (let i = 0; i < textSlides; i++) {
    const dot = document.createElement("span");
    dot.classList.add("dot");
    dot.addEventListener("click", () => {
      slideIndex = i;
      updateSlider();
    });
    dotsContainer.appendChild(dot);
  }
}

function updateDots() {
  const dots = document.querySelectorAll(".slider-dots .dot");
  dots.forEach((dot, i) => {
    dot.classList.toggle("active", i === slideIndex);
  });
}

// Auto-slide functionality
let sliderInterval = setInterval(slideTextNext, 5000);

// Pause auto-slide on hover
textSlider.parentElement.addEventListener("mouseenter", () => {
  clearInterval(sliderInterval);
});

textSlider.parentElement.addEventListener("mouseleave", () => {
  sliderInterval = setInterval(slideTextNext, 5000);
});

// Keyboard navigation
document.addEventListener("keydown", (e) => {
  if (e.key === "ArrowLeft") {
    slideTextPrev();
  } else if (e.key === "ArrowRight") {
    slideTextNext();
  }
});

// Initialize
createDots();
updateSlider();
</script>

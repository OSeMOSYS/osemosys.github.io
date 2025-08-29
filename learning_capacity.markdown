---
theme: jekyll-theme-primer
layout: sub-page
title: OSeMOSYS
permalink: /learning_capacity/
---

<section class="bg-gray-light py-5 fade-in-center">
  <div class="container-lg p-responsive">

  <div class="text-center fade-in-center">
    <h2 class="alt-h2 mb-4">Learning & Capacity Building</h2>
  </div>
    <div class="mt-3 animate-in">
      <h3 class="alt-h3 mt-3 animate-in" style="font-size: 1.25rem;">
        <a href="https://www.open.edu/openlearncreate/course/view.php?id=13558" class="text-dark font-weight-bold" style="text-decoration: none;">
          <strong>📘 Open University Course on Energy System Modelling using OSeMOSYS</strong>
        </a>
      </h3>
      <p class="animate-in" style="font-size: 0.95rem;">This comprehensive course provides students with a strong foundation in energy system modelling using OSeMOSYS (Open Source Energy Modelling System).</p>
      <p class="animate-in">
        <a href="https://www.open.edu/openlearncreate/course/view.php?id=13558" class="btn btn-outline-light">Access Here →</a>
      </p>
    </div>

    <div class="mt-3 animate-in">
      <h3 class="alt-h3 mt-3 animate-in" style="font-size: 1.25rem;">📦 Starter Data Kits</h3>
      <p class="animate-in" style="font-size: 0.95rem;">Take your skills to the next level by modelling a zero-order representation of your country using specially designed national data packages adapted for OSeMOSYS.</p>
      <div class="row align-items-center mb-4 animate-in">
        <div class="col-md-6">
          <p class="animate-in" style="font-size: 0.95rem;">Enhance your skills in energy systems modelling with our user-friendly interface and additional learning materials, enabling comprehensive national-level modelling of the power and transport sectors.</p>
          <ul class="animate-in">
            <li><strong>Download Interface</strong> – <em>Coming soon</em></li>
            <li><strong>Teaching Material (Zenodo)</strong> – <em>Coming soon</em></li>
          </ul>
        </div>
      </div>
    </div>

    <div class="mt-3 animate-in">
      <h3 class="alt-h3 mt-1 animate-in" style="font-size: 1.25rem;">🎓 Energy Modelling Community (YouTube Playlist)</h3>
      <div class="row align-items-center text-left mb-4 animate-in">
        <div class="col-md-6">
          <p class="animate-in" style="font-size: 0.95rem;">Explore insights and community discussions from the Energy Modelling Platform and Climate Compatible Growth events.</p>
          <p class="animate-in"><a href="https://www.youtube.com/watch?v=of8JpyEd8_Y&list=PLhLN8V8JSUnJgt4SIE7gnXXncVEaXh0Ir" target="_blank" class="btn btn-outline-primary sky-blue-accent d-block d-sm-inline-block px-1 px-md-3" style="border-color: #3490dc; color: #3490dc;">Watch on YouTube →</a></p>
        </div>
      </div>
    </div>

    <div class="mt-3 animate-in">
      <h3 class="alt-h3 mt-3 animate-in" style="font-size: 1.25rem;">
        <a href="https://climatecompatiblegrowth.com/energy-modelling-platform/" class="text-dark font-weight-bold" style="text-decoration: none;">
          <strong>🌍 Energy Modelling Platforms (EMPs)</strong>
        </a>
      </h3>
      <p class="animate-in" style="font-size: 0.95rem;">By offering training to professionals from the Global South, the Energy Modelling Platforms (EMPs) enable these countries to gather critical data, perform independent analyses, and develop credible investment proposals for clean energy infrastructure projects. EMPs play a vital role in what we refer to as local capacity building.</p>
      <p class="animate-in">
        <a href="https://climatecompatiblegrowth.com/energy-modelling-platform/" class="btn btn-outline-light">Learn more →</a>
      </p>
    </div>


    <div class="container-lg p-responsive py-4 py-md-6 my-lg-6 animate-in">
      <h3 class="alt-h3 text-center mb-3 animate-in" style="font-size: 1.25rem;">🌍 Explore EMP Events</h3>
      
      <div class="clearfix gutter-spacious">
        {% for event in site.data.learning_events.events %}
        <div class="col-md-4 float-left animate-in mb-4">
          <h3 class="alt-h3 mb-3">{{ event.title }}</h3>
          <p><a href="" target="_blank">
            <img src="{{ event.image }}" class="img-fluid" alt="{{ event.alt }}"/></a>
          </p>
          <p class="text-gray">{{ event.description }}</p>
          <details class="animate-in">
            <summary class="btn btn-sm btn-outline toggle-arrow">Show Outputs</summary>
            <ul class="mt-2">
              {% for output in event.outputs %}
              <li class="animate-in">{{ output.flag }} <strong>{{ output.country }}</strong>: <a href="{{ output.url }}" target="_blank">{{ output.title }}</a></li>
              {% endfor %}
            </ul>
          </details>
        </div>
        {% endfor %}
      </div>

      <!-- EMP-Adjacent Events -->
      <div class="clearfix gutter-spacious">
        <div class="col-md-12 animate-in mb-4">
          <h3 class="alt-h3 mb-3">EMP-Adjacent Events</h3>
          <p class="text-gray">These capacity building events used the OSeMOSYS methodology outside the formal EMP series:</p>
          <ul>
            {% for adjacent in site.data.learning_events.adjacent_events %}
            <li class="animate-in">{{ adjacent.flag }} <a href="{{ adjacent.url }}" target="_blank">{{ adjacent.title }}</a></li>
            {% endfor %}
          </ul>
        </div>
      </div>
    </div>

    <h3 class="alt-h3 mt-3 animate-in" style="font-size: 1.25rem;">🛠️ Flatpack Program</h3>
    <p class="animate-in" style="font-size: 0.95rem;">Content to be updated soon.</p>

  </div>
</section>

<style>
/* Fade-in animation for main title */
.fade-in-center {
  opacity: 0;
  transform: translateY(20px);
  animation: fadeInUp 1s ease forwards;
}

@keyframes fadeInUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Animate-in effects for all elements */
.animate-in {
  opacity: 0;
  transform: translateY(30px);
  animation: animateIn 0.8s ease-out forwards;
  animation-delay: var(--animation-delay, 0s);
}

/* Staggered animation delays */
.animate-in:nth-child(1) { --animation-delay: 0.1s; }
.animate-in:nth-child(2) { --animation-delay: 0.2s; }
.animate-in:nth-child(3) { --animation-delay: 0.3s; }
.animate-in:nth-child(4) { --animation-delay: 0.4s; }
.animate-in:nth-child(5) { --animation-delay: 0.5s; }
.animate-in:nth-child(6) { --animation-delay: 0.6s; }
.animate-in:nth-child(7) { --animation-delay: 0.7s; }
.animate-in:nth-child(8) { --animation-delay: 0.8s; }
.animate-in:nth-child(9) { --animation-delay: 0.9s; }
.animate-in:nth-child(10) { --animation-delay: 1.0s; }

/* Column animations with staggered delays for 3-column layout */
.col-md-4.float-left.animate-in:nth-child(1) { animation-delay: 0.1s; }
.col-md-4.float-left.animate-in:nth-child(2) { animation-delay: 0.2s; }
.col-md-4.float-left.animate-in:nth-child(3) { animation-delay: 0.3s; }

/* Column hover effects */
.col-md-4.float-left {
  transition: all 0.3s ease;
  display: flex;
  flex-direction: column;
  height: 100%;
}

.col-md-4.float-left:hover {
  transform: translateY(-4px);
}

/* Standardize column height and content distribution */
.col-md-4.float-left > h3 {
  flex-shrink: 0;
  min-height: 5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  margin-bottom: 1rem;
  line-height: 1.3;
}

.col-md-4.float-left > p:first-of-type {
  flex-shrink: 0;
  text-align: center;
  margin-bottom: 1rem;
}

/* Standardized image container */
.col-md-4 img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  object-position: center;
  border-radius: 8px;
  transition: transform 0.3s ease;
}

.col-md-4 img:hover {
  transform: scale(1.02);
}

/* Text content area - flexible height */
.col-md-4.float-left > p.text-gray {
  flex: 1;
  margin-bottom: 1.5rem;
  line-height: 1.5;
}

/* Details section at bottom - aligned */
.col-md-4.float-left > details {
  margin-top: auto;
  align-self: flex-start;
}

/* Button alignment */
.col-md-4.float-left > details > summary {
  margin: 0;
}

/* List item animations */
li.animate-in:nth-child(1) { animation-delay: 0.1s; }
li.animate-in:nth-child(2) { animation-delay: 0.2s; }
li.animate-in:nth-child(3) { animation-delay: 0.3s; }
li.animate-in:nth-child(4) { animation-delay: 0.4s; }
li.animate-in:nth-child(5) { animation-delay: 0.5s; }
li.animate-in:nth-child(6) { animation-delay: 0.6s; }
li.animate-in:nth-child(7) { animation-delay: 0.7s; }
li.animate-in:nth-child(8) { animation-delay: 0.8s; }
li.animate-in:nth-child(9) { animation-delay: 0.9s; }

@keyframes animateIn {
  from {
    opacity: 0;
    transform: translateY(30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Hover effects for interactive elements */
.animate-in:hover {
  transform: translateY(-2px);
  transition: transform 0.3s ease;
}

/* Enhanced container animations */
.container .animate-in {
  animation-delay: 0.3s;
}

/* Button hover animations */
.btn.animate-in:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  transition: all 0.3s ease;
}

/* Image animations */
img.animate-in:hover {
  transform: scale(1.05);
  transition: transform 0.3s ease;
}

.toggle-arrow::after {
  content: '↓';
  display: inline-block;
  margin-left: 6px;
  transition: transform 0.3s ease;
}
details[open] .toggle-arrow::after {
  transform: rotate(180deg);
}
</style>
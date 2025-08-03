---
theme: jekyll-theme-primer
layout: sub-page
title: OSeMOSYS
permalink: /about/
---
<section class="bg-gray-light container-lg p-responsive py-4 py-md-6 my-lg-6 fade-in-center">
<div class="text-center fade-in-center">
  <h2 class="alt-h3 mb-4">About OSeMOSYS </h2>
  <div class="container-lg p-responsive py-4 py-md-6 ">
    <div class="col-md-12 animate-out mb-2">
      <p class="alt-lead text-gray text-justify-between col-md-15 mx-auto" style="text-align: justify; font-size: 0.875em;">
        <strong>OSeMOSYS</strong> is a full-fledged systems optimization model for long-run energy planning.
        The initial working code of OSeMOSYS was published in 2008 in a presentation at the International Energy Workshop in Paris at the IEA
        (<a href="https://www.osemosys.org/uploads/1/8/5/0/18504136/osemosys_iea_paris2008.pdf" target="_blank">the date stamped PDF with the original code can be found here</a>).
        Ongoing efforts since then have resulted in a more robust version of the code, which is openly available.
      </p>
    </div>
    <h2 class="aboutpage-subtitle text-left mb-3 mt-lg-6" id="more-than-just-code">What does it do?</h2>
    <div class="col-md-12 animate-out mb-2">
      <p class="alt-lead text-gray text-justify-between col-md-15 mx-auto" style="text-align: justify; font-size: 0.875em;">
      OSeMOSYS identifies the most cost-effective approach for capacity expansion and energy generation,
      focusing on minimizing discounted system costs. It meets exogenously defined final energy demands while considering existing technological attributes
      such as costs, lifetimes, and system constraints like greenhouse gas emission limits, renewable energy targets, and investment caps.
      </p>
    </div>
    <h2 class="aboutpage-subtitle text-left mb-3 mt-lg-6" id="more-than-just-code">What type of energy system can you model?</h2>
    <div class="col-md-12 animate-out mb-2">
      <p class="alt-lead text-gray text-justify-between col-md-15 mx-auto" style="text-align: justify; font-size: 0.875em;">
      You can model any type of energy system, starting from primary sources (e.g., coal mines), through fuel processing (e.g., refineries, electrolyzers),
      to end-use technologies (e.g., electric vehicles, industrial furnaces). Additionally, you can represent broader systems, such as land use and water,
      to create integrated assessment models.
    </p>
    <h2 class="aboutpage-subtitle text-left mb-3 mt-lg-6" id="more-than-just-code">Who is the target audience?</h2>
    <div class="col-md-12 animate-out mb-2">
      <p class="alt-lead text-gray text-justify-between col-md-15 mx-auto" style="text-align: justify; font-size: 0.875em;">
      OSeMOSYS is suitable for everyone working in the energy field, including governmental bodies, industry players, and academia.
      The framework has proven its usefulness across a wide range of applications, from master's theses
      (<a href="https://doi.org/10.1016/j.rser.2024.114555" target="_blank">Hersaputri et al., 2024</a>)
      to national decarbonization plans
      (<a href="https://doi.org/10.1016/j.enpol.2020.111089" target="_blank">Godínez-Zamora et al., 2020</a>).
    </p>
    <h2 class="aboutpage-subtitle text-left mb-3 mt-lg-6" id="more-than-just-code">What outcomes can you obtain?</h2>
    <div class="col-md-12 animate-out mb-2">
      <p class="alt-lead text-gray text-justify-between col-md-15 mx-auto" style="text-align: justify; font-size: 0.875em;">
      Key outputs from OSeMOSYS include system costs, installed capacities, energy generation, and emissions.
      Results can be further broken down by type (e.g., investment, operating, penalties), by year, by region, by sector, and by technology,
      depending on the model design.
      </p>
    </div>
    <h2 class="aboutpage-subtitle text-left mb-3 mt-lg-6" id="more-than-just-code">How can you start with OSeMOSYS?</h2>
    <div class="col-md-12 animate-out mb-2">
      <p class="alt-lead text-gray text-justify-between col-md-15 mx-auto" style="text-align: justify; font-size: 0.875em;">
      Go ahead and download our Modelling User Interface for OSeMOSYS (MUIO).
      MUIO is an all-in-one application that lets you manage data, run models, and visualize results seamlessly.
      For training on how to use both the model and the interface, you can take our free, certified course at the Open University
      <a href="https://www.open.edu/openlearncreate/course/view.php?id=6824" target="_blank">here</a>.
      To download the interface and learn more, please visit
      <a href="https://osemosys.readthedocs.io/en/latest/MUIO.html" target="_blank">this site</a>.
      </p>
    </div>
    <h2 class="aboutpage-subtitle text-left mb-3 mt-lg-6" id="more-than-just-code">How can you contribute?</h2>
    <div class="col-md-12 animate-out mb-2">
      <p class="alt-lead text-gray text-justify-between col-md-15 mx-auto" style="text-align: justify; font-size: 0.875em;">
      OSeMOSYS is currently available in three languages: (1) GNUMathprog, (2) Python, and (3) GAMS.
      Versions (1) and (2) can be run fully open-source, from source to solver.
      All code bases are maintained on <a href="https://github.com/OSeMOSYS" target="_blank">GitHub</a>, and contributions from the community are welcome.
      </p>
    </div>
  </div>
</div>

<!-- Icon Links -->
<div class="icon-links-section">
  <div class="icon-links-wrapper">
    <!-- GitHub Repository -->
    <div class="icon-link-item">
      <a href="https://github.com/OSeMOSYS" target="_blank">
        <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="80" height="80" alt="GitHub" />
        <h3 class="aboutpage-subtitle text-primary">GitHub Repository</h3>
      </a>
    </div>

    <!-- Model Documentation -->
    <div class="icon-link-item">
      <a href="https://osemosys.readthedocs.io/en/latest/index.html" target="_blank">
        <img src="/assets/img/Rtdicon.png" width="80" height="80" alt="ReadTheDocs icon" />
        <h3 class="aboutpage-subtitle text-primary">Model Documentation</h3>
      </a>
    </div>
  </div>
</div>

  

<style>
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
.alt-h3 {
  font-size: 1.15rem;
}
@media (min-width: 768px) {
  .row.justify-content-center > .col-md-4 {
    margin-bottom: 2rem;
  }
}
</style>


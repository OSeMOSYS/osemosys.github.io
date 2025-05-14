---
theme: jekyll-theme-primer
layout: sub-page
title: OSeMOSYS
permalink: /about/
---
<section class="bg-gray-light container-lg p-responsive py-4 py-md-6 my-lg-6 fade-in-center">
  <div class="text-center fade-in-center">
 <h2 class="alt-h2 mb-4">About OSeMOSYS </h2>

    <p class="alt-lead text-gray text-justify">
      <strong>OSeMOSYS</strong> is a full-fledged systems optimization model for long-run energy planning.
      The initial working code of OSeMOSYS was published in 2008 in a presentation at the International Energy Workshop in Paris at the IEA
      (<a href="https://www.osemosys.org/uploads/1/8/5/0/18504136/osemosys_iea_paris2008.pdf" target="_blank">the date stamped PDF with the original code can be found here</a>).
      Ongoing efforts since then have resulted in a more robust version of the code, which is openly available.
    </p>

    <h3 class="alt-h3 mt-5">What does it do?</h3>
    <p class="text-gray text-justify">
      OSeMOSYS identifies the most cost-effective approach for capacity expansion and energy generation,
      focusing on minimizing discounted system costs. It meets exogenously defined final energy demands while considering existing technological attributes
      such as costs, lifetimes, and system constraints like greenhouse gas emission limits, renewable energy targets, and investment caps.
    </p>

    <h3 class="alt-h3 mt-5">What type of energy system can you model?</h3>
    <p class="text-gray text-justify">
      You can model any type of energy system, starting from primary sources (e.g., coal mines), through fuel processing (e.g., refineries, electrolyzers),
      to end-use technologies (e.g., electric vehicles, industrial furnaces). Additionally, you can represent broader systems, such as land use and water,
      to create integrated assessment models.
    </p>

    <h3 class="alt-h3 mt-5">Who is the target audience?</h3>
    <p class="text-gray text-justify">
      OSeMOSYS is suitable for everyone working in the energy field, including governmental bodies, industry players, and academia.
      The framework has proven its usefulness across a wide range of applications, from master's theses
      (<a href="https://doi.org/10.1016/j.rser.2024.114555" target="_blank">Hersaputri et al., 2024</a>)
      to national decarbonization plans
      (<a href="https://doi.org/10.1016/j.enpol.2020.111089" target="_blank">Godínez-Zamora et al., 2020</a>).
    </p>

    <h3 class="alt-h3 mt-5">What outcomes can you obtain?</h3>
    <p class="text-gray text-justify">
      Key outputs from OSeMOSYS include system costs, installed capacities, energy generation, and emissions.
      Results can be further broken down by type (e.g., investment, operating, penalties), by year, by region, by sector, and by technology,
      depending on the model design.
    </p>

    <h3 class="alt-h3 mt-5">How can you start with OSeMOSYS?</h3>
    <p class="text-gray text-justify">
      Go ahead and download our Modelling User Interface for OSeMOSYS (MUIO).
      MUIO is an all-in-one application that lets you manage data, run models, and visualize results seamlessly.
      For training on how to use both the model and the interface, you can take our free, certified course at the Open University
      <a href="https://www.open.edu/openlearncreate/course/view.php?id=6824" target="_blank">here</a>.
      To download the interface and learn more, please visit
      <a href="https://osemosys.readthedocs.io/en/latest/MUIO.html" target="_blank">this site</a>.
    </p>

    <h3 class="alt-h3 mt-5">How can you contribute?</h3>
    <p class="text-gray text-justify">
      OSeMOSYS is currently available in three languages: (1) GNUMathprog, (2) Python, and (3) GAMS.
      Versions (1) and (2) can be run fully open-source, from source to solver.
      All code bases are maintained on <a href="https://github.com/OSeMOSYS" target="_blank">GitHub</a>, and contributions from the community are welcome.
    </p>
  </div>
  
<!-- Icon Links -->
<div class="container text-center my-5">
  <div class="row justify-content-center">

    <!-- GitHub Repository -->
    <div class="col-md-4 d-flex flex-column align-items-center">
      <a href="https://github.com/OSeMOSYS" target="_blank" style="text-decoration: none;">
        <svg height="80" viewBox="0 0 16 16" version="1.1" width="80" aria-hidden="true" class="mb-2">
          <path fill="#000000" fill-rule="evenodd"
            d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 
            5.47 7.59.4.07.55-.17.55-.38 
            0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94
            -.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52
            -.01-.53.63-.01 1.08.58 1.23.82
            .72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07
            -1.78-.2-3.64-.89-3.64-3.95 
            0-.87.31-1.59.82-2.15-.08-.2-.36-1.01.08-2.11 
            0 0 .67-.21 2.2.82.64-.18 1.32-.27 
            2-.27s1.36.09 2 .27c1.53-1.04 2.2-.82 
            2.2-.82.44 1.1.16 1.91.08 2.11.51.56.82 
            1.27.82 2.15 0 3.07-1.87 3.75-3.65 
            3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 
            2.2 0 .21.15.46.55.38A8.013 8.013 
            0 0016 8c0-4.42-3.58-8-8-8z">
          </path>
        </svg>
        <h3 class="alt-h3 text-primary mt-2">Our GitHub Repository</h3>
      </a>
    </div>

    <!-- Model Documentation -->
    <div class="col-md-4 d-flex flex-column align-items-center">
      <a href="https://osemosys.readthedocs.io/en/latest/index.html" target="_blank" style="text-decoration: none;">
        <img src="/assets/img/Rtdicon.png" width="80" height="80" alt="ReadTheDocs icon" class="mb-2" />
        <h3 class="alt-h3 text-primary mt-2">Our Model Documentation</h3>
      </a>
    </div>

  </div>
</div>

  
</section>

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


---
theme: jekyll-theme-primer
layout: sub-page
title: OSeMOSYS
permalink: /contact/
---

<section class="bg-gray-light py-5 fade-in-center">
  <div class="container-lg p-responsive">
    <div class="text-center mb-5">
      <h2 class="alt-h2 mb-4">Get Involved</h2>
    </div>

    <!-- Section 1: Community Engagement -->
    <div class="involvement-section mb-5">
      <h3 class="section-title text-center mb-4">💬 Join Our Community</h3>
      
      <!-- Discourse Link at the start -->
      <div class="text-center mb-4">
        <a href="https://forum.u4ria.org/" target="_blank" class="btn btn-primary btn-lg">
          Visit the Discourse Forum →
        </a>
      </div>

      <p class="text-center lead mb-4">
        Join other OSeMOSYS practitioners by becoming part of our Discourse community—a dedicated online space for collaboration, learning, and sharing.
      </p>

      <!-- Centered platform benefits -->
      <div class="text-center mb-4">
        <h4 class="platform-benefits-title">This platform allows members to:</h4>
      </div>

      <div class="benefits-container">
        <div class="benefit-card text-center">
          {% octicon tools height:40 class:"fill-blue mb-3" aria-label:tools %}
          <h5>Troubleshoot Models</h5>
          <p class="text-gray">Share challenges, seek advice, and collaborate with other users to overcome technical hurdles in your OSeMOSYS applications.</p>
        </div>
        <div class="benefit-card text-center">
          {% octicon checklist height:40 class:"fill-blue mb-3" aria-label:checklist %}
          <h5>Share Publications</h5>
          <p class="text-gray">Showcase your research, explore the work of others, and contribute to the expanding body of knowledge on integrated systems modeling.</p>
        </div>
        <div class="benefit-card text-center">
          <img src="/assets/img/sparkles.svg" height="40" class="mb-3" alt="Events">
          <h5>Stay Updated on Events</h5>
          <p class="text-gray">Be the first to know about upcoming capacity-building workshops, webinars, and networking opportunities.</p>
        </div>
      </div>
    </div>

    <!-- Section 2: Technical Contributions -->
    <div class="involvement-section">
      <h3 class="section-title text-center mb-4">🛠️ Contribute to Development</h3>
      
      <div class="github-container">
        <div class="unified-github-card text-center">
          <a href="https://github.com/OSeMOSYS" target="_blank" class="github-link">
            <svg height="80" viewBox="0 0 16 16" version="1.1" width="80" aria-hidden="true" class="mb-3">
              <path fill-rule="evenodd" fill="#0366d6" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 
              6.53 5.47 7.59.4.07.55-.17.55-.38 
              0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52
              -.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 
              2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 
              0-.87.31-1.59.82-2.15-.08-.2-.36-1.01.08-2.11 
              0 0 .67-.21 2.2.82.64-.18 1.32-.27 
              2-.27s1.36.09 2 .27c1.53-1.04 2.2-.82 
              2.2-.82.44 1.1.16 1.91.08 2.11.51.56.82 
              1.27.82 2.15 0 3.07-1.87 3.75-3.65 
              3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 
              2.2 0 .21.15.46.55.38A8.013 8.013 
              0 0016 8c0-4.42-3.58-8-8-8z"></path>
            </svg>
            <h4 class="text-primary mt-2 mb-4">Contribute to OSeMOSYS on GitHub</h4>
          </a>
          
          <div class="contribution-section text-left">
            <h5>Contribute to This Website</h5>
            <p>
              Want to share your OSeMOSYS-related work, training, or resources? We welcome external contributions to this site!
            </p>
            <h6>How to contribute:</h6>
            <ul class="contribution-steps">
              <li>Fork the repository: <a href="https://github.com/OSeMOSYS" target="_blank">github.com/OSeMOSYS</a></li>
              <li>Edit or add content (e.g. publications, capacity building activities)</li>
              <li>Submit a pull request</li>
              <li>A site administrator will review and approve if appropriate</li>
            </ul>
            <p class="text-muted">
              This website exists to grow a self-sustaining OSeMOSYS community—open to all. Let's make sure your work is visible and contributes to the global ecosystem!
            </p>
          </div>
        </div>
      </div>
    </div>

  </div>
</section>

<style>
/* Enhanced Get Involved Page Styling */
.involvement-section {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease;
}

.involvement-section:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
}

.section-title {
  color: #0366d6;
  font-size: 1.5rem;
  font-weight: 600;
  margin-bottom: 1.5rem;
  padding-bottom: 0.5rem;
  border-bottom: 2px solid #e1e4e8;
}

.platform-benefits-title {
  color: #24292e;
  font-size: 1.2rem;
  font-weight: 500;
  margin-bottom: 2rem;
}

.benefits-container {
  display: flex;
  justify-content: center;
  align-items: stretch;
  gap: 2rem;
  flex-wrap: wrap;
  margin: 0 auto;
  max-width: 900px;
}

.benefit-card {
  background: #f8f9fa;
  padding: 2rem 1rem;
  border-radius: 8px;
  transition: all 0.3s ease;
  border: 1px solid #e1e4e8;
  flex: 1;
  min-width: 250px;
  max-width: 280px;
}

.benefit-card:hover {
  background: white;
  transform: translateY(-4px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.benefit-card h5 {
  color: #24292e;
  font-weight: 600;
  margin-bottom: 1rem;
}

.github-container {
  display: flex;
  justify-content: center;
  margin: 0 auto;
  max-width: 600px;
}

.unified-github-card {
  background: #f8f9fa;
  padding: 2rem;
  border-radius: 8px;
  transition: all 0.3s ease;
  border: 1px solid #e1e4e8;
  border-left: 4px solid #0366d6;
  width: 100%;
}

.unified-github-card:hover {
  background: white;
  transform: translateY(-4px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.contribution-section {
  margin-top: 2rem;
  padding-top: 2rem;
  border-top: 1px solid #e1e4e8;
}

.github-link {
  text-decoration: none;
  transition: all 0.3s ease;
  display: inline-block;
}

.github-link:hover {
  transform: scale(1.05);
  text-decoration: none;
}

.github-link svg {
  transition: all 0.3s ease;
}

.github-link:hover svg {
  transform: scale(1.1);
}

.unified-github-card h5 {
  color: #24292e;
  font-weight: 600;
  margin-bottom: 1rem;
}

.unified-github-card h6 {
  color: #0366d6;
  font-weight: 600;
  margin-top: 1rem;
  margin-bottom: 0.5rem;
}

.contribution-steps {
  list-style: none;
  padding-left: 0;
}

.contribution-steps li {
  padding: 0.5rem 0;
  padding-left: 1.5rem;
  position: relative;
}

.contribution-steps li::before {
  content: "→";
  position: absolute;
  left: 0;
  color: #0366d6;
  font-weight: bold;
}

.contribution-steps a {
  color: #0366d6;
  text-decoration: none;
}

.contribution-steps a:hover {
  text-decoration: underline;
}

.btn-primary {
  background-color: #0366d6;
  border-color: #0366d6;
  padding: 0.75rem 1.5rem;
  font-weight: 500;
  transition: all 0.3s ease;
}

.btn-primary:hover {
  background-color: #0256c7;
  border-color: #0256c7;
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(3, 102, 214, 0.3);
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

/* Responsive design */
@media (max-width: 768px) {
  .involvement-section {
    padding: 1.5rem;
  }
  
  .benefits-container, .github-container {
    flex-direction: column;
    gap: 1rem;
    max-width: 100%;
  }
  
  .benefit-card, .unified-github-card {
    padding: 1.5rem 1rem;
    min-width: auto;
    max-width: 100%;
    flex: none;
  }
  
  .contribution-section {
    margin-top: 1.5rem;
    padding-top: 1.5rem;
  }
  
  .section-title {
    font-size: 1.25rem;
  }
}
</style>
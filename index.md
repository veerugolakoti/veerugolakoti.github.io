---
layout: home
title: "Home"
---

<!-- Global Styles & Scripts -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
<script src="https://cdn.tailwindcss.com"></script>
<style>
  body { font-family: 'Poppins', sans-serif; }
  nav { backdrop-filter: blur(12px); }
  .hero { background: linear-gradient(135deg, #4F46E5 0%, #3B82F6 100%); }
  .btn-primary { background-color: #3B82F6; color: white; }
  .btn-secondary { border: 2px solid white; color: white; }
  .btn-secondary:hover { background-color: rgba(255,255,255,0.1); }
  .reveal { opacity: 0; transform: translateY(20px); transition: all 0.6s ease-out; }
  .reveal.active { opacity: 1; transform: translateY(0); }
</style>
<script>
  // Scroll reveal
  document.addEventListener('scroll', () => {
    document.querySelectorAll('.reveal').forEach(el => {
      if (el.getBoundingClientRect().top < window.innerHeight - 100) {
        el.classList.add('active');
      }
    });
  });
  function menuToggle() {
    document.getElementById('mobileMenu').classList.toggle('hidden');
  }
</script>

<nav class="fixed w-full z-30 top-0 bg-white bg-opacity-50 px-8 py-4">
  <div class="flex items-center justify-between max-w-6xl mx-auto">
    <a href="#home" class="text-2xl font-bold text-indigo-600">VeeruAI</a>
    <ul class="hidden md:flex space-x-8 text-gray-800">
      <li><a href="#about" class="hover:text-indigo-500">About</a></li>
      <li><a href="#skills" class="hover:text-indigo-500">Skills</a></li>
      <li><a href="#journey" class="hover:text-indigo-500">Journey</a></li>
      <li><a href="#projects" class="hover:text-indigo-500">Projects</a></li>
      <li><a href="#insights" class="hover:text-indigo-500">Insights</a></li>
      <li><a href="#contact" class="hover:text-indigo-500">Contact</a></li>
    </ul>
    <button class="md:hidden text-gray-800" onclick="menuToggle()">
      <!-- hamburger -->
      <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/></svg>
    </button>
  </div>
  <div id="mobileMenu" class="hidden md:hidden bg-white px-8 py-4">
    <a href="#about" class="block py-2">About</a>
    <a href="#skills" class="block py-2">Skills</a>
    <a href="#journey" class="block py-2">Journey</a>
    <a href="#projects" class="block py-2">Projects</a>
    <a href="#insights" class="block py-2">Insights</a>
    <a href="#contact" class="block py-2">Contact</a>
  </div>
</nav>

<header id="home" class="hero h-screen flex items-center justify-center text-center text-white px-4">
  <div>
    <h1 class="text-5xl md:text-7xl font-bold mb-4 reveal">Building Tomorrow’s<br>Enterprise Solutions</h1>
    <p class="text-lg md:text-2xl mb-8 reveal" style="transition-delay:0.2s;">Java Microservices · GovTech Platforms · Generative AI</p>
    <div class="space-x-4 reveal" style="transition-delay:0.4s;">
      <a href="#projects" class="btn-primary px-6 py-3 rounded-full">View Projects</a>
      <a href="#contact" class="btn-secondary px-6 py-3 rounded-full">Get In Touch</a>
    </div>
  </div>
</header>

<main class="pt-24">
  <section id="about" class="max-w-4xl mx-auto px-4 py-20 reveal">
    <div class="text-center">
      <img src="assets/images/Veeru_AI.png" alt="Profile" class="w-40 h-40 mx-auto rounded-full shadow-lg mb-6">
      <h2 class="text-3xl font-bold text-indigo-600 mb-4">Veeranjaneyulu Golakoti</h2>
      <p class="text-gray-700 mb-4">Enterprise software leader with <strong>13+ years</strong> in Java microservices, government platforms like ACRA, and cloud-native solutions.</p>
      <p class="text-gray-700 mb-4">Associate Manager at Accenture Singapore, specializing in secure APIs, DevOps automation, and high-availability architectures.</p>
      <p class="text-gray-700 mb-4">Now pioneering <strong>Generative AI</strong> – LLM agents, RAG workflows, and next-gen enterprise intelligence.</p>
    </div>
  </section>

  <section id="skills" class="bg-indigo-50 py-20">
    <div class="max-w-6xl mx-auto px-4 reveal">
      <h2 class="text-3xl font-bold text-center text-indigo-600 mb-12">Technical Expertise</h2>
      <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition">
          <h3 class="font-semibold mb-2">Languages & Frameworks</h3>
          <p>Java, Spring Boot, Hibernate, JPA<br>Python, Node.js</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition">
          <h3 class="font-semibold mb-2">Cloud & DevOps</h3>
          <p>AWS, Azure, Docker, Kubernetes<br>Jenkins, Terraform</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition">
          <h3 class="font-semibold mb-2">Security & Integration</h3>
          <p>OAuth2, SAML2, Spring Security<br>REST & GraphQL APIs</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition">
          <h3 class="font-semibold mb-2">Generative AI</h3>
          <p>LLM Integration, RAG, Agentic Systems<br>Prompt Engineering, Model Serving</p>
        </div>
      </div>
    </div>
  </section>

  <section id="journey" class="py-20 reveal">
    <div class="max-w-4xl mx-auto px-4">
      <h2 class="text-3xl font-bold text-center text-indigo-600 mb-12">Professional Journey</h2>
      <ul class="space-y-8">
        <li class="flex items-start space-x-4">
          <div class="mt-1 w-3 h-3 bg-indigo-600 rounded-full"></div>
          <div>
            <h4 class="font-semibold">Associate Manager, Accenture Singapore <span class="text-gray-600">(2021–Present)</span></h4>
            <p class="text-gray-700">Leading microservices & cloud teams, driving AI PoCs, and automating DevOps pipelines.</p>
          </div>
        </li>
        <li class="flex items-start space-x-4">
          <div class="mt-1 w-3 h-3 bg-indigo-600 rounded-full"></div>
          <div>
            <h4 class="font-semibold">Senior Java Developer, Accenture Singapore <span class="text-gray-600">(2018–2021)</span></h4>
            <p class="text-gray-700">Architected ACRA platform, optimized throughput, and enforced security standards.</p>
          </div>
        </li>
        <li class="flex items-start space-x-4">
          <div class="mt-1 w-3 h-3 bg-indigo-600 rounded-full"></div>
          <div>
            <h4 class="font-semibold">Java Developer, Accenture India <span class="text-gray-600">(2012–2018)</span></h4>
            <p class="text-gray-700">Built enterprise integration solutions and financial services APIs.</p>
          </div>
        </li>
      </ul>
    </div>
  </section>

  <section id="projects" class="bg-white py-20 reveal">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-3xl font-bold text-center text-indigo-600 mb-12">Featured Projects</h2>
      <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="group relative overflow-hidden rounded-lg shadow-lg">
          <img src="https://veerugolakoti.github.io/assets/project-acra.jpg" alt="ACRA" class="w-full h-56 object-cover group-hover:scale-105 transition">
          <div class="absolute inset-0 bg-black bg-opacity-50 opacity-0 group-hover:opacity-100 transition p-6 flex flex-col justify-end">
            <h3 class="text-white font-semibold mb-2">ACRA Regulatory Platform</h3>
            <p class="text-gray-200 text-sm mb-4">High-throughput microservices for government workflows.</p>
            <a href="#" class="text-indigo-300 hover:underline">View Details →</a>
          </div>
        </div>
        <div class="group relative overflow-hidden rounded-lg shadow-lg">
          <img src="https://veerugolakoti.github.io/assets/project-ai.jpg" alt="AI PoC" class="w-full h-56 object-cover group-hover:scale-105 transition">
          <div class="absolute inset-0 bg-black bg-opacity-50 opacity-0 group-hover:opacity-100 transition p-6 flex flex-col justify-end">
            <h3 class="text-white font-semibold mb-2">Generative AI PoC</h3>
            <p class="text-gray-200 text-sm mb-4">LLM integration for automated reporting.</p>
            <a href="#" class="text-indigo-300 hover:underline">View Details →</a>
          </div>
        </div>
        <div class="group relative overflow-hidden rounded-lg shadow-lg">
          <img src="https://veerugolakoti.github.io/assets/project-devops.jpg" alt="DevOps" class="w-full h-56 object-cover group-hover:scale-105 transition">
          <div class="absolute inset-0 bg-black bg-opacity-50 opacity-0 group-hover:opacity-100 transition p-6 flex flex-col justify-end">
            <h3 class="text-white font-semibold mb-2">DevOps Automation</h3>
            <p class="text-gray-200 text-sm mb-4">Terraform & Jenkins for zero-downtime.</p>
            <a href="#" class="text-indigo-300 hover:underline">View Details →</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="insights" class="bg-indigo-50 py-20 reveal">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-3xl font-bold text-center text-indigo-600 mb-12">Latest Insights</h2>
      <div class="grid md:grid-cols-2 gap-8">
        <article class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition">
          <h4 class="font-semibold mb-2">Driving AI in Enterprise</h4>
          <p class="text-gray-700 text-sm mb-4">Integrating LLMs with microservices and RAG patterns.</p>
          <a href="https://veerugolakoti.github.io/insights/ai-enterprise" class="text-indigo-600 hover:underline">Read more →</a>
        </article>
        <article class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition">
          <h4 class="font-semibold mb-2">Secure API Design</h4>
          <p class="text-gray-700 text-sm mb-4">Best practices for OAuth2 & SAML2 in microservices.</p>
          <a href="https://veerugolakoti.github.io/insights/secure-api" class="text-indigo-600 hover:underline">Read more →</a>
        </article>
      </div>
    </div>
  </section>

  <section id="contact" class="py-20 reveal">
    <div class="max-w-md mx-auto px-4 text-center">
      <h2 class="text-3xl font-bold text-indigo-600 mb-6">Let’s Build Something Together</h2>
      <form action="mailto:veerugolakoti@gmail.com" method="post" class="space-y-4">
        <input type="text" name="name" placeholder="Your Name" class="w-full p-3 rounded-lg border-gray-300 focus:outline-indigo-500">
        <input type="email" name="email" placeholder="Your Email" class="w-full p-3 rounded-lg border-gray-300 focus:outline-indigo-500">
        <textarea name="message" rows="4" placeholder="Your Message" class="w-full p-3 rounded-lg border-gray-300 focus:outline-indigo-500"></textarea>
        <button type="submit" class="w-full py-3 btn-primary rounded-lg">Send Message</button>
      </form>
      <div class="mt-6 flex justify-center space-x-6">
        <a href="https://linkedin.com/in/veerugolakoti" target="_blank"><img src="assets/images/linkedin.svg" alt="LinkedIn" class="w-6 h-6 filter hover:opacity-75"></a>
        <a href="https://github.com/veerugolakoti" target="_blank"><img src="assets/images/github.svg" alt="GitHub" class="w-6 h-6 filter hover:opacity-75"></a>
      </div>
    </div>
  </section>
</main>

<footer class="bg-gray-200 text-center py-6">
  <p class="text-gray-700 text-sm">&copy; 2025 Veeranjaneyulu Golakoti. All rights reserved.</p>
</footer>

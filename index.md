---
layout: home
title: "Welcome"
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Veeranjaneyulu Golakoti | Enterprise Solutions & Generative AI</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    .about-bg { background: rgba(255,255,255,0.8); backdrop-filter: blur(10px); }
    .profile-img { filter: brightness(1.1) contrast(1.2); }
  </style>
</head>
<body class="bg-gray-50 text-gray-800 leading-relaxed">

  <!-- Navbar -->
  <nav class="bg-white shadow-md fixed w-full z-10">
    <div class="container mx-auto px-6 py-4 flex justify-between items-center">
      <a href="#home" class="text-xl font-bold">VG Solutions</a>
      <ul class="flex space-x-6">
        <li><a href="#about" class="hover:text-blue-600">About</a></li>
        <li><a href="#skills" class="hover:text-blue-600">Skills</a></li>
        <li><a href="#journey" class="hover:text-blue-600">Journey</a></li>
        <li><a href="#projects" class="hover:text-blue-600">Work</a></li>
        <li><a href="#insights" class="hover:text-blue-600">Insights</a></li>
        <li><a href="#contact" class="hover:text-blue-600">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Hero -->
  <header id="home" class="h-screen bg-gradient-to-r from-blue-500 to-indigo-600 flex items-center pt-16">
    <div class="container mx-auto px-6 text-white">
      <h1 class="text-4xl md:text-6xl font-extrabold leading-tight">Building Tomorrow’s Enterprise Solutions Today</h1>
      <p class="mt-4 text-lg md:text-xl">Java Microservices | GovTech Platforms | Generative AI Innovator</p>
      <div class="mt-6">
        <a href="#projects" class="px-6 py-3 bg-white text-blue-600 font-medium rounded shadow hover:bg-gray-100 transition">View My Work</a>
        <a href="#contact" class="ml-4 px-6 py-3 border border-white text-white rounded hover:bg-white hover:text-blue-600 transition">Get In Touch</a>
      </div>
    </div>
  </header>

  <!-- About -->
  <section id="about" class="py-20">
    <div class="container mx-auto px-6 md:flex md:items-center">
      <div class="md:w-1/2 p-6 about-bg rounded-lg shadow-lg">
        <h2 class="text-3xl font-semibold mb-4">About Me</h2>
        <p class="mb-4"><strong>Veeranjaneyulu Golakoti</strong>—enterprise software leader with <strong>13+ years</strong> of experience in Java microservices, Hibernate/JPA, and government-scale platforms like ACRA.</p>
        <p class="mb-4">As Associate Manager at Accenture Singapore, I architect secure, scalable APIs with Spring Boot, enforce OAuth2/SAML2 standards, and streamline deployments on AWS ECS, Lambda, Azure, Kubernetes, and Docker.</p>
        <p class="mb-4">Passionate about DevOps—Jenkins pipelines, Terraform IaC, and zero-downtime strategies—and innovating with <strong>Generative AI</strong>: LLM bots, RAG workflows, and agentic systems for next-gen enterprise solutions.</p>
        <p><strong>Location:</strong> Singapore</p>
      </div>
      <div class="md:w-1/2 p-6 flex justify-center">
        <img src="/assets/images/Veeru_AI.png" alt="Veeranjaneyulu Golakoti" class="w-48 h-48 md:w-64 md:h-64 rounded-full profile-img shadow-lg">
      </div>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills" class="py-20 bg-white">
    <div class="container mx-auto px-6">
      <h2 class="text-3xl font-semibold mb-8 text-center">Technical Expertise</h2>
      <div class="grid md:grid-cols-2 gap-8 text-center">
        <div>
          <h3 class="text-xl font-semibold mb-2">Languages & Frameworks</h3>
          <p>Java, Spring Boot, Hibernate, JPA, MyBatis</p>
          <p>Python (AI Prototyping), Node.js</p>
        </div>
        <div>
          <h3 class="text-xl font-semibold mb-2">Cloud & DevOps</h3>
          <p>AWS (ECS, Lambda, S3), Azure</p>
          <p>Docker, Kubernetes, Jenkins, Terraform</p>
        </div>
        <div>
          <h3 class="text-xl font-semibold mb-2">Security & Integration</h3>
          <p>OAuth2, SAML2, Spring Security</p>
          <p>REST & GraphQL APIs, Microservices</p>
        </div>
        <div>
          <h3 class="text-xl font-semibold mb-2">Generative AI</h3>
          <p>LLM Integration, RAG, Agentic Systems</p>
          <p>Prompt Engineering, Databricks Model Serving</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Journey -->
  <section id="journey" class="py-20">
    <div class="container mx-auto px-6">
      <h2 class="text-3xl font-semibold mb-8 text-center">Professional Journey</h2>
      <ul class="border-l-2 border-blue-600 ml-4">
        <li class="mb-6">
          <span class="inline-block w-4 h-4 bg-blue-600 rounded-full -ml-2"></span>
          <div class="ml-6">
            <h4 class="font-semibold">Associate Manager, Accenture Singapore</h4>
            <span class="text-sm text-gray-600">2021 – Present</span>
            <p class="mt-2 text-gray-700 text-sm">Leading Java microservices & cloud teams, driving AI PoCs, and DevOps pipelines.</p>
          </div>
        </li>
        <li class="mb-6">
          <span class="inline-block w-4 h-4 bg-blue-600 rounded-full -ml-2"></span>
          <div class="ml-6">
            <h4 class="font-semibold">Senior Java Developer, Accenture Singapore</h4>
            <span class="text-sm text-gray-600">2018 – 2021</span>
            <p class="mt-2 text-gray-700 text-sm">Architected ACRA regulatory platform, optimized throughput, and enforced security standards.</p>
          </div>
        </li>
        <li>
          <span class="inline-block w-4 h-4 bg-blue-600 rounded-full -ml-2"></span>
          <div class="ml-6">
            <h4 class="font-semibold">Java Developer, Accenture India</h4>
            <span class="text-sm text-gray-600">2012 – 2018</span>
            <p class="mt-2 text-gray-700 text-sm">Built enterprise integration solutions, financial services APIs, and performance tuning.</p>
          </div>
        </li>
      </ul>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="py-20 bg-white">
    <div class="container mx-auto px-6">
      <h2 class="text-3xl font-semibold mb-8 text-center">Featured Projects</h2>
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="bg-gray-100 rounded-lg overflow-hidden shadow hover:shadow-lg transition">
          <img src="https://veerugolakoti.github.io/assets/project-acra.jpg" alt="ACRA Regulatory Platform" class="w-full h-40 object-cover">
          <div class="p-6">
            <h3 class="text-xl font-semibold mb-2">ACRA Regulatory Platform</h3>
            <p class="text-gray-600 text-sm mb-4">High-throughput Java microservices for government regulatory workflows.</p>
            <a href="#" class="text-blue-600 font-medium hover:underline">View Details →</a>
          </div>
        </div>
        <div class="bg-gray-100 rounded-lg overflow-hidden shadow hover:shadow-lg transition">
          <img src="https://veerugolakoti.github.io/assets/project-ai.jpg" alt="Generative AI PoC" class="w-full h-40 object-cover">
          <div class="p-6">
            <h3 class="text-xl font-semibold mb-2">Generative AI PoC</h3>
            <p class="text-gray-600 text-sm mb-4">Integrated LLMs with backend services for automated report generation.</p>
            <a href="#" class="text-blue-600 font-medium hover:underline">View Details →</a>
          </div>
        </div>
        <div class="bg-gray-100 rounded-lg overflow-hidden shadow hover:shadow-lg transition">
          <img src="https://veerugolakoti.github.io/assets/project-devops.jpg" alt="DevOps Pipeline" class="w-full h-40 object-cover">
          <div class="p-6">
            <h3 class="text-xl font-semibold mb-2">DevOps Pipeline Automation</h3>
            <p class="text-gray-600 text-sm mb-4">Terraform + Jenkins IaC for zero-downtime deployments across environments.</p>
            <a href="#" class="text-blue-600 font-medium hover:underline">View Details →</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Insights -->
  <section id="insights" class="py-20">
    <div class="container mx-auto px-6">
      <h2 class="text-3xl font-semibold mb-8 text-center">Latest Insights</h2>
      <div class="space-y-6 max-w-3xl mx-auto">
        <article class="bg-gray-50 p-6 rounded-lg shadow">
          <h4 class="text-2xl font-semibold mb-2">Driving AI in Enterprise: Best Practices</h4>
          <p class="text-gray-600 text-sm mb-4">Exploring integration of LLMs with existing microservices, security considerations, and RAG patterns.</p>
          <a href="https://veerugolakoti.github.io/insights/ai-enterprise" class="text-blue-600 hover:underline">Read more →</a>
        </article>
        <article class="bg-gray-50 p-6 rounded-lg shadow">
          <h4 class="text-2xl font-semibold mb-2">Secure API Design with OAuth2 & SAML2</h4>
          <p class="text-gray-600 text-sm mb-4">Deep dive into best practices for implementing OAuth2 and SAML2 in microservices.</p>
          <a href="https://veerugolakoti.github.io/insights/secure-api" class="text-blue-600 hover:underline">Read more →</a>
        </article>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-20 bg-blue-600 text-white">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-3xl font-semibold mb-4">Let’s Build Something Together</h2>
      <p class="mb-8">Email me at <a href="mailto:veerugolakoti@gmail.com" class="underline">veerugolakoti@gmail.com</a><br>Connect on <a href="https://linkedin.com/in/veerugolakoti" class="underline" target="_blank">LinkedIn</a> │ <a href="https://github.com/veerugolakoti" class="underline" target="_blank">GitHub</a></p>
      <form action="mailto:veerugolakoti@gmail.com" method="post" enctype="text/plain" class="max-w-md mx-auto">
        <input type="text" name="name" placeholder="Your Name" class="w-full mb-4 p-3 rounded text-gray-800" required>
        <input type="email" name="email" placeholder="Your Email" class="w-full mb-4 p-3 rounded text-gray-800" required>
        <textarea name="message" rows="4" placeholder="Your Message" class="w-full mb-4 p-3 rounded text-gray-800" required></textarea>
        <button type="submit" class="w-full py-3 bg-white text-blue-600 font-medium rounded hover:bg-gray-100 transition">Send Message</button>
      </form>
    </div>
  </section>

  <footer class="bg-gray-200 py-6 text-center text-sm text-gray-600">
    &copy; 2025 Veeranjaneyulu Golakoti. All rights reserved.
  </footer>

</body>
</html>

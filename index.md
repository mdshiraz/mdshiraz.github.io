<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mohammad Shiraz Anwar | Resume Website</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 text-gray-900 font-sans">

  <!-- Header -->
  <header class="bg-white shadow-md sticky top-0 z-20">
    <div class="max-w-6xl mx-auto flex justify-between items-center py-4 px-6">
      <h1 class="text-xl font-bold">Mohammad Shiraz Anwar</h1>
      <!-- Desktop Nav -->
      <nav class="hidden md:flex space-x-6">
        <a href="#about" class="hover:text-blue-600">About</a>
        <a href="#skills" class="hover:text-blue-600">Skills</a>
        <a href="#experience" class="hover:text-blue-600">Experience</a>
        <a href="#education" class="hover:text-blue-600">Education</a>
        <a href="#contact" class="hover:text-blue-600">Contact</a>
      </nav>
      <!-- Mobile Menu Button -->
      <button id="menu-btn" class="md:hidden text-gray-700 focus:outline-none">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
        </svg>
      </button>
    </div>
    <!-- Mobile Nav -->
    <div id="mobile-menu" class="hidden md:hidden bg-white border-t">
      <nav class="flex flex-col space-y-2 p-4">
        <a href="#about" class="hover:text-blue-600">About</a>
        <a href="#skills" class="hover:text-blue-600">Skills</a>
        <a href="#experience" class="hover:text-blue-600">Experience</a>
        <a href="#education" class="hover:text-blue-600">Education</a>
        <a href="#contact" class="hover:text-blue-600">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="text-center py-20 bg-gradient-to-r from-blue-500 to-indigo-600 text-white">
    <h2 class="text-4xl font-bold mb-4">Senior Program & Project Leader</h2>
    <p class="text-lg mb-6 max-w-2xl mx-auto">
      20+ years in technology, 10+ years in Program/Project Management — driving governance frameworks,
      agile at scale, delivery acceleration (30–40%) and throughput improvements (up to 80%) across Fintech, Travel, Media, and Consumer Tech.
    </p>
    <a href="#contact" class="bg-white text-blue-600 px-6 py-3 rounded-lg font-semibold hover:bg-gray-100 transition">
      Get in Touch
    </a>
  </section>

  <!-- About -->
  <section id="about" class="max-w-5xl mx-auto py-16 px-6">
    <h3 class="text-2xl font-bold mb-4">About Me</h3>
    <p class="text-gray-700 leading-relaxed">
      I specialize in transforming execution by introducing governance frameworks, scaling agile delivery, and leveraging AI & data for predictive insights.
      Skilled at stakeholder communication, release governance, CI/CD, and orchestrating mobile app releases across multiple verticals. 
      Proven track record with Paytm, MakeMyTrip, SWOO, and Adobe delivering measurable improvements in velocity and adoption.
    </p>
  </section>

  <!-- Skills -->
  <section id="skills" class="bg-gray-100 py-16 px-6">
    <div class="max-w-5xl mx-auto">
      <h3 class="text-2xl font-bold mb-6">Key Skills</h3>
      <div class="grid md:grid-cols-2 gap-6">
        <div class="p-4 bg-white rounded-lg shadow">
          <strong>Execution & Governance</strong>
          <ul class="list-disc ml-5 mt-2 text-gray-700">
            <li>Program/Project Management, Scrum of Scrums</li>
            <li>Release Governance, CI/CD, Process Optimization</li>
            <li>Delivery Metrics, Process Automation</li>
          </ul>
        </div>
        <div class="p-4 bg-white rounded-lg shadow">
          <strong>Collaboration & Leadership</strong>
          <ul class="list-disc ml-5 mt-2 text-gray-700">
            <li>Cross-functional leadership, Stakeholder Communication</li>
            <li>Leading with influence, Managing ambiguity</li>
          </ul>
        </div>
        <div class="p-4 bg-white rounded-lg shadow">
          <strong>Tools & Platforms</strong>
          <ul class="list-disc ml-5 mt-2 text-gray-700">
            <li>JIRA & Confluence, Slack automation</li>
            <li>Mobile App Release Orchestration (Android & iOS)</li>
          </ul>
        </div>
        <div class="p-4 bg-white rounded-lg shadow">
          <strong>Domain Expertise</strong>
          <ul class="list-disc ml-5 mt-2 text-gray-700">
            <li>Fintech & Payments, Travel, Media/Entertainment</li>
            <li>Video Streaming, Ads (CSAI/SSAI), DRM</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Experience -->
  <section id="experience" class="max-w-5xl mx-auto py-16 px-6">
    <h3 class="text-2xl font-bold mb-6">Professional Experience</h3>
    <div class="space-y-6">
      <div class="p-6 bg-white shadow rounded-lg">
        <h4 class="font-semibold">Director, Technical Program Manager — Paytm</h4>
        <p class="text-sm text-gray-600">Noida, India · Jan 2022 – Present</p>
        <ul class="list-disc ml-5 mt-2 text-gray-700">
          <li>End-to-end mobile app release management across 25+ business verticals with strict cadence.</li>
          <li>Leveraged AI tools to accelerate go-live by 33% and improve throughput by 70–80%.</li>
          <li>Delivered adoption models and dashboards forecasting ~70% accuracy.</li>
        </ul>
      </div>
      <div class="p-6 bg-white shadow rounded-lg">
        <h4 class="font-semibold">Sr. Technical Program Manager — MakeMyTrip</h4>
        <p class="text-sm text-gray-600">Gurugram, India · Oct 2019 – Dec 2022</p>
        <ul class="list-disc ml-5 mt-2 text-gray-700">
          <li>Improved commitment reliability from 36% → 58% through structured planning.</li>
          <li>Reduced dependency resolution time from 6 months → 1.5 months.</li>
        </ul>
      </div>
      <div class="p-6 bg-white shadow rounded-lg">
        <h4 class="font-semibold">Head of Technical Program Management — SWOO (Algorythma)</h4>
        <p class="text-sm text-gray-600">Abu Dhabi, UAE · Jun 2018 – Jul 2019</p>
        <ul class="list-disc ml-5 mt-2 text-gray-700">
          <li>Led roadmap planning and delivered 5+ new games in 6 months.</li>
          <li>Improved productivity by 30% through process refinements.</li>
        </ul>
      </div>
      <div class="p-6 bg-white shadow rounded-lg">
        <h4 class="font-semibold">Technical Program Manager — Adobe Systems</h4>
        <p class="text-sm text-gray-600">Noida, India · Apr 2014 – Jun 2018</p>
        <ul class="list-disc ml-5 mt-2 text-gray-700">
          <li>Enabled adoption of Adobe Primetime by Disney, NBC, Hotstar, and others.</li>
          <li>Led partner readiness for global SI vendors and delivered DRM/Ad Insertion integrations.</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Education -->
  <section id="education" class="bg-gray-100 py-16 px-6">
    <div class="max-w-5xl mx-auto">
      <h3 class="text-2xl font-bold mb-6">Education</h3>
      <div class="p-6 bg-white shadow rounded-lg">
        <h4 class="font-semibold">B.Tech, Computer Engineering</h4>
        <p class="text-sm text-gray-600">Aligarh Muslim University · 2005</p>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="max-w-5xl mx-auto py-16 px-6 text-center">
    <h3 class="text-2xl font-bold mb-4">Contact</h3>
    <p class="mb-6">Let’s connect for opportunities or collaborations.</p>
    <div class="space-y-4">
      <a href="mailto:mdshiraz@gmail.com" class="bg-blue-600 text-white px-6 py-3 rounded-lg font-semibold hover:bg-blue-700 transition">📧 mdshiraz@gmail.com</a><br/>
      <a href="tel:+919818555830" class="bg-blue-600 text-white px-6 py-3 rounded-lg font-semibold hover:bg-blue-700 transition">📞 +91 98185 55830</a><br/>
      <a href="https://linkedin.com/in/mdshiraz" target="_blank" rel="noopener" class="bg-blue-600 text-white px-6 py-3 rounded-lg font-semibold hover:bg-blue-700 transition">🔗 LinkedIn</a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="text-center py-6 bg-white border-t mt-8">
    <p class="text-sm text-gray-600">© 2025 Mohammad Shiraz Anwar. All rights reserved.</p>
  </footer>

  <script>
    const menuBtn = document.getElementById('menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');
    menuBtn.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });
  </script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Aswin Raj Sivaprakash | Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-white text-gray-800">
  <!-- Header -->
  <header class="bg-green-600 text-white p-6">
    <div class="container mx-auto flex flex-col md:flex-row items-center justify-between">
      <div class="flex items-center space-x-4">
        <img src="images/aswin-profile.jpg" alt="Aswin Raj Sivaprakash" class="w-24 h-24 rounded-full border-2 border-white" />
        <div>
          <h1 class="text-4xl font-bold">Aswin Raj Sivaprakash</h1>
          <p class="text-lg mt-1">Clean Tech Marketer | Environmental Strategist | CRM Specialist</p>
        </div>
      </div>
      <div class="mt-4 md:mt-0 text-right">
        <p>📍 Porto, Portugal</p>
        <p>📞 +351 938816822</p>
        <p>✉️ <a href="mailto:aswinr63@gmail.com" class="underline">aswinr63@gmail.com</a></p>
        <p>🔗 <a href="https://linkedin.com/in/aswin-sivaprakash" target="_blank" class="underline">linkedin.com/in/aswin-sivaprakash</a></p>
      </div>
    </div>
  </header>

  <main class="container mx-auto px-4 py-10">

    <!-- Hero -->
    <section class="text-center px-4">
      <h2 class="text-5xl font-bold text-gray-800 mb-4">Hey, I'm Aswin 👋</h2>
      <p class="text-lg text-gray-600 max-w-xl mx-auto">
        A passionate clean tech marketer and sustainability specialist with 5+ years driving CRM, digital strategy, and ESG communications across global markets.
      </p>
      <div class="flex justify-center gap-4 mt-6">
        <a href="Resume - AR Sivaprakash.pdf" class="bg-green-600 text-white px-5 py-2 rounded-xl hover:bg-green-700 transition" download>📄 Download Resume</a>
        <a href="https://linkedin.com/in/aswin-sivaprakash" target="_blank" class="bg-blue-600 text-white px-5 py-2 rounded-xl hover:bg-blue-700 transition">🔗 LinkedIn</a>
      </div>
    </section>

    <!-- About -->
    <section id="about" class="py-16 px-4 bg-gray-100 text-gray-800">
      <div class="max-w-3xl mx-auto">
        <h2 class="text-3xl font-bold mb-4">About Me</h2>
        <p class="text-lg">
          I blend market expertise and sustainability passion to craft high-impact marketing strategies for clean technology and environmental initiatives. Skilled in CRM (HubSpot & Salesforce), digital campaigns, and stakeholder engagement, I deliver measurable results that support both business growth and environmental impact.
        </p>
      </div>
    </section>

    <!-- Experience -->
    <section id="experience" class="py-16 px-4 bg-white text-gray-800">
      <div class="max-w-4xl mx-auto">
        <h2 class="text-3xl font-bold mb-6 text-center">Experience</h2>
        <ul class="space-y-6">
          <li>
            <button onclick="toggle('exp1')" class="w-full text-left px-4 py-2 rounded bg-green-500 text-white hover:bg-green-600 transition">Freelance Clean Tech Marketer - Cleantech GrowthLab (Jun 2024 – Present)</button>
            <div id="exp1" class="hidden mt-2 ml-4">
              <ul class="list-disc pl-6">
                <li>Designed CRM workflows to nurture leads and improve SQL generation (10× increase).</li>
                <li>Sustained 44% average open rate on nurture emails.</li>
                <li>Developed digital strategy and content for social campaigns, boosting engagement by 30%.</li>
              </ul>
            </div>
          </li>
          <li>
            <button onclick="toggle('exp2')" class="w-full text-left px-4 py-2 rounded bg-blue-500 text-white hover:bg-blue-600 transition">Customer Success & Marketing Specialist - Scores &amp; Levels (Jun 2024 – Present)</button>
            <div id="exp2" class="hidden mt-2 ml-4">
              <ul class="list-disc pl-6">
                <li>Managed multi-channel campaigns, improving user retention by 25%.</li>
                <li>Developed onboarding flows in HubSpot, enhancing customer satisfaction by 20%.</li>
              </ul>
            </div>
          </li>
          <li>
            <button onclick="toggle('exp3')" class="w-full text-left px-4 py-2 rounded bg-blue-500 text-white hover:bg-blue-600 transition">Business Development Manager - National Chromatography Inco (Oct 2022 – May 2024)</button>
            <div id="exp3" class="hidden mt-2 ml-4">
              <ul class="list-disc pl-6">
                <li>Led international sales of chromatography equipment worth $35k+</li>
                <li>Onboarded 50+ clients via RFPs and cold outreach (80% sales quota).</li>
                <li>Boosted lead conversion by 13% with Salesforce CRM.</li>
              </ul>
            </div>
          </li>
          <li>
            <button onclick="toggle('exp4')" class="w-full text-left px-4 py-2 rounded bg-green-500 text-white hover:bg-green-600 transition">Environmental Consultant - MGK Aqua Inco (Nov 2020 – Aug 2021)</button>
            <div id="exp4" class="hidden mt-2 ml-4">
              <ul class="list-disc pl-6">
                <li>Assembled DPRs for sustainability, energy efficiency, and GHG management projects.</li>
                <li>Executed water treatment solutions for housing & corporate projects.</li>
                <li>Implemented rainwater harvesting and automated wastewater treatment plans.</li>
              </ul>
            </div>
          </li>
          <li>
            <button onclick="toggle('exp5')" class="w-full text-left px-4 py-2 rounded bg-green-500 text-white hover:bg-green-600 transition">Project Assistant – UNICEF WASH (Jul 2018 – Jun 2019)</button>
            <div id="exp5" class="hidden mt-2 ml-4">
              <ul class="list-disc pl-6">
                <li>Streamlined water testing (63 parameters) and installed solar stoves for 10k+ residents.</li>
                <li>Coordinated with government officials on solar stove and water pump projects.</li>
                <li>Modernized honeycomb toilet designs across 16 tea estates.</li>
              </ul>
            </div>
          </li>
        </ul>
      </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="py-16 px-4 bg-gray-100 text-gray-800">
      <div class="max-w-5xl mx-auto">
        <h2 class="text-3xl font-bold mb-6 text-center">Projects</h2>
        <div class="space-y-8">
          <div class="bg-green-50 p-6 rounded-xl">
            <h3 class="text-xl font-semibold">Upcoming Geothermal Heat Grid Case Study – Leeuwarden, NL (Feb 2022 – Apr 2022)</h3>
            <p class="mt-2">Collected data by interviewing 100 respondents on social concerns for geothermal integration. Processed qualitative insights with the DESSIN-ESS framework. Findings published by Omrop: <a href="https://www.omropfryslan.nl/nl/nieuws/1144457/internationale-studenten-duurzame-aanpak-in-fryslan-is-mogelijk" class="underline text-blue-600" target="_blank">View Article</a>.</p>
          </div>
          <div class="bg-green-50 p-6 rounded-xl">
            <h3 class="text-xl font-semibold">Coral Bleaching Status – Andaman Islands, India (Dec 2017 – Feb 2018)</h3>
            <p class="mt-2">Identified a 1°C SST increase above monthly maxima causing zooxanthellae symbiosis degradation. Assessed thermal stress via CBAS with satellite-derived SST. Studied Acropora degradation rates, presenting to ANET, the Indian Wildlife Department, and Indian Coast Guard.</p>
          </div>
          <div class="bg-green-50 p-6 rounded-xl">
            <h3 class="text-xl font-semibold">Municipal Solid Waste Management – Erode, India (Sep 2016 – Nov 2016)</h3>
            <p class="mt-2">Monitored 10k kWh/day electricity from gasification of 135 metric tonnes of waste. Assisted waste segregation into 6 categories including E-waste and hazardous waste.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Certifications & Courses -->
    <section id="certifications" class="py-16 px-4 bg-white text-gray-800">
      <div class="max-w-3xl mx-auto">
        <h2 class="text-3xl font-bold mb-4 text-center">Certifications & Courses</h2>
        <ul class="list-disc pl-6 text-lg space-y-2">
          <li>ISO 14001:2015 Lead Auditor (IRCA)</li>
          <li>NEBOSH International General Certificate in Occupational Health & Safety</li>
          <li>Health & Safety Practical Application</li>
          <li>Management of International Health & Safety</li>
          <li>Project Management by Google (Coursera)</li>
          <li>Generative AI for Digital Marketers (LinkedIn)</li>
        </ul>
      </div>
    </section>

    <!-- Skills -->
    <section id="skills" class="py-16 px-4 bg-gray-100 text-gray-800">
      <div class="max-w-3xl mx-auto">
        <h2 class="text-3xl font-bold mb-4 text-center">Skills</h2>
        <ul class="list-disc pl-6 text-lg space-y-2">
          <li>Sales & Marketing</li>
          <li>Lead Generation</li>
          <li>Cold Calling & Negotiation</li>
          <li>Zendesk & Mailchimp</li>
          <li>Kanban & Jira</li>
          <li>Excel & Google Sheets</li>
        </ul>
      </div>
    </section>

    <!-- Contact CTA -->
    <section id="contact" class="py-16 px-4 bg-white text-gray-800 text-center">
      <h2 class="text-3xl font-bold mb-4">Let’s Connect</h2>
      <p class="text-lg mb-4">Open to freelance, full-time, and mission-driven collaborations.</p>
      <a href="mailto:aswinr63@gmail.com" class="inline-block bg-blue-600 text-white py-3 px-6 rounded-xl hover:bg-blue-700 transition">
        ✉️ Email Me
      </a>
    </section>

  </main>

  <footer class="text-center text-sm text-gray-500 mt-12 p-4 border-t">
    &copy; 2024 Aswin Raj Sivaprakash
  </footer>

  <script>
    function toggle(id) {
      document.getElementById(id).classList.toggle('hidden');
    }
  </script>
</body>
</html>

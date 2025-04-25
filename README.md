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
    <div class="container mx-auto text-center">
      <h1 class="text-4xl font-bold">Aswin Raj Sivaprakash</h1>
      <p class="text-lg mt-2">Clean Tech Marketer | Environmental Strategist | CRM Specialist</p>
    </div>
  </header>

  <main class="container mx-auto px-4 py-10">

    <!-- Hero -->
    <section class="text-center px-4">
      <h1 class="text-5xl font-bold text-gray-800 mb-4">Hey, I'm Aswin 👋</h1>
      <p class="text-lg text-gray-600 max-w-xl mx-auto">
        A passionate clean tech marketer and sustainability specialist with experience in CRM, digital strategy, and ESG communications.
      </p>
      <div class="flex justify-center gap-4 mt-6">
        <a href="YOUR_RESUME_LINK.pdf" class="bg-green-600 text-white px-5 py-2 rounded-xl hover:bg-green-700 transition" download>📄 Download Resume</a>
        <a href="https://linkedin.com/in/aswin-sivaprakash" target="_blank" class="bg-blue-600 text-white px-5 py-2 rounded-xl hover:bg-blue-700 transition">🔗 LinkedIn</a>
      </div>
    </section>

    <!-- About -->
    <section class="py-16 px-4 bg-gray-100 text-gray-800">
      <div class="max-w-3xl mx-auto">
        <h2 class="text-3xl font-bold mb-4">About Me</h2>
        <p class="text-lg">
          With 5+ years of experience in clean tech marketing, sustainability projects, and CRM campaigns, I design high-impact strategies that drive both environmental and business outcomes. I blend data, storytelling, and execution to move missions forward.
        </p>
      </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="py-16 px-4 bg-white text-gray-800">
      <div class="max-w-5xl mx-auto">
        <h2 class="text-3xl font-bold mb-6 text-center">Projects</h2>
        <div class="grid gap-4 md:grid-cols-2">

          <!-- Cleantech Project -->
          <div class="p-6 rounded-xl bg-blue-100 hover:shadow-lg transition col-span-2">
            <h3 class="text-xl font-semibold mb-2 cursor-pointer text-blue-800" onclick="toggleProject('crm1')">CRM Campaign – Cleantech Growthlab</h3>
            <p>Click to view CRM workflow, results, and email sample.</p>
            <div id="crm1" class="mt-4 hidden">
              <ul class="list-disc pl-6 text-sm">
                <li>Lifecycle nurture + behavior scoring</li>
                <li>SQLs grew 10x | 44% open rate</li>
              </ul>
              <img src="images/crm-sql-graph.png" class="rounded mt-3 w-full max-w-sm" alt="CRM Graph">
            </div>
          </div>

          <!-- iGaming -->
          <div class="p-6 rounded-xl bg-yellow-100 hover:shadow-lg transition col-span-2">
            <h3 class="text-xl font-semibold mb-2 cursor-pointer text-yellow-800" onclick="toggleProject('crm2')">CRM Campaign – iGaming</h3>
            <p>Click to view segmentation and retention strategy.</p>
            <div id="crm2" class="mt-4 hidden">
              <ul class="list-disc pl-6 text-sm">
                <li>Lifecycle-based reactivation using HubSpot</li>
                <li>+20% user LTV</li>
              </ul>
            </div>
          </div>

          <!-- UNICEF -->
          <div class="p-6 rounded-xl bg-green-100 hover:shadow-lg transition col-span-2">
            <h3 class="text-xl font-semibold mb-2 cursor-pointer text-green-800" onclick="toggleProject('unicef')">UNICEF Solar Sanitation Project</h3>
            <p>Click to view fieldwork and implementation summary.</p>
            <div id="unicef" class="mt-4 hidden">
              <ul class="list-disc pl-6 text-sm">
                <li>Solar cooking + sanitation for 10,000+</li>
                <li>Coordination with local government</li>
              </ul>
            </div>
          </div>

          <!-- SMOOV -->
          <div class="p-6 rounded-xl bg-purple-100 hover:shadow-lg transition col-span-2">
            <h3 class="text-xl font-semibold mb-2 cursor-pointer text-purple-800" onclick="toggleProject('smoov')">EV Charging App Research – SMOOV</h3>
            <p>Click to view GIS and urban mobility analysis.</p>
            <div id="smoov" class="mt-4 hidden">
              <ul class="list-disc pl-6 text-sm">
                <li>LiDAR, GIS, and user survey analysis</li>
                <li>Used in nitrogen crisis mobility strategy</li>
              </ul>
            </div>
          </div>

        </div>
      </div>
    </section>

    <!-- Contact -->
    <section class="py-16 px-4 bg-gray-100 text-gray-800 text-center">
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

  <!-- Toggle JS -->
  <script>
    function toggleProject(id) {
      document.getElementById(id).classList.toggle('hidden');
    }
  </script>
</body>
</html>

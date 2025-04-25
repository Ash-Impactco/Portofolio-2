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
    <section class="min-h-screen flex flex-col items-center justify-center text-center px-4">
      <h1 class="text-5xl font-bold text-gray-800 mb-4">Hey, I'm Aswin 👋</h1>
      <p class="text-lg text-gray-600 max-w-xl">
        A passionate clean tech marketer and sustainability specialist with experience in CRM, digital strategy, and ESG communications.
      </p>
    </section>

    <!-- About -->
    <section class="py-20 px-4 bg-gray-100 text-gray-800">
      <div class="max-w-3xl mx-auto">
        <h2 class="text-3xl font-bold mb-4">About Me</h2>
        <p class="text-lg">
          With 5+ years of experience in clean tech marketing, sustainability projects, and CRM campaigns, I design high-impact strategies that drive both environmental and business outcomes. I blend data, storytelling, and execution to move missions forward.
        </p>
      </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="py-20 px-4 bg-white text-gray-800">
      <div class="max-w-5xl mx-auto">
        <h2 class="text-3xl font-bold mb-8">Projects</h2>
        <div class="grid gap-8 md:grid-cols-2">

          <!-- CRM Cleantech -->
          <div class="p-6 border rounded-xl shadow-sm hover:shadow-md transition col-span-2">
            <h3 class="text-xl font-semibold mb-2 cursor-pointer text-blue-700 hover:underline" onclick="toggleProject('crm1')">CRM Campaign – Cleantech Growthlab</h3>
            <p class="text-gray-600">Click to view full CRM workflow, results, and email example.</p>
            <div id="crm1" class="mt-4 hidden transition-all">
              <p>💡 Full-funnel CRM lifecycle using HubSpot and Salesforce for B2B cleantech buyers.</p>
              <ul class="list-disc pl-6 mt-2">
                <li>Lifecycle nurture workflow (welcome → value → conversion)</li>
                <li>Behavior-based triggers and scoring logic</li>
                <li>10x SQL increase, 44% open rate</li>
              </ul>
              <!-- Image placeholder (replace src with your actual image) -->
              <img src="images/crm-sql-graph.png" alt="SQL Growth Chart" class="rounded-lg shadow-md mt-4 max-w-md">
              <pre class="bg-gray-100 p-3 rounded text-sm mt-4 overflow-auto">
Subject: Your Cleantech Growth Pod is Ready 🚀

Hi {{firstName}},
Thanks for signing up for Cleantech Growthlab!
Activate your free GTM toolkit → [link]
              </pre>
            </div>
          </div>

          <!-- CRM iGaming -->
          <div class="p-6 border rounded-xl shadow-sm hover:shadow-md transition col-span-2">
            <h3 class="text-xl font-semibold mb-2 cursor-pointer text-blue-700 hover:underline" onclick="toggleProject('crm2')">CRM Campaign – iGaming</h3>
            <p class="text-gray-600">Click to view segmentation and retention strategy.</p>
            <div id="crm2" class="mt-4 hidden transition-all">
              <p>🎯 Built multichannel HubSpot campaign targeting segmented iGaming audiences.</p>
              <ul class="list-disc pl-6 mt-2">
                <li>Lifecycle & LTV-based segmentation</li>
                <li>Bonus-triggered reactivation emails</li>
                <li>20% uplift in average user lifetime</li>
              </ul>
            </div>
          </div>

          <!-- UNICEF -->
          <div class="p-6 border rounded-xl shadow-sm hover:shadow-md transition col-span-2">
            <h3 class="text-xl font-semibold mb-2 cursor-pointer text-blue-700 hover:underline" onclick="toggleProject('unicef')">UNICEF Solar Sanitation Project</h3>
            <p class="text-gray-600">Click to view implementation and fieldwork summary.</p>
            <div id="unicef" class="mt-4 hidden transition-all">
              <p>🌱 Provided solar-powered cooking and clean water access in rural Assam.</p>
              <ul class="list-disc pl-6 mt-2">
                <li>Deployed sanitation solutions for 10,000+ residents</li>
                <li>Coordinated with local government & stakeholders</li>
                <li>Reduced reliance on coal and firewood</li>
              </ul>
            </div>
          </div>

          <!-- SMOOV -->
          <div class="p-6 border rounded-xl shadow-sm hover:shadow-md transition col-span-2">
            <h3 class="text-xl font-semibold mb-2 cursor-pointer text-blue-700 hover:underline" onclick="toggleProject('smoov')">EV Charging App Research – SMOOV</h3>
            <p class="text-gray-600">Click to view UX and smart mobility analysis project.</p>
            <div id="smoov" class="mt-4 hidden transition-all">
              <p>🚗 Assessed urban planning needs using GIS & LiDAR for EV route optimization.</p>
              <ul class="list-disc pl-6 mt-2">
                <li>User survey + traffic data collection</li>
                <li>Helped refine city-level deployment models</li>
              </ul>
            </div>
          </div>

        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="py-20 px-4 bg-gray-100 text-gray-800">
      <div class="max-w-xl mx-auto text-center">
        <h2 class="text-3xl font-bold mb-4">Get In Touch</h2>
        <p class="text-lg mb-6">Have a project in mind or just want to connect? I’d love to hear from you.</p>
        <a href="mailto:aswinr63@gmail.com" class="inline-block bg-blue-600 text-white py-3 px-6 rounded-xl hover:bg-blue-700 transition">
          Say Hello
        </a>
      </div>
    </section>

  </main>

  <!-- Footer -->
  <footer class="text-center text-sm text-gray-500 mt-12 p-4 border-t">
    &copy; 2024 Aswin Raj Sivaprakash
  </footer>

  <!-- Toggle Script -->
  <script>
    function toggleProject(id) {
      const el = document.getElementById(id);
      el.classList.toggle('hidden');
    }
  </script>
</body>
</html>

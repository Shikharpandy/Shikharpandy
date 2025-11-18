<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Data Analyst Portfolio — Shikhar Pandey</title>
  <link href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-800 leading-relaxed">

  <!-- HEADER WITH LOGO GIF -->
  <header class="bg-white shadow">
    <div class="container mx-auto px-6 py-6 flex items-center justify-between">
      <div class="flex items-center gap-4">
        <!-- Replace GIF link -->
        <img src="https://media.giphy.com/media/SvckSy7fFviqrq8ClF/giphy.gif" alt="logo" class="w-16 h-16 rounded-full border" />
        <div>
          <h1 class="text-3xl font-bold">Shikhar Pandey</h1>
          <p class="text-sm text-gray-600">Data Analyst • Python • SQL • BI Tools</p>
        </div>
      </div>
      <nav class="space-x-4 text-sm">
        <a href="#skills" class="hover:underline">Skills</a>
        <a href="#projects" class="hover:underline">Projects</a>
        <a href="#contact" class="hover:underline">Contact</a>
      </nav>
    </div>
  </header>

  <!-- HERO SECTION -->
  <section class="container mx-auto px-6 py-16 text-center">
    <h2 class="text-4xl font-bold mb-4">Hi, I'm <span class="text-indigo-600">Shikhar Pandey</span></h2>
    <p class="max-w-2xl mx-auto text-lg text-gray-700">
      A passionate <strong>Data Analyst</strong> skilled in Python, SQL, BI tools, and data storytelling — transforming raw data into actionable insights.
    </p>
    <div class="mt-6 flex justify-center gap-3">
      <a href="#projects" class="px-5 py-2 rounded-lg bg-indigo-600 text-white text-sm">View Projects</a>
      <a href="#contact" class="px-5 py-2 rounded-lg border text-sm">Contact</a>
    </div>
  </section>

  <!-- SKILLS WITH GIF ICONS -->
  <section id="skills" class="container mx-auto px-6 py-10">
    <h3 class="text-2xl font-semibold mb-6">Skills</h3>
    <div class="grid md:grid-cols-4 gap-6">

      <!-- Python -->
      <div class="bg-white shadow p-4 rounded-lg text-center">
        <img src="https://media.giphy.com/media/KAq5w47R9rmTuvWOWa/giphy.gif" class="h-20 mx-auto mb-2" />
        <h4 class="font-semibold">Python</h4>
        <p class="text-xs text-gray-600">Numpy, Pandas, Matplotlib, Seaborn</p>
      </div>

      <!-- SQL -->
      <div class="bg-white shadow p-4 rounded-lg text-center">
        <img src="sql.gif" class="h-20 mx-auto mb-2" />
        <h4 class="font-semibold">SQL</h4>
        <p class="text-xs text-gray-600">MySQL, MS SQL, PostgreSQL</p>
      </div>

      <!-- MongoDB -->
      <div class="bg-white shadow p-4 rounded-lg text-center">
        <img src="mongodb.gif" class="h-20 mx-auto mb-2" />
        <h4 class="font-semibold">MongoDB</h4>
        <p class="text-xs text-gray-600">NoSQL & Document Databases</p>
      </div>

      <!-- BI Tools -->
      <div class="bg-white shadow p-4 rounded-lg text-center">
        <img src="powerbi.gif" class="h-20 mx-auto mb-2" />
        <h4 class="font-semibold">BI Tools</h4>
        <p class="text-xs text-gray-600">Power BI, Tableau, Excel</p>
      </div>

    </div>
  </section>

  <!-- PROJECTS SECTION WITH REPOSITORY CARDS -->
  <section id="projects" class="container mx-auto px-6 py-10">
    <h3 class="text-2xl font-semibold mb-6">Projects</h3>
    <p class="text-sm text-gray-700 mb-4">Below are some of my GitHub repositories:</p>

    <div class="grid md:grid-cols-3 gap-6">

      <!-- PROJECT ITEM TEMPLATE → duplicate and update repo links -->
      <div class="bg-white p-5 rounded-lg shadow">
        <h4 class="font-bold mb-1">Attendance System</h4>
        <p class="text-xs text-gray-600 mb-2">Full analytics + SQL backend + Power BI dashboard.</p>
        <a href="#" class="text-sm underline">View Repository</a>
      </div>

      <div class="bg-white p-5 rounded-lg shadow">
        <h4 class="font-bold mb-1">Shopping Sales Analysis</h4>
        <p class="text-xs text-gray-600 mb-2">ETL pipeline + trend analysis + visual dashboards.</p>
        <a href="https://www.kaggle.com/code/shikharpandy/shopping-data-analysis" class="text-sm underline">View Repository</a>
      </div>

      <div class="bg-white p-5 rounded-lg shadow">
        <h4 class="font-bold mb-1">Book Data Insights</h4>
        <p class="text-xs text-gray-600 mb-2">Cleaned & modeled book sales dataset with Python.</p>
        <a href="#" class="text-sm underline">View Repository</a>
      </div>

    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="text-center py-10">
    <p class="text-gray-700 text-sm">Email: jrspandey@gmail.com</p>
    <p class="text-gray-600 text-xs">LinkedIn: linkedin.com/in/yourusername</p>
  </section>

  <footer class="bg-white border-t mt-10">
    <div class="container mx-auto px-6 py-6 text-sm text-gray-600 text-center">
      © 2025 Shikhar Pandey — Data Analyst Portfolio
    </div>
  </footer>

</body>
</html>

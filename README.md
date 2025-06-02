<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ganesh Chandra | Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <style>
    @keyframes float {
      0% { transform: translatey(0px); }
      50% { transform: translatey(-10px); }
      100% { transform: translatey(0px); }
    }
    .animate-float {
      animation: float 3s ease-in-out infinite;
    }
    .fade-in {
      animation: fadeIn 1.5s ease-in forwards;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body class="bg-gray-900 text-white font-sans">
  <div class="min-h-screen flex flex-col items-center justify-center px-4">
    <h1 class="text-5xl font-bold text-center animate-float">👋 Hi, I'm Ganesh Chandra</h1>
    <p class="text-xl text-gray-400 mt-4 text-center fade-in">Software Developer | Cloud Enthusiast | Full Stack Engineer</p>
    <div class="mt-10 space-x-4 fade-in">
      <a href="mailto:cganesh208@gmail.com" class="bg-blue-500 hover:bg-blue-600 text-white px-4 py-2 rounded-lg transition-all">Email Me</a>
      <a href="https://github.com/ganeshchandra" target="_blank" class="bg-gray-800 hover:bg-gray-700 text-white px-4 py-2 rounded-lg transition-all">GitHub</a>
      <a href="https://linkedin.com/in/..." target="_blank" class="bg-blue-700 hover:bg-blue-800 text-white px-4 py-2 rounded-lg transition-all">LinkedIn</a>
    </div>

    <div class="mt-20 max-w-3xl w-full fade-in">
      <h2 class="text-3xl font-semibold mb-4 border-b pb-2 border-gray-700">🚀 Projects</h2>
      <div class="grid md:grid-cols-2 gap-6">
        <div class="bg-gray-800 p-4 rounded-lg shadow-lg hover:scale-105 transform transition-transform">
          <h3 class="text-xl font-bold">Fleet Tracker</h3>
          <p class="text-gray-300">Real-time GPS fleet tracking with Vue.js and Golang.</p>
        </div>
        <div class="bg-gray-800 p-4 rounded-lg shadow-lg hover:scale-105 transform transition-transform">
          <h3 class="text-xl font-bold">GeneView</h3>
          <p class="text-gray-300">Genome visualization using React and TypeScript.</p>
        </div>
      </div>
    </div>

    <footer class="mt-20 text-sm text-gray-500 text-center fade-in">
      Built with ❤️ using TailwindCSS. Last updated 2025.
    </footer>
  </div>
</body>
</html>

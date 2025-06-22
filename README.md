<!-- README.md starts here -->

<!-- Tailwind CSS & AOS -->
<link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>

<!-- Custom Style -->
<style>
  body {
    background: linear-gradient(135deg, #0f172a, #1e293b);
    color: white;
    font-family: 'Segoe UI', sans-serif;
  }
  .neon-text {
    text-shadow: 0 0 10px #6ee7b7, 0 0 20px #3b82f6;
  }
  .typewriter::after {
    content: "|";
    animation: blink 1s infinite;
  }
  @keyframes blink {
    50% { opacity: 0; }
  }
</style>

<!-- Animated Header -->
<div class="text-center mt-10" data-aos="fade-in">
  <h1 class="text-4xl md:text-6xl font-extrabold neon-text">
    👋 <span id="typewriter" class="typewriter">Hi, I'm Pratham</span>
  </h1>
  <p class="mt-3 text-lg text-gray-300">GenAI Intern at EY | Building AI-Powered Solutions That Amaze</p>
  <p class="mt-1 italic text-sm text-gray-400">"I love building projects that make people go 'Whoa!'"</p>
</div>

<!-- About Me -->
<div class="mt-10 px-4" data-aos="fade-up">
  <h2 class="text-2xl font-semibold neon-text mb-4">🧑‍💻 About Me</h2>
  <div class="grid md:grid-cols-2 gap-6">
    <div class="bg-gray-800 p-4 rounded-xl hover:scale-105 transition-transform shadow-lg" data-aos="fade-up">
      <p>
        Currently a GenAI intern at <strong>EY</strong>, passionate about <strong>Kubernetes, GenAI, AI agents, LangChain</strong>, and building innovative solutions.
        I’m working on a <strong>Fashion AI Recommendation System integrated with our own e-commerce website</strong>.
      </p>
    </div>
  </div>
</div>

<!-- Tech Stack -->
<div class="mt-10 px-4" data-aos="fade-right">
  <h2 class="text-2xl font-semibold neon-text mb-4">⚙️ Tech Stack</h2>
  <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-4 text-center">
    <div data-aos="slide-up" class="bg-gray-900 rounded p-2 hover:bg-purple-700 transition">Python</div>
    <div data-aos="slide-up">Shell Scripting</div>
    <div data-aos="slide-up">R</div>
    <div data-aos="slide-up">HTML</div>
    <div data-aos="slide-up">MySQL</div>
    <div data-aos="slide-up">Transformers</div>
    <div data-aos="slide-up">Pandas</div>
    <div data-aos="slide-up">NumPy</div>
    <div data-aos="slide-up">Matplotlib</div>
    <div data-aos="slide-up">Git</div>
    <div data-aos="slide-up">GitHub</div>
    <div data-aos="slide-up">Linux</div>
    <div data-aos="slide-up">Docker</div>
    <div data-aos="slide-up">AWS</div>
    <div data-aos="slide-up">GenAI Tools</div>
  </div>
</div>

<!-- GitHub Stats -->
<div class="mt-10 px-4 text-center" data-aos="zoom-in">
  <h2 class="text-2xl font-semibold neon-text mb-4">📊 GitHub Stats</h2>
  <div class="flex flex-wrap justify-center gap-4">
    <img src="https://github-readme-stats.vercel.app/api?username=prathamj937&show_icons=true&theme=radical" width="400">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=prathamj937&theme=radical" width="400">
  </div>
</div>

<!-- Projects -->
<div class="mt-10 px-4" data-aos="fade-left">
  <h2 class="text-2xl font-semibold neon-text mb-4">🚀 Projects Worth Checking Out</h2>
  <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-6">
    <!-- Project Card Template -->
    <div class="bg-gray-800 p-4 rounded-lg hover:shadow-neon transition-transform transform hover:scale-105" data-aos="flip-up">
      <h3 class="text-xl font-bold">Project 1 - TBD</h3>
      <p class="text-sm text-gray-400">A cool project in progress, stay tuned!</p>
      <div class="text-xs text-purple-400 mt-2">Python, AWS</div>
      <a href="#" class="mt-2 inline-block bg-purple-600 text-white px-3 py-1 rounded hover:bg-purple-800">View Project</a>
    </div>
    <!-- Repeat for other projects -->
    <div class="bg-gray-800 p-4 rounded-lg hover:scale-105 transition" data-aos="flip-up">...Project 2...</div>
    <div class="bg-gray-800 p-4 rounded-lg hover:scale-105 transition" data-aos="flip-up">...Project 3...</div>
    <div class="bg-gray-800 p-4 rounded-lg hover:scale-105 transition" data-aos="flip-up">...Project 4...</div>
    <div class="bg-gray-800 p-4 rounded-lg hover:scale-105 transition" data-aos="flip-up">...Project 5...</div>
  </div>
</div>

<!-- Contact -->
<div class="mt-10 px-4 text-center" data-aos="fade-up">
  <h2 class="text-2xl font-semibold neon-text mb-4">✨ Let's Connect</h2>
  <p>Reach me at: <a href="mailto:prathamj937@gmail.com" class="underline text-blue-400">prathamj937@gmail.com</a></p>
  <div class="mt-4 flex justify-center gap-4">
    <a href="https://www.linkedin.com/in/your-profile" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-blue?logo=linkedin&style=for-the-badge" class="animate-bounce hover:scale-110 transition">
    </a>
    <a href="mailto:prathamj937@gmail.com">
      <img src="https://img.shields.io/badge/Gmail-red?logo=gmail&style=for-the-badge" class="animate-bounce hover:scale-110 transition">
    </a>
  </div>
</div>

<!-- Footer -->
<div class="mt-10 text-center text-gray-500 text-sm">
  <p>Made with ❤️ by Pratham | Powered by GitHub</p>
  <button onclick="window.scrollTo({ top: 0, behavior: 'smooth' })"
    class="fixed bottom-4 right-4 bg-purple-700 hover:bg-purple-900 text-white px-3 py-1 rounded-full shadow-lg animate-bounce hidden md:inline-block">
    ⬆️
  </button>
</div>

<!-- AOS and Typewriter -->
<script>
  AOS.init();

  const typewriter = document.getElementById("typewriter");
  const text = "Hi, I'm Pratham";
  let index = 0;
  function typeEffect() {
    if (index < text.length) {
      typewriter.innerText = text.substring(0, index + 1);
      index++;
      setTimeout(typeEffect, 100);
    }
  }
  typeEffect();
</script>

<!-- README.md ends here -->

 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Music Producer & Sound Engineer</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-900 text-white font-sans">

  <!-- Header / Hero -->
  <section class="min-h-screen flex flex-col justify-center items-center text-center px-6">
    <h1 class="text-5xl font-bold mb-4">Your Name</h1>
    <p class="text-xl text-gray-300 mb-6">Professional Music Producer & Sound Engineer</p>
    <a href="#contact" class="bg-blue-600 hover:bg-blue-700 text-white px-6 py-3 rounded-full">Book a Session</a>
  </section>

  <!-- About -->
  <section id="about" class="py-20 px-6 max-w-4xl mx-auto text-center">
    <h2 class="text-3xl font-bold mb-6">About Me</h2>
    <p class="text-gray-300 leading-relaxed">I’m a music producer and sound engineer with experience in multiple genres. From mixing and mastering to full beat production, I help artists bring their vision to life with industry-standard quality.</p>
  </section>

  <!-- Services -->
  <section id="services" class="py-20 bg-gray-800 px-6">
    <h2 class="text-3xl font-bold text-center mb-10">Services</h2>
    <div class="grid md:grid-cols-2 gap-8 max-w-5xl mx-auto">
      <div class="bg-gray-700 p-6 rounded-2xl shadow">
        <h3 class="text-xl font-semibold mb-2">🎚️ Mixing & Mastering</h3>
        <p class="text-gray-300 mb-4">Clean, polished, and professional sound for your tracks.</p>
        <a href="#contact" class="text-blue-400 hover:underline">Hire Me</a>
      </div>
      <div class="bg-gray-700 p-6 rounded-2xl shadow">
        <h3 class="text-xl font-semibold mb-2">🎵 Beat Production</h3>
        <p class="text-gray-300 mb-4">Custom beats tailored to your style and vision.</p>
        <a href="#contact" class="text-blue-400 hover:underline">Hire Me</a>
      </div>
      <div class="bg-gray-700 p-6 rounded-2xl shadow">
        <h3 class="text-xl font-semibold mb-2">🎤 Vocal Recording / Editing</h3>
        <p class="text-gray-300 mb-4">Professional recording setup and vocal tuning/editing.</p>
        <a href="#contact" class="text-blue-400 hover:underline">Hire Me</a>
      </div>
      <div class="bg-gray-700 p-6 rounded-2xl shadow">
        <h3 class="text-xl font-semibold mb-2">🎧 Sound Design</h3>
        <p class="text-gray-300 mb-4">Unique sounds and textures for your music or projects.</p>
        <a href="#contact" class="text-blue-400 hover:underline">Hire Me</a>
      </div>
    </div>
  </section>

  <!-- Portfolio -->
  <section id="portfolio" class="py-20 px-6 max-w-5xl mx-auto text-center">
    <h2 class="text-3xl font-bold mb-6">Portfolio</h2>
    <p class="text-gray-300 mb-8">Listen to some of my recent projects.</p>
    <div class="grid md:grid-cols-2 gap-8">
      <iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay"
        src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/yourtrackid"></iframe>
      <iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay"
        src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/yourtrackid"></iframe>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-20 bg-gray-800 px-6">
    <h2 class="text-3xl font-bold text-center mb-6">Contact Me</h2>
    <form class="max-w-xl mx-auto space-y-4">
      <input type="text" placeholder="Your Name" class="w-full p-3 rounded bg-gray-700 text-white">
      <input type="email" placeholder="Your Email" class="w-full p-3 rounded bg-gray-700 text-white">
      <textarea placeholder="Your Message" rows="5" class="w-full p-3 rounded bg-gray-700 text-white"></textarea>
      <button type="submit" class="bg-blue-600 hover:bg-blue-700 px-6 py-3 rounded-full">Send Message</button>
    </form>
    <div class="text-center mt-6">
      <p>Or reach me at: <a href="mailto:youremail@example.com" class="text-blue-400">youremail@example.com</a></p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-6 text-center text-gray-400 bg-gray-900">
    <p>© 2025 Your Name. All Rights Reserved.</p>
  </footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Aditi Parnami | Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
  <style>
    @keyframes fadeSlideIn {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .fade-slide {
      animation: fadeSlideIn 0.8s ease-out both;
    }
  </style>
</head>
<body class="bg-gradient-to-tr from-slate-900 via-purple-900 to-slate-800 text-white font-sans">

  <!-- Navbar -->
  <header class="fixed top-0 w-full bg-slate-950 bg-opacity-80 backdrop-blur z-50 shadow">
    <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-xl font-bold text-pink-400">Aditi Parnami</h1>
      <nav>
        <ul class="hidden md:flex space-x-8 text-sm font-medium">
          <li><a href="#home" class="hover:text-pink-400">Home</a></li>
          <li><a href="#about" class="hover:text-pink-400">About</a></li>
          <li><a href="#profile" class="hover:text-pink-400">Profile</a></li>
          <li><a href="#skills" class="hover:text-pink-400">Skills</a></li>
          <li><a href="#projects" class="hover:text-pink-400">Projects</a></li>
          <li><a href="#achievements" class="hover:text-pink-400">Achievements</a></li>
          <li><a href="#contact" class="hover:text-pink-400">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section id="home" class="pt-32 pb-20 text-center fade-slide">
    <div class="max-w-3xl mx-auto px-6">
      <h2 class="text-5xl font-extrabold mb-4 text-pink-400">Hi, I'm Aditi Parnami</h2>
      <p class="text-xl text-gray-300 mb-6">An Enthusiastic Learner | Exploring the World of Tech</p>
      <a href="#contact" class="inline-block px-6 py-3 bg-pink-500 text-white font-semibold rounded hover:bg-pink-600 transition">Contact Me</a>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="py-20 bg-slate-800">
    <div class="max-w-4xl mx-auto px-6 text-center fade-slide">
      <h2 class="text-3xl font-bold text-pink-400 mb-6">About Me</h2>
      <p class="text-gray-300">I am a 2nd-year B.Tech student in Information Technology with a basic understanding of C and C++. I am passionate about technology and love learning new things, especially by connecting with others in the tech world.</p>
    </div>
  </section>

  <!-- Profile -->
  <section id="profile" class="py-20 bg-slate-900">
    <div class="max-w-6xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center fade-slide">
      <div class="flex justify-center">
        <img src="https://via.placeholder.com/250" alt="C:\Users\aditi\OneDrive\Pictures\WhatsApp Image 2025-06-14 at 03.14.34_cd8c3827.jpg" class="rounded-2xl shadow-lg w-60 h-60 object-cover" />
      </div>
      <div>
        <h2 class="text-3xl font-bold text-pink-400 mb-4">My Profile</h2>
        <p class="text-gray-300 mb-2">Name: <span class="text-white">Aditi Parnami</span></p>
        <p class="text-gray-300 mb-2">Education: <span class="text-white">B.Tech in Information Technology (2nd Year)</span></p>
        <p class="text-gray-300 mb-2">Email: <a href="mailto:aditiparnami@gmail.com" class="text-white underline">aditiparnami@gmail.com</a></p>
        <p class="text-gray-300">Phone: <span class="text-white">+91 7389339888</span></p>
      </div>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills" class="py-20 bg-gradient-to-r from-slate-900 to-slate-700">
    <div class="max-w-6xl mx-auto px-6">
      <h2 class="text-3xl font-bold text-center text-pink-400 mb-10">Skills</h2>
      <div class="grid md:grid-cols-2 gap-12 text-gray-300">
        <div>
          <h3 class="text-xl font-semibold mb-4">Technical Skills</h3>
          <ul class="space-y-2">
            <li>HTML</li>
            <li>C++</li>
            <li>C</li>
            <li>Maven, JDBC, Servlet, JSP</li>
          </ul>
        </div>
        <div>
          <h3 class="text-xl font-semibold mb-4">Soft Skills</h3>
          <ul class="space-y-2">
            <li>Communication</li>
            <li>Teamwork</li>
            <li>Project Management</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="py-20 bg-slate-800">
    <div class="max-w-6xl mx-auto px-6">
      <h2 class="text-3xl font-bold text-center text-pink-400 mb-12">Projects</h2>
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="bg-slate-700 p-6 rounded-lg shadow-md hover:shadow-xl transition">
          <h3 class="text-lg font-bold text-white mb-2">Student Result Management</h3>
          <p class="text-sm text-gray-300">A web app using JSP, Servlets, and MySQL to manage student results with role-based access.</p>
        </div>
        <div class="bg-slate-700 p-6 rounded-lg shadow-md hover:shadow-xl transition">
          <h3 class="text-lg font-bold text-white mb-2">Library Management System</h3>
          <p class="text-sm text-gray-300">A Java Swing application using JDBC to manage books and user records in a library.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Achievements -->
  <section id="achievements" class="py-20 bg-slate-900">
    <div class="max-w-4xl mx-auto px-6 text-center fade-slide">
      <h2 class="text-3xl font-bold text-pink-400 mb-10">Achievements</h2>
      <ul class="space-y-6 text-left text-gray-300">
        <li>
          <h3 class="font-semibold text-white">NPTEL Elite - Programming in Java</h3>
          <p class="text-sm">Received Elite certification for outstanding performance.</p>
        </li>
        <li>
          <h3 class="font-semibold text-white">Aspire Leaders Program Graduate</h3>
          <p class="text-sm">Completed a Harvard-certified leadership program focused on personal growth and career readiness.</p>
        </li>
      </ul>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-20 bg-pink-600 text-white text-center">
    <div class="max-w-3xl mx-auto px-6">
      <h2 class="text-3xl font-bold mb-6">Contact Me</h2>
      <p>Email: <a href="mailto:aditiparnami@gmail.com" class="underline">aditiparnami@gmail.com</a></p>
      <p>Phone: +91 7389339888</p>
      <div class="mt-4 flex justify-center space-x-6 text-xl">
        <a href="https://github.com/aditiparnami05" target="_blank"><i class="fab fa-github"></i></a>
        <a href="https://www.linkedin.com/in/aditi-parnami-68223433a/" target="_blank"><i class="fab fa-linkedin"></i></a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-6 bg-slate-950 text-center text-gray-400 text-sm">
    <p>&copy; 2025 Aditi Parnami. All rights reserved.</p>
  </footer>

</body>
</html>

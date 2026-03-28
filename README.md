<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portafolio | Abdias Aq</title>

<!-- Tailwind -->
<script src="https://cdn.tailwindcss.com"></script>

<!-- AOS -->
<link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet">

<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
body {
  background: linear-gradient(135deg, #0b0003, #1a0008, #000000);
}

/* sombra glow vino */
.glow {
  text-shadow: 0 0 10px rgba(140, 0, 40, 0.8),
               0 0 20px rgba(140, 0, 40, 0.6);
}
</style>

</head>

<body class="text-white font-sans">

<!-- NAVBAR FIJA -->
<nav class="fixed top-0 left-0 w-full bg-black/80 backdrop-blur-md shadow-lg z-50">
  <div class="max-w-5xl mx-auto flex justify-center gap-10 py-4">
    <a href="#inicio" class="hover:text-red-400 transition">Inicio</a>
    <a href="#proyectos" class="hover:text-red-400 transition">Proyectos</a>
    <a href="#habilidades" class="hover:text-red-400 transition">Habilidades</a>
    <a href="#contacto" class="hover:text-red-400 transition">Contacto</a>
  </div>
</nav>

<!-- ESPACIO PARA NAVBAR -->
<div class="h-20"></div>

<!-- LANDING -->
<section id="inicio" class="h-screen flex flex-col justify-center items-center text-center px-6">

  <h1 class="text-5xl md:text-6xl font-bold mb-4 glow"
      data-aos="fade-up">
    Abdias Aq
  </h1>

  <p class="text-gray-400 mb-6" data-aos="fade-up" data-aos-delay="200">
    Estudiante de Ingeniería Estadística e Informática
  </p>

  <a href="#proyectos"
     class="bg-red-900 hover:bg-red-700 px-6 py-3 rounded-lg shadow-lg transition"
     data-aos="zoom-in" data-aos-delay="400">
     Ver Proyectos
  </a>

</section>

<!-- SOBRE -->
<section class="max-w-4xl mx-auto py-20 px-6" data-aos="fade-up">
  <h2 class="text-3xl text-red-500 mb-4">Sobre mí</h2>
  <p class="text-gray-400">
    Soy estudiante de Ingeniería Estadística e Informática, con interés en análisis de datos,
    programación y desarrollo web. Me enfoco en aprender constantemente y desarrollar soluciones modernas.
  </p>
</section>

<!-- PROYECTOS -->
<section id="proyectos" class="max-w-4xl mx-auto py-20 px-6">
  <h2 class="text-3xl text-red-500 mb-6" data-aos="fade-up">Proyectos</h2>

  <div class="grid md:grid-cols-2 gap-6">

    <div class="bg-black/50 p-6 rounded-xl shadow-lg hover:scale-105 transition"
         data-aos="fade-right">
      <h3 class="text-xl text-red-400">Proyecto 1</h3>
      <p class="text-gray-400">Aplicación web en desarrollo.</p>
    </div>

    <div class="bg-black/50 p-6 rounded-xl shadow-lg hover:scale-105 transition"
         data-aos="fade-left">
      <h3 class="text-xl text-red-400">Proyecto 2</h3>
      <p class="text-gray-400">Análisis de datos.</p>
    </div>

  </div>
</section>

<!-- HABILIDADES -->
<section id="habilidades" class="max-w-4xl mx-auto py-20 px-6">
  <h2 class="text-3xl text-red-500 mb-6" data-aos="fade-up">Habilidades</h2>

  <div class="space-y-5">

    <div data-aos="fade-right">
      <p>HTML</p>
      <div class="w-full bg-gray-800 h-3 rounded">
        <div class="bg-red-600 h-3 rounded w-[90%] shadow-md"></div>
      </div>
    </div>

    <div data-aos="fade-right" data-aos-delay="100">
      <p>CSS</p>
      <div class="w-full bg-gray-800 h-3 rounded">
        <div class="bg-red-600 h-3 rounded w-[85%] shadow-md"></div>
      </div>
    </div>

    <div data-aos="fade-right" data-aos-delay="200">
      <p>JavaScript</p>
      <div class="w-full bg-gray-800 h-3 rounded">
        <div class="bg-red-600 h-3 rounded w-[75%] shadow-md"></div>
      </div>
    </div>

  </div>
</section>

<!-- CONTACTO -->
<section id="contacto" class="max-w-4xl mx-auto py-20 px-6 text-center">
  <h2 class="text-3xl text-red-500 mb-4" data-aos="fade-up">Contacto</h2>

  <p class="text-gray-400 mb-4">
    abdias.aquise.12@gmail.com
  </p>

  <div class="flex justify-center gap-6 text-2xl" data-aos="zoom-in">

    <a href="#" class="hover:text-red-400"><i class="fab fa-github"></i></a>
    <a href="#" class="hover:text-red-400"><i class="fab fa-linkedin"></i></a>
    <a href="#" class="hover:text-red-400"><i class="fas fa-globe"></i></a>

  </div>

</section>

<!-- FOOTER -->
<footer class="text-center py-6 text-gray-600">
  © 2026 - Abdias Aq
</footer>

<!-- AOS -->
<script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
<script>
AOS.init({
  duration: 1000,
  once: true
});
</script>

</body>
</html>

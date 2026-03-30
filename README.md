<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Abdias Aq | Portafolio Cyber Futurista</title>

<!-- Tipografías futuristas -->
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500;700&family=Roboto:wght@400;500&display=swap" rel="stylesheet">

<!-- Iconos -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
/* RESET */
*{margin:0;padding:0;box-sizing:border-box;}

/* BODY */
body{
    font-family:'Orbitron', 'Roboto', sans-serif;
    background:#010101;
    color:#0a3d62;
    font-size:18px;
    overflow-x:hidden;
}

/* FONDO DIFUMINADO + ELEMENTOS FLOTANTES */
body::before{
    content:"";
    position:fixed;
    width:100%;
    height:100%;
    background: radial-gradient(circle at 20% 30%, #111 0%, #000 100%), 
                radial-gradient(circle at 80% 70%, #222 0%, #000 100%);
    z-index:-1;
}
.floating{
    position:absolute;
    color:#1e90ff22;
    font-size:50px;
    animation:float 10s infinite linear;
    user-select:none;
}
@keyframes float{
    0%{transform:translateY(0px) rotate(0deg);}
    50%{transform:translateY(-30px) rotate(180deg);}
    100%{transform:translateY(0px) rotate(360deg);}
}

/* NAV */
nav{
    position:fixed;
    width:100%;
    padding:15px;
    text-align:center;
    background:rgba(20,20,20,0.85);
    backdrop-filter:blur(5px);
    z-index:10;
}
nav a{
    margin:0 20px;
    color:#0a3d62;
    text-decoration:none;
    font-weight:700;
    font-size:20px;
    transition:0.3s;
}
nav a:hover{color:#1e90ff;}

/* HEADER */
header{
    text-align:center;
    padding:120px 20px 60px;
}
header h1{
    font-size:4.5em;
    color:#0a3d62;
    text-shadow:0 0 20px #0a3d62, 0 0 40px #0a3d6211;
    display:flex;
    justify-content:center;
    align-items:center;
    gap:15px;
}
header p{
    font-size:1.5em;
    margin-top:10px;
    color:#1c1c1c;
}
header .anon-icon{
    font-size:70px;
    color:#0a3d62;
    text-shadow:0 0 15px #0a3d62,0 0 25px #1e90ff,0 0 35px #0a3d62;
}

/* CARDS */
.card{
    background:rgba(30,30,30,0.6);
    backdrop-filter:blur(12px);
    border-radius:18px;
    padding:30px;
    box-shadow:0 0 20px #0a3d6211;
    transition:0.3s;
    margin-bottom:20px;
}
.card:hover{
    transform:translateY(-10px) scale(1.02);
    box-shadow:0 0 35px #1e90ff55;
}

/* SECCIONES */
section{
    max-width:1200px;
    margin:auto;
    padding:60px 20px;
}
h2{
    margin-bottom:25px;
    border-left:6px solid #0a3d62;
    padding-left:12px;
    color:#0a3d62;
    font-size:2.2em;
    font-family:'Orbitron', sans-serif;
}

/* GRID PROYECTOS */
.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:30px;
}
.grid .card{text-align:center;padding:35px;}
.grid .card button{
    margin-top:10px;
    padding:10px 20px;
    border:none;
    border-radius:8px;
    background:#1e90ff;
    color:#fff;
    cursor:pointer;
}

/* SKILLS */
.skill-bar{
    margin:15px 0;
    display:flex;
    align-items:center;
}
.skill-icon{margin-right:12px;font-size:1.6em;}
.bar{
    flex:1;height:14px;background:#111;border-radius:6px;overflow:hidden;
}
.progress{
    height:14px;background:#1e90ff;border-radius:6px;
}

/* LOGROS / CURSOS / IDIOMAS */
.list-item{
    margin:12px 0;
    font-size:18px;
}
.list-item i{margin-right:10px;color:#1e90ff;}

/* REDES */
.redes{text-align:center;margin-top:40px;}
.redes a{
    font-size:36px;
    margin:15px;
    color:#0a3d62;
    transition:0.3s;
}
.redes a:hover{color:#1e90ff;}

/* IA - IACRISS */
#iacriss{margin-top:50px;}
#iacrissChat{
    background:rgba(0,0,0,0.8);
    border-radius:15px;
    padding:15px;
    min-height:250px;
    max-height:350px;
    overflow-y:auto;
    color:#1e90ff;
    font-family:'Orbitron', sans-serif;
    box-shadow:0 0 20px #1e90ff33;
    margin-top:15px;
}
#iacriss input{
    flex:1;
    padding:10px;
    border-radius:8px;
    border:none;
    background:#111;
    color:#0a3d62;
    font-size:16px;
}
#iacriss button{
    padding:10px 20px;
    border:none;
    border-radius:8px;
    background:#1e90ff;
    color:#fff;
    cursor:pointer;
}
</style>
</head>
<body>

<!-- ELEMENTOS FLOTANTES TECNO -->
<i class="fas fa-microchip floating" style="top:10%; left:5%; font-size:60px;"></i>
<i class="fas fa-robot floating" style="top:40%; left:80%; font-size:80px;"></i>
<i class="fas fa-network-wired floating" style="top:70%; left:20%; font-size:50px;"></i>
<i class="fas fa-brain floating" style="top:60%; left:60%; font-size:70px;"></i>

<!-- NAV -->
<nav>
<a href="#inicio">Inicio</a>
<a href="#skills">Skills</a>
<a href="#proyectos">Proyectos</a>
<a href="#logros">Logros</a>
<a href="#contacto">Contacto</a>
<a href="#iacriss">Iacriss</a>
</nav>

<!-- HEADER -->
<header id="inicio">
<h1>Abdias Aq <i class="fas fa-user-secret anon-icon"></i></h1>
<p>Ningún sistema es seguro ⚡ | <a href="mailto:abdias.aquise.12@gmail.com" style="color:#1e90ff; text-decoration:none;">abdias.aquise.12@gmail.com</a></p>
</header>

<!-- HABILIDADES -->
<section id="skills">
<h2>💻 Mejores Tecnologías y Lenguajes</h2>
<div class="card">
<div class="skill-bar"><i class="fab fa-html5 skill-icon"></i>HTML<div class="bar"><div class="progress" style="width:95%"></div></div></div>
<div class="skill-bar"><i class="fab fa-css3-alt skill-icon"></i>CSS<div class="bar"><div class="progress" style="width:90%"></div></div></div>
<div class="skill-bar"><i class="fab fa-js skill-icon"></i>JavaScript<div class="bar"><div class="progress" style="width:85%"></div></div></div>
<div class="skill-bar"><i class="fab fa-python skill-icon"></i>Python<div class="bar"><div class="progress" style="width:80%"></div></div></div>
<div class="skill-bar"><i class="fab fa-java skill-icon"></i>Java<div class="bar"><div class="progress" style="width:75%"></div></div></div>
<div class="skill-bar"><i class="fas fa-robot skill-icon"></i>AI / Machine Learning<div class="bar"><div class="progress" style="width:70%"></div></div></div>
<div class="skill-bar"><i class="fas fa-network-wired skill-icon"></i>Redes & Cloud<div class="bar"><div class="progress" style="width:80%"></div></div></div>
</div>
</section>

<!-- PROYECTOS -->
<section id="proyectos">
<h2>📂 Proyectos Destacados por Semestre</h2>
<div class="grid">
  <div class="card">
    <h3>Semestre 1</h3>
    <p>Proyecto Inicial de HTML/CSS</p>
    <p><strong>Cursos:</strong> HTML Básico, CSS Básico</p>
    <button onclick="alert('Ir al proyecto Semestre 1')">Ver Proyecto</button>
  </div>
  <div class="card">
    <h3>Semestre 2</h3>
    <p>Proyecto Web Interactivo</p>
    <p><strong>Cursos:</strong> HTML Avanzado, CSS Flex/Grid</p>
    <button onclick="alert('Ir al proyecto Semestre 2')">Ver Proyecto</button>
  </div>
  <div class="card">
    <h3>Semestre 3</h3>
    <p>Aplicación JavaScript Dinámica</p>
    <p><strong>Cursos:</strong> JavaScript ES6, DOM, Eventos</p>
    <button onclick="alert('Ir al proyecto Semestre 3')">Ver Proyecto</button>
  </div>
  <div class="card">
    <h3>Semestre 4</h3>
    <p>API Backend en Python</p>
    <p><strong>Cursos:</strong> Python, Flask, REST APIs</p>
    <button onclick="alert('Ir al proyecto Semestre 4')">Ver Proyecto</button>
  </div>
  <div class="card">
    <h3>Semestre 5</h3>
    <p>Proyecto Full Stack</p>
    <p><strong>Cursos:</strong> Node.js, Express, MongoDB</p>
    <button onclick="alert('Ir al proyecto Semestre 5')">Ver Proyecto</button>
  </div>
  <div class="card">
    <h3>Semestre 6</h3>
    <p>Seguridad Web</p>
    <p><strong>Cursos:</strong> OWASP, Seguridad Informática, Pentesting Básico</p>
    <button onclick="alert('Ir al proyecto Semestre 6')">Ver Proyecto</button>
  </div>
  <div class="card">
    <h3>Semestre 7</h3>
    <p>App Python/JS Avanzada</p>
    <p><strong>Cursos:</strong> Python Avanzado, APIs, JS Frameworks</p>
    <button onclick="alert('Ir al proyecto Semestre 7')">Ver Proyecto</button>
  </div>
  <div class="card">
    <h3>Semestre 8</h3>
    <p>Integración de APIs Externas</p>
    <p><strong>Cursos:</strong> APIs REST, JSON, OAuth</p>
    <button onclick="alert('Ir al proyecto Semestre 8')">Ver Proyecto</button>
  </div>
  <div class="card">
    <h3>Semestre 9</h3>
    <p>Proyecto Avanzado Full Stack</p>
    <p><strong>Cursos:</strong> MERN Stack, DevOps Básico</p>
    <button onclick="alert('Ir al proyecto Semestre 9')">Ver Proyecto</button>
  </div>
  <div class="card">
    <h3>Semestre 10</h3>
    <p>Proyecto Final Profesional</p>
    <p><strong>Cursos:</strong> Arquitectura de Software, Cloud, CI/CD</p>
    <button onclick="alert('Ir al proyecto Semestre 10')">Ver Proyecto</button>
  </div>
</div>
</section>

<!-- LOGROS / CURSOS / IDIOMAS -->
<section id="logros">
<h2>🏆 Logros y Cursos</h2>
<div class="card">
<p class="list-item"><i class="fas fa-trophy"></i>Desarrollador web full stack</p>
<p class="list-item"><i class="fas fa-certificate"></i>Curso avanzado de JavaScript</p>
<p class="list-item"><i class="fas fa-certificate"></i>Curso de Python y Data Science</p>
<p class="list-item"><i class="fas fa-certificate"></i>Curso de Seguridad Informática</p>
<p class="list-item"><i class="fas fa-book"></i>Idiomas: Inglés, Portugués, Francés, Italiano</p>
</div>
</section>

<!-- REDES -->
<section id="contacto">
<h2>🌐 Redes Sociales</h2>
<div class="redes">
<a href="https://github.com"><i class="fab fa-github"></i></a>
<a href="https://linkedin.com"><i class="fab fa-linkedin"></i></a>
<a href="https://instagram.com"><i class="fab fa-instagram"></i></a>
</div>
</section>

<!-- IA - IACRISS -->
<section id="iacriss">
<h2>🤖 Iacriss - Guía Interactiva del Portafolio</h2>
<div class="card">
<p>Pregunta a Iacriss y te guiará por el portafolio:</p>
<div id="iacrissChat"><p><em>Iacriss está lista para guiarte...</em></p></div>
<div style="display:flex; gap:10px; margin-top:15px;">
<input type="text" id="iacrissInput" placeholder="Escribe tu pregunta...">
<button onclick="iacrissResponder()">Enviar</button>
</div>
</div>
</section>

<script>
const iaResponses = {
    "hola": "¡Hola! Soy Iacriss, tu guía en este portafolio.",
    "skills": "¡Vamos a la sección de Skills!", 
    "proyectos": "Te llevo a los proyectos destacados.",
    "logros": "Aquí están todos los logros y cursos que he completado.",
    "contacto": "Esta es la sección de contacto y redes sociales.",
    "inicio": "Regresando a la presentación inicial.",
    "default": "Lo siento, no entiendo eso. Puedes escribir: inicio, skills, proyectos, logros o contacto."
};

function iacrissResponder() {
    const input = document.getElementById("iacrissInput").value.toLowerCase();
    const chatDiv = document.getElementById("iacrissChat");
    
    if(!input) return;
    
    const userMsg = document.createElement("p");
    userMsg.innerHTML = `<strong>Tú:</strong> ${document.getElementById("iacrissInput").value}`;
    userMsg.style.color="#fff";
    chatDiv.appendChild(userMsg);
    
    const response = iaResponses[input] || iaResponses["default"];
    const iaMsg = document.createElement("p");
    iaMsg.innerHTML = `<strong>Iacriss:</strong> ${response}`;
    iaMsg.style.color="#1e90ff";
    iaMsg.style.textShadow = "0 0 5px #1e90ff, 0 0 10px #1e90ff";
    chatDiv.appendChild(iaMsg);

    const sections = ["inicio","skills","proyectos","logros","contacto"];
    if(sections.includes(input)){
        document.getElementById(input).scrollIntoView({behavior:"smooth"});
    }
    
    document.getElementById("iacrissInput").value = "";
    chatDiv.scrollTop = chatDiv.scrollHeight;
}
</script>

</body>
</html>

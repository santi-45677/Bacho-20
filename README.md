<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Problemática Ambiental y de Salud - Plantel 20 del Valle</title>
    <link rel="stylesheet" href="estilos.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <div class="header-content">
            <img src="file:///C:/Users/Santiago%20Rivera/Downloads/LOGOTIPOO.png" alt="Logo que elaboraste para tu empresa">
            <h1><i>Nutrición y Cuidado del Medio Ambiente en Nuestro Plantel</i></h1>
            <h2><i>Colegio De Bachilleres"Matias Romero"Plantel 20 Del Valle</i></h2>
        </div>
        <audio id="himnoAudio" src="file:///C:/Users/Santiago%20Rivera/Downloads/himno.mp3" controls loop></audio>
    </header>

    <main>
        <section id="problematica" class="container">
            <h2><i>Un Bachilleres Más Limpio</i></h2>
            <div class="problem-description">
                <p>La Empresa tiene el proposito de ayudar a el Colegio De Bachilleres "Matias Romero" Plantel 20 Del Valle a que tenga un ambiente mas limpio haciendo conciencia sobre la basura en este y cómo es afectada la alimentación de los estudiantes.</p>
              
            </div>
        </section>

        <section id="soluciones" class="container">
            <h2><i>Propuestas de Solución</i></h2>
            <div class="buttons-grid">
                <button class="solution-btn" data-solution="separacion">
                    <span>Como cuidar el ambiente</span>
                </button>
                <button class="solution-btn" data-solution="huerto">
                    <span>Las tres R</span>
                </button>
                <button class="solution-btn" data-solution="comedores">
                    <span>Educación y concientización</span>
                </button>
                <button class="solution-btn" data-solution="talleres">
                    <span>Mejoras de instalaciones</span>
                </button>
                <button class="solution-btn" data-solution="reforestacion">
                    <span>Alimentación sana</span>
                </button>
            </div>
            <div id="solution-display" class="solution-display">
                </div>
        </section>

        <section id="galeria" class="container">
            <h2><i>Imágenes de Nuestra Comunidad</i></h2>
            <div class="carousel-container">
                <div class="carousel-slide">
                    <img src="![image](https://github.com/user-attachments/assets/bb7d030a-6f1e-4f24-b1bd-3699f66a245f)
" alt="Imagen 1 del plantel">
                    <img src="file:///C:/Users/Santiago%20Rivera/Downloads/img2.jpg" alt="Imagen 2 del plantel">
                    <img src="file:///C:/Users/Santiago%20Rivera/Downloads/img3.jpg"Imagen 3 del plantel">
                    <img src="file:///C:/Users/Santiago%20Rivera/Downloads/img4.jpg" alt="Imagen 4 del plantel">
                    <img src="file:///C:/Users/Santiago%20Rivera/Downloads/img5.jpg" alt="Imagen 5 del plantel">
                    <img src="file:///C:/Users/Santiago%20Rivera/Downloads/img4.jpg" alt"imagen 6 del plantel">
                   </div>
                <button class="carousel-btn prev" aria-label="Anterior">&#10094;</button>
                <button class="carousel-btn next" aria-label="Siguiente">&#10095;</button>
            </div>
        </section>

        <section id="contacto" class="container">
            <h2>Envía tus Sugerencias</h2>
            <p>¡Tu opinión es importante! Ayúdanos a encontrar más soluciones.</p>
            <form id="contactForm">
                <div class="form-group">
                    <label for="name">Nombre:</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Correo Electrónico:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="suggestion">Tu Sugerencia:</label>
                    <textarea id="suggestion" name="suggestion" rows="5" required></textarea>
                </div>
                <button type="submit" class="submit-btn">Enviar Sugerencia</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Integrantes: Aeon Zellhuber Saavedra, Santiago Rivera Becerril grupo:601. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

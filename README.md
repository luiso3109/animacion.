# animacion.
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Programación y sus Ramas</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <h1>Explorando la Programación</h1>
        <nav>
            <ul>
                <li><a href="https://www.youtube.com/watch?v=video1" target="_blank">Inicio</a></li>
                <li><a href="https://www.youtube.com/watch?v=video2" target="_blank">Introducción</a></li>
                <li><a href="https://www.youtube.com/watch?v=video3" target="_blank">Ramas</a></li>
                <li><a href="https://www.youtube.com/watch?v=video4" target="_blank">Conclusión</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="inicio">
            <h2>Bienvenido a la Página de Programación</h2>
            <p>Descubre el fascinante mundo de la programación y sus diversas ramas.</p>
            <img src="imagenes/programming.jpg" alt="Programación">
        </section>
        <section id="introduccion" class="fade-in">
            <h2>Introducción</h2>
            <p>La programación es el proceso de crear un conjunto de instrucciones que le dicen a una computadora cómo realizar una tarea. Se puede hacer usando varios lenguajes de programación, cada uno con sus propias características y usos.</p>
            <img src="imagenes/intro.jpg" alt="Introducción a la Programación">
        </section>
        <section id="ramas">
            <h2>Ramas de la Programación</h2>
            <article class="slide-in">
                <h3>Desarrollo Web</h3>
                <p>El desarrollo web implica la creación de sitios y aplicaciones web. Se divide en desarrollo frontend y backend.</p>
                <img src="imagenes/webdev.jpg" alt="Desarrollo Web">
            </article>
            <article class="slide-in">
                <h3>Desarrollo de Software</h3>
                <p>El desarrollo de software se refiere a la creación de aplicaciones de escritorio y móviles, incluyendo sistemas operativos y aplicaciones empresariales.</p>
                <img src="imagenes/softwaredev.jpg" alt="Desarrollo de Software">
            </article>
            <article class="slide-in">
                <h3>Desarrollo de Juegos</h3>
                <p>El desarrollo de juegos implica la creación de videojuegos para diversas plataformas, incluyendo consolas, PC y dispositivos móviles.</p>
                <img src="imagenes/gamedev.jpg" alt="Desarrollo de Juegos">
            </article>
            <article class="slide-in">
                <h3>Inteligencia Artificial</h3>
                <p>La inteligencia artificial se centra en crear sistemas que puedan aprender y tomar decisiones de manera autónoma.</p>
                <img src="imagenes/ai.jpg" alt="Inteligencia Artificial">
            </article>
        </section>
        <section id="conclusion" class="fade-in">
            <h2>Conclusión</h2>
            <p>La programación es una habilidad valiosa y versátil que abre un sinfín de oportunidades en diversas industrias y disciplinas.</p>
            <img src="imagenes/conclusion.jpg" alt="Conclusión">
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Explorando la Programación. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

header {
    background-color: #333;
    color: white;
    padding: 1em;
    text-align: center;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    background-color: #444;
}

nav ul li {
    margin: 0 1em;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    padding: 1em;
}

main {
    padding: 2em;
    text-align: center;
}

section {
    margin: 2em 0;
    padding: 1em;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

section img {
    max-width: 100%;
    height: auto;
    margin-top: 1em;
    border-radius: 8px;
}

.fade-in {
    opacity: 0;
    transform: translateY(20px);
    animation: fadeIn 2s forwards;
}

.slide-in {
    opacity: 0;
    transform: translateX(-100%);
    animation: slideIn 2s forwards;
}

@keyframes fadeIn {
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes slideIn {
    to {
        opacity: 1;
        transform: translateX(0);
    }
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1em;
    position: fixed;
    width: 100%;
    bottom: 0;
}


creando animacion 

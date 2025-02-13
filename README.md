<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Caples - Capacitación en LESCO</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenido a Caples</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#servicios">Servicios</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio">
        <h2>¿Quiénes somos?</h2>
        <p>Caples es una empresa dedicada a la capacitación en LESCO y asistencia al cliente con inclusión.</p>
    </section>

    <section id="servicios">
        <h2>Nuestros Servicios</h2>
        <ul>
            <li>Clases de LESCO para empresas y particulares</li>
            <li>Asesoría en accesibilidad e inclusión</li>
            <li>Capacitación en servicio al cliente inclusivo</li>
        </ul>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <form>
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" required>

            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" required>

            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Caples - Todos los derechos reservados</p>
    </footer>

    <script src="script.js"></script>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
}

header {
    background: #003366;
    color: white;
    padding: 15px;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
}

form {
    display: flex;
    flex-direction: column;
    width: 50%;
    margin: auto;
}

input, textarea {
    margin: 10px 0;
    padding: 10px;
}

button {
    background: #003366;
    color: white;
    padding: 10px;
    border: none;
    cursor: pointer;
}

footer {
    background: #f1f1f1;
    padding: 10px;
    margin-top: 20px;
}
document.querySelector("form").addEventListener("submit", function(event) {
    event.preventDefault();
    alert("¡Mensaje enviado! Nos pondremos en contacto pronto.");
});



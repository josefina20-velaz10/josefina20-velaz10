## Hi there 👋

<!--
**josefina20-velaz10/josefina20-velaz10** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...[Uploading index.html…]()<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Renta de Casa Vacacional</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <h1>Renta de Casa Vacacional</h1>
    </header>

    <section class="galeria">
        <h2>Galería</h2>
        <div class="imagenes">
            <img src="imagenes_casa/Image4 .jpg" alt="Casa vacacional 1">
            <img src="imagenes_casa/Image7.jpg" alt="Casa vacacional 2">
            <img src="imagenes_casa/Image9.jpg" alt="Casa vacacional 3">
        </div>
    </section>

    <section class="ubicacion">
        <h2>Ubicación</h2>
        <iframe 
            src="https://maps.app.goo.gl/qgR7tZWj4QVPRvPR9 "
            width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy">
        </iframe>
    </section>

    <section class="contacto">
        <h2>Reserva tu estancia</h2>
        <form action="https://formspree.io/f/tu-correo" method="POST">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>

            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email" required>

            <label for="Dia de entrada">Dia de entrada:</label>
            <input type="date" id="Dia de entrada" required>

            <label for="Telefono">Telefono:</label>
            <input type="tel" id="Telefono" required>

            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>© 2025 Renta de Casa Vacacional</p>
    </footer>
    [Uploading script.js…]()document.addEventListener("DOMContentLoaded", function () {
    console.log("Página cargada correctamente.");
});
[Uploading styles.css…]()body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
}

header {
    background-color: #0073e6;
    color: white;
    padding: 20px;
}

h1, h2 {
    margin: 20px 0;
}

.galeria .imagenes {
    display: flex;
    justify-content: center;
    gap: 10px;
    flex-wrap: wrap;
}

.galeria img {
    width: 300px;
    height: 200px;
    border-radius: 10px;
}

.ubicacion iframe {
    width: 80%;
    border-radius: 10px;
}

.contacto {
    background-color: #f4f4f4;
    padding: 20px;
}

form {
    max-width: 400px;
    margin: auto;
    display: flex;
    flex-direction: column;
    gap: 10px;
}

input, textarea {
    width: 100%;
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

button {
    background-color: #0073e6;
    color: white;
    padding: 10px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #005bb5;
}

footer {
    background-color: #333;
    color: white;
    padding: 10px;
}


</body>
</html>

- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

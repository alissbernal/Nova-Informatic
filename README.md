# Nova-Informatic
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nova Informatic</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000;
            color: #fff;
        }
        header {
            background-color: #0078D7;
            color: #fff;
            padding: 20px;
            display: flex;
            align-items: center;
            position: relative;
        }
        header img {
            max-width: 150px;
            margin-right: 20px;
        }
        header h1 {
            margin: 0;
            font-size: 2em;
        }
        header a.contact-link {
            position: absolute;
            right: 20px;
            top: 50%;
            transform: translateY(-50%);
            text-decoration: none;
            background-color: #fff;
            color: #0078D7;
            padding: 10px 15px;
            border-radius: 5px;
            font-size: 0.9em;
            font-weight: bold;
        }
        header a.contact-link:hover {
            background-color: #005bb5;
            color: #fff;
        }
        section {
            padding: 20px;
            margin: 20px auto;
            max-width: 800px;
            background: #333;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.1);
        }
        h2 {
            color: #0078D7;
        }
        .contact-form label {
            display: block;
            margin: 10px 0 5px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #555;
            border-radius: 5px;
            background: #222;
            color: #fff;
        }
        .contact-form button {
            background-color: #0078D7;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #005bb5;
        }
    </style>
</head>
<body>
    <header>
        <img src="imghtml/novainformatic.jpg" alt="Logo de Nova Informatic">
        <h1>Nova Informatic</h1>
        <a href="#contact" class="contact-link">Contacto</a>
    </header>

    <section>
        <h2>Objetivo General</h2>
        <p>Proveer soluciones tecnológicas eficientes y personalizadas que optimicen el rendimiento de los sistemas informáticos de las pequeñas empresas, garantizando la continuidad operativa, la seguridad de la información y el acceso a herramientas digitales que impulsen su crecimiento y competitividad.</p>
    </section>

    <section>
        <h2>Servicios que ofrecemos</h2>
        <ul>
            <li>Reparación de hardware</li>
            <li>Instalación y configuración de nuevos dispositivos y sistemas operativos</li>
            <li>Eliminación de virus</li>
            <li>Seguimiento post-servicio</li>
        </ul>
    </section>

    <section>
        <h2>Compromiso Social</h2>
        <p>En Nova Informatic, nuestro compromiso social se centra en brindar asistencia integral a usuarios y pequeñas empresas. Nos dedicamos a evaluar sus necesidades y realizar diagnósticos iniciales para ofrecer soluciones efectivas y personalizadas. Esto incluye la reparación de fallas en hardware, la instalación y configuración de nuevos dispositivos, así como la instalación de sistemas operativos y eliminación de virus. Además, creemos en la importancia de empoderar a nuestros clientes a través de la capacitación sobre el uso eficiente de la tecnología.</p>
    </section>

    <section>
        <h2>Misión</h2>
        <p>Brindar asistencia a usuarios y pequeñas empresas mediante la evaluación de necesidades, diagnóstico inicial, y resolución de problemas. Esto incluye la reparación de fallas en hardware, la instalación y configuración de nuevos dispositivos, así como la instalación de sistemas operativos y eliminación de virus. También se ofrecerá capacitación sobre el uso eficiente de tecnología y seguimiento post-servicio para garantizar la satisfacción del usuario.</p>
    </section>

    <section>
        <h2>Visión</h2>
        <p>Ser reconocidos como la empresa más confiable y eficaz en la resolución de problemas de hardware y software, instalación de sistemas operativos y eliminación de virus, a través de nuestra dedicación y compromiso con la excelencia.</p>
    </section>

    <section>
        <h2>Valores</h2>
        <ul>
            <li><strong>Responsabilidad:</strong> Porque este valor implica cumplir con nuestras obligaciones y ser conscientes de nuestras acciones.</li>
            <li><strong>Respeto:</strong> Porque respetar a los demás significa valorar sus opiniones, derechos y sentimientos.</li>
            <li><strong>Amabilidad:</strong> Porque ser amable implica tratar a los demás con consideración y empatía. La amabilidad no solo mejora el día de alguien, sino que también crea una cadena de positividad en nuestro entorno.</li>
            <li><strong>Confianza:</strong> Porque la confianza es la base de cualquier relación sólida. Al confiar en los demás y ser confiables nosotros mismos, establecemos conexiones más profundas y significativas.</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contacto</h2>
        <p>Número: <strong>5540288298</strong></p>
        <form class="contact-form">
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name" placeholder="Tu nombre" required>

            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="email" placeholder="Tu correo electrónico" required>

            <label for="message">Mensaje:</label>
            <textarea id="message" name="message" rows="4" placeholder="Escribe tu mensaje"></textarea>

            <button type="submit">Enviar</button>
        </form>
    </section>
</body>
</html>

[web.html](https://github.com/user-attachments/files/22502748/web.html)
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Conceptos Web</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-white font-sans">

    <!-- Header -->
    <header class="bg-white shadow-sm">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <h1 class="text-2xl font-bold text-primary">Conceptos Web</h1>
            <nav class="hidden md:flex space-x-8">
                <a href="#preguntas" class="text-foreground hover:text-primary transition-colors">Preguntas</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-gradient-to-r from-primary to-accent text-white py-20">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-4xl md:text-5xl font-bold mb-6">Aprende los conceptos básicos de la web</h2>
            <p class="text-xl mb-8 max-w-2xl mx-auto">
                Descubre qué son las páginas web, HTTP, cookies, URL y mucho más.
            </p>
        </div>
    </section>

    <!-- Preguntas y Respuestas Section -->
    <section id="preguntas" class="py-16 bg-muted">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center text-foreground mb-12">Preguntas y Respuestas</h2>

            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Pregunta 1 -->
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-xl font-semibold mb-3 text-foreground">¿Qué es una página web?</h3>
                    <p class="text-muted-foreground">
                        Una página web es un documento accesible a través de Internet que puede contener texto, imágenes, videos y enlaces, generalmente escrito en HTML y mostrado mediante un navegador.
                    </p>
                </div>

                <!-- Pregunta 2 -->
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-xl font-semibold mb-3 text-foreground">¿En qué consiste el protocolo HTTP?</h3>
                    <p class="text-muted-foreground">
                        HTTP (HyperText Transfer Protocol) es el protocolo que permite la comunicación entre navegadores y servidores web para solicitar y entregar páginas web y otros recursos.
                    </p>
                </div>

                <!-- Pregunta 3 -->
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-xl font-semibold mb-3 text-foreground">¿Para qué utilizan las Cookies los navegadores web?</h3>
                    <p class="text-muted-foreground">
                        Las cookies son pequeños archivos que los navegadores almacenan para recordar información sobre el usuario, como preferencias, sesiones iniciadas o seguimiento de navegación.
                    </p>
                </div>

                <!-- Pregunta 4 -->
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-xl font-semibold mb-3 text-foreground">¿Qué es la dirección URL y de qué partes se compone?</h3>
                    <p class="text-muted-foreground">
                        La URL (Uniform Resource Locator) es la dirección de un recurso en la web. Se compone de: protocolo (http/https), dominio, ruta, y opcionalmente parámetros y fragmentos.
                    </p>
                </div>

                <!-- Pregunta 5 -->
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-xl font-semibold mb-3 text-foreground">Nombres de protocolos distintos de HTTP</h3>
                    <p class="text-muted-foreground">
                        Algunos ejemplos son HTTPS, FTP, SMTP, IMAP, POP3 y WebSocket, cada uno con distintas funciones en la comunicación de la red.
                    </p>
                </div>

                <!-- Pregunta 6 -->
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-xl font-semibold mb-3 text-foreground">¿Qué es un servidor web y para qué se utilizan?</h3>
                    <p class="text-muted-foreground">
                        Un servidor web es un software y hardware que almacena, procesa y entrega páginas web a los navegadores cuando los usuarios las solicitan.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contacto" class="bg-foreground text-white py-12">
        <div class="container mx-auto px-4 text-center">
            <p>Contacto: contacto@conceptosweb.com | +34 912 345 678 | Madrid, España</p>
            <p class="mt-4 text-muted-foreground">&copy; 2025 Conceptos Web. Todos los derechos reservados.</p>
        </div>
    </footer>

</body>
</html>

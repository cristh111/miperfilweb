<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hoja de Vida</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.8;
            background: #fffafc;
            padding: 20px;
            
            /* Mantener footer al final */
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        main {
            flex: 1; /* Ocupar todo el espacio disponible */
        }

        img {
            border: 5px solid #ff69b4; 
            border-radius: 10px;      
            padding: 5px;             
            background-color: #fff0f6; 
        }

        /* Estilos para el pie de página */
        footer {
            margin-top: 30px;
            padding: 15px;
            text-align: center;
            background-color: #f9f9f9;
            border-top: 2px solid #ccc;
            font-size: 0.9rem;
            color: #333;
        }

        /* Parte 3 y 4 - Tarjetas */
        .tarjeta {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 10px 15px;
            margin-bottom: 15px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }
        h2 {
            color: #ff69b4;
            margin-top: 40px;
            text-align: center;
        }
        .pregunta {
            font-weight: bold;
            color: #333;
        }
        .respuesta {
            color: #555;
            margin-left: 10px;
        }

        /* Parte 5 */
        .contenedor {
            max-width: 900px;
            margin: auto;
            background: #fff;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 0 10px rgba(0,0,0,0.2);
        }
        .proyectos {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }
        .card {
            border: 1px solid #ddd;
            border-radius: 10px;
            padding: 15px;
            text-align: center;
            background: #fafafa;
        }
        .card img {
            width: 100%;
            height: 120px;
            object-fit: cover;
            border-radius: 8px;
        }
        .servicios {
            background: #fff0f6;
            padding: 20px;
            border-radius: 10px;
            margin-top: 30px;
        }
        .servicios p {
            font-size: 18px;
            line-height: 1.5;
        }
    </style>
</head>
<body>
    <main>
        <!-- Parte 1 -->
        <h1>Mi Hoja de Vida</h1>
        
        <ul>
            <li>HTML</li>
            <li>CSS</li>
        </ul>
        
        <p>Estudiante de Aguadas</p>

        <h2>Vista previa en el navegador:</h2>
        <img src="images/Captura.png" alt="Vista previa de la Hoja de Vida" width="600">

        <!-- Parte 3 -->
        <h2>Correcciones de Código</h2>

        <div class="tarjeta">
            <p class="pregunta">❌ &lt;h1&gt;Mi nombre&lt;h1&gt;</p>
            <p class="respuesta">✅ Correcto: &lt;h1&gt;Mi nombre&lt;/h1&gt; 👉 El error era que no se cerró con &lt;/h1&gt;.</p>
        </div>

        <div class="tarjeta">
            <p class="pregunta">❌ &lt;p&gt;Este es un párrafo&lt;p&gt;</p>
            <p class="respuesta">✅ Correcto: &lt;p&gt;Este es un párrafo&lt;/p&gt; 👉 El error era que no se cerró con &lt;/p&gt;.</p>
        </div>

        <div class="tarjeta">
            <p class="pregunta">❌ &lt;img src=imagen.jpg&gt;</p>
            <p class="respuesta">✅ Correcto: &lt;img src="imagen.jpg" alt="Descripción de la imagen"&gt; 👉 Faltaban las comillas y el atributo alt.</p>
        </div>

        <div class="tarjeta">
            <p class="pregunta">❌ colr: blue;</p>
            <p class="respuesta">✅ Correcto: color: blue; 👉 Estaba mal escrito colr, debe ser color.</p>
        </div>

        <div class="tarjeta">
            <p class="pregunta">❌ font sixe: 16px;</p>
            <p class="respuesta">✅ Correcto: font-size: 16px; 👉 Error de escritura, debe ser font-size.</p>
        </div>

        <!-- Parte 4 -->
        <h2>Parte 4 – Quiz Creativo</h2>

        <div class="tarjeta">
            <p class="pregunta">1. ¿Cuál es la diferencia entre &lt;ul&gt; y &lt;ol&gt;?</p>
            <p class="respuesta">👉 &lt;ul&gt; crea listas desordenadas con viñetas, mientras que &lt;ol&gt; crea listas ordenadas con números.</p>
        </div>

        <div class="tarjeta">
            <p class="pregunta">2. ¿Qué hace la propiedad border-radius en CSS?</p>
            <p class="respuesta">👉 Redondea las esquinas de un elemento.</p>
        </div>

        <div class="tarjeta">
            <p class="pregunta">3. ¿Qué propiedad de CSS cambia el color de fondo?</p>
            <p class="respuesta">👉 background-color.</p>
        </div>

        <div class="tarjeta">
            <p class="pregunta">4. ¿Cómo se escribe un comentario en HTML?</p>
            <p class="respuesta">👉 &lt;!-- Esto es un comentario --&gt;.</p>
        </div>

        <div class="tarjeta">
            <p class="pregunta">5. ¿Cuál es la función de la etiqueta &lt;header&gt;?</p>
            <p class="respuesta">👉 Define la cabecera de una página o sección.</p>
        </div>

        <div class="tarjeta">
            <p class="pregunta">6. ¿Qué propiedad CSS se usa para centrar un texto?</p>
            <p class="respuesta">👉 text-align: center;</p>
        </div>

        <div class="tarjeta">
            <p class="pregunta">7. ¿Cuál es la diferencia entre id y class en CSS?</p>
            <p class="respuesta">👉 id es único para un elemento, class puede aplicarse a varios elementos.</p>
        </div>

        <div class="tarjeta">
            <p class="pregunta">8. ¿Qué significa la etiqueta &lt;footer&gt;?</p>
            <p class="respuesta">👉 Representa el pie de página de un documento o sección.</p>
        </div>

        <div class="tarjeta">
            <p class="pregunta">9. ¿Qué etiqueta se usa para insertar una imagen en HTML?</p>
            <p class="respuesta">👉 &lt;img&gt;.</p>
        </div>

        <div class="tarjeta">
            <p class="pregunta">10. ¿Cuál es la etiqueta correcta para un párrafo?</p>
            <p class="respuesta">👉 &lt;p&gt;.</p>
        </div>

        <div class="tarjeta">
            <p class="pregunta">11. ¿Cómo se crea una lista ordenada?</p>
            <p class="respuesta">👉 Con la etiqueta &lt;ol&gt; y dentro &lt;li&gt; para cada ítem.</p>
        </div>

        <div class="tarjeta">
            <p class="pregunta">12. ¿Qué atributo se usa para enlazar una hoja de estilos CSS en HTML?</p>
            <p class="respuesta">👉 rel="stylesheet" dentro de la etiqueta &lt;link&gt;.</p>
        </div>

        <div class="tarjeta">
            <p class="pregunta">13. ¿Qué propiedad de CSS se usa para cambiar el color del texto?</p>
            <p class="respuesta">👉 color.</p>
        </div>

        <div class="tarjeta">
            <p class="pregunta">14. ¿Cómo se centra un texto en CSS?</p>
            <p class="respuesta">👉 text-align: center;</p>
        </div>

        <!-- Parte 5 -->
        <h2>Parte 5 – Mi Página en Papel</h2>
        <div class="contenedor">
            <header style="text-align: center;">
                <h1>Cristian Osorio</h1>
                <img src="images/criss.jpg" alt="Foto de Cristian" width="150">
                <p>Desarrollador de aplicaciones con experiencia en FlutterFlow</p>
            </header>

            <section>
                <h2>Mis Proyectos</h2>
                <div class="proyectos">
                    <div class="card">
                        <img src="images/proyecto1.png" alt="Gallery">
                        <h3>Gallery</h3>
                    </div>
                    <div class="card">
                        <img src="images/proyecto2.png" alt="Phothos">
                        <h3>Phothos</h3>
                    </div>
                    <div class="card">
                        <img src="images/proyecto3.png" alt="Asistencia IERP">
                        <h3>Asistencia IERP</h3>
                    </div>
                </div>
            </section>

            <section class="servicios">
                <h2>Servicios</h2>
                <p>
                    🚀 Desarrollo de aplicaciones móviles en FlutterFlow.<br>
                    💻 Creación de prototipos y diseños personalizados.<br>
                    📲 Asesorías para proyectos digitales.<br>
                    📦 Entregas rápidas y funcionales.
                </p>
            </section>
        </div>
    </main>

    <!-- Parte 2: Siempre al final -->
    <footer>
        <p>Hago constar que la información aquí consignada es verídica y puede ser comprobada por cualquier persona.</p>
        <p>Derechos de Autor <strong>Cristian Osorio Lopez</strong>.</p>
    </footer>
</body>
</html>


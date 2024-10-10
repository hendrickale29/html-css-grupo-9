<!--** <!Doctype html> **: Indicar al navegador que este es un documentos HTML5. -->
<!DOCTYPE html>
<html lang="es">
    <!-- ** <head> **: contiene metadatos sobre el documento, como el titulo y la configuracion de caracteres. -->
<head>
    <!-- ** <meta charset="UTF-8> **: Define la codificacion de cararteres utilizada en el documento. -->
    <meta charset="UTF-8">
    <!-- ** <meta name="viempot" content="width=device-width, initial-scale=1.0"> **: Ayuda a controlar el
     diseño en dispositivos moviles. -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--** <title> **: define el titulo de la página que aparece en la pestaña del navegador. -->
    <title>Primera pagina web grupo 9</title>
</head>
<!--** <body> **: Contiene el contenido visible de la pagina web. -->
<body>
    <!-- ** <header> **: Sección que agrupa la parte superior de la pagina,  -->
    <header>
        <!-- *Uso*: Se utiliza para el titulo principal dentro la seccion definida por el <h1>. Se puede usar
            múltiples veces en un a pagina. -->
        <h1>Bienvenido a mi pagina web</h1>
        <nav>
            <ul>
                <li>
                    <a href="https://www.w3schools.com/" target="_blank">Sobre mi</a>
                </li>
                <li>
                    <a href="contacto.html">Contacto</a>
                </li>
                <li> 
                    <a href="Paginas/Informacion.html">Informacion</a>
                </li>
            </ul>
        </nav>
    </header>
    <!-- ** <section **: Define secciones temátocas en el contenido. -->
    <section>
        <h2>Sobre mi</h2>
        <p>Hola, soy un programador fullstack</p>
        <!-- Aqui se agarra un articulo-->
         <article >
            <h3>Mi trayectoria</h3>
            <p>Desde pequeño he estado interesado en la tecnologia y la programacion</p>
         </article>

         <div>
            <h3>inrereses
                <ul>
                    <li>programacion</li>
                    <li>Fotografias</li>
                    <li>Viajes</li>
                    <li>Videos Juegos</li>
                </ul>
            </h3>
         </div>
    </section>
    <section>
        <h2>Contacto</h2>
        <p>Puedes contactarme a traves de mi correo <a href="mailto:miemail@example.com">miemail@example.com</a></p>
    </section>

    <section>
        <h2>Mis lenguajes de programacion</h2>
        <!-- ** <ul> y <li> **: crea una lista ordena. <li> define cada elemento de la lista. -->
            <ol>
                <li>Html</li>
                <li>CSS</li>
                <li>JavaScrip</li>            
            </ol>
    </section>
    <!--** <footer> **: Sección que contiene información de pie de pagina, como derecho de autor. -->
    <footer>
        <p>&copy: 2024 Mi pagina web. Todos los derechos reselvados</p>
    </footer>
</body>
</html>
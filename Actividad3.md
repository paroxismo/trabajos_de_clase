 ## Actividad 3

 Una pagina web simple usando


 ```
 <!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #333333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: blue;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <section>
        <h2>Imágenes</h2>
        <p>Contenido sobre imágenes...</p>
        <img src="vikingos2.jpg" alt="Descripción de la imagen">
        <img src="vikingos1.jpg" alt="Descripción de la imagen"> 
        <img src="vikingos2.jpg" alt="Descripción de la imagen">
        <img src="vikingos1.jpg" alt="Descripción de la imagen"> 
    </section>

    <section>
        <h2>Videos</h2>
        <p>Contenido sobre videos...</p>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/A2QjentBmh8?si=aWNuDyu0_ColiPb_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
        allowfullscreen></iframe>

        <iframe width="560" height="315" src="https://www.youtube.com/embed/0NAKpzOfVoY?si=74GnpI9oSIBpJJCM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

        <iframe width="560" height="315" src="https://www.youtube.com/embed/DCPU5YWHffM?si=y129tcAqjaByyoHv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

        <iframe width="560" height="315" src="https://www.youtube.com/embed/aTUfR4lCKEE?si=aUA6nU5zfgO1k62l" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

    </section>

    <section>
        <h2>Audios</h2>
        <p>Contenido sobre audios...</p>
        <audio controls>
            <source src="file:///C:/Users/ASUS/Downloads/Gully%20Dreams%20-%20Hanu%20Dixit.mp3" type="audio/mpeg">
            <source src="file:///C:/Users/ASUS/Downloads/Gully%20Dreams%20-%20Hanu%20Dixit.mp3" type="audio/mpeg">
            <source src="file:///C:/Users/ASUS/Downloads/Gully%20Dreams%20-%20Hanu%20Dixit.mp3" type="audio/mpeg">
            <source src="file:///C:/Users/ASUS/Downloads/Gully%20Dreams%20-%20Hanu%20Dixit.mp3" type="audio/mpeg">

    </section>

    <section>
        <h2>iFrames</h2>
        <p>Contenido sobre iframes...</p>
        <iframe src="https://doc-ip.vercel.app/docs/actividades/actividad3" width="600" height="400"></iframe>
        <iframe src="https://www.spacex.com/" width="600" height="400"></iframe>

    </section>

    <footer>
        yerson manuel sierra urbiñez
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>
```
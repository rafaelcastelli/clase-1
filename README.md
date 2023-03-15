# clase-1
<!DOCTYPE html>
<html lang="es">
    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <meta name="description" content="Diseño y nuevos medios" />
        <link href="style.css" rel="stylesheet" />
        <title>&#127891; DNO037</title>
        <!--
        Esto es un comentario de HTML. No es necesario que lo borres.
        Si arriba, dentro de <title></title>, quieres otro emoji, búscarlo en 
        - https://www.w3schools.com/charsets/ref_emoji.asp
        - https://www.w3schools.com/charsets/ref_emoji_smileys.asp
        Usa la columna "Dec" y reemplaza solo el número, manteniendo el "&#" que le antecede.
        -->
    </head>
    <body>

        <main>
            <h1>Nombre Apellido</h1>
            <p>Preséntate en este párrafo, compartiendo la razón por la que tomas este OPR. Intenta ser breve. Este párrafo tiene treinta palabras. Tú puedes agregar más, pero evita superar las cincuenta.</p>
        </main>

        <div id="next"></div>

        <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.5.0/p5.min.js" integrity="sha512-WJXVjqeINVpi5XXJ2jn0BSCfp0y80IKrYh731gLRnkAS9TKc5KNt/OfLtu+fCueqdWniouJ1ubM+VI/hbo7POQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>

        <script>
            // Esto es una línea de comentario en JAVASCRIPT
            var palabras = ["siguiente", "repüyen", "seguente", "suivant", "next", "Nächster", "次の", "다음의"];
            function setup() {
                var palabra = random(palabras);
                createA("page.html?data="+palabra, palabra).parent("next");
                noCanvas();
            }
            /* 
            Esto también es un comentario en JAVASCRIPT
            Se usa así para varias líneas de comentario
            */
        </script>
    </body>
</html>
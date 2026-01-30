1. Manipulacion de elementos del dom en javascript tales como 

getElementByID : se usa para traer elementos del html por medio del id que tenga asignado la etiqueta

querySelector() = Retorna el primer elemento que coincide con un selector CSS.

2. <link rel="preconnect"> o <link rel="preload"> : son directivas de recursos en el <head> HTML para optimizar la velocidad de carga. Usa preload para descargar de inmediato archivos críticos necesarios para la página actual (ej. fuentes, CSS principal).

3. base del head para mejor rendimiento del SEO

  <!-- Metadatos -->
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <meta name="description" content="Esta pagina esta enfocada en gestionar, priorizar y organizar tus tareas pendientes">
            <!-- titulo -->
            <title>
                Todo-list
            </title>
            <!-- Autor  -->
            <meta name="author" content="Aldair Zambrano">
            <!-- Link  -->
            <link rel="stylesheet" href="./index.css">

            <!-- uso del gap  -->

            gap :  es una propiedad de CSS que define el espacio ENTRE los elementos hijos cuando usas Flexbox o Grid.

            ejemplo
            .container {
            display: flex;
            gap: 20px;
            }

            <div class="container">
            <div>Uno</div>
            <div>Dos</div>
            <div>Tres</div>
            </div>

            uso del flex

            el flex nos sirve para controlar el tamaño de los hijos
           
           flex-grow
           ocupa los espacios disponibles
            flex-grow: 1

            errores que cometi

            el uso del margin left top y position para el ajuste de la posicion de los elementos del nav
            
            resumen 
            display: flex activa Flexbox

            El contenedor controla todo

            justify-content y align-items alinean

            gap separa

            flex: 1 reparte espacio
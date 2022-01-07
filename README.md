# Arrowupjs
Arrow up for the web

To see a catalog of arrows and animations go to: arrowupjs.diegosanchez.digital
Para ver un catalogo de flechas y animaciones ir: arrowupjs.diegosanchez.digital


Simple example
<!DOCTYPE html>
<html lang="es" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="https://www.diegosanchez.digital/arrowupjs/arrow.css">
    <title>Arrowup</title>
  </head>
  <body>
    <div id="arrow-up"></div>

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js" charset="utf-8"></script>
  <script src="https://www.diegosanchez.digital/arrowupjs/arrow.js" charset="utf-8"></script>
  <script type="text/javascript">
    var values = {
      img: 'flecha10', //Name of the image you want from the arrow catalog
      position: 'right', //Arrow position on screen. left or right
      size: 'md', //Arrow size. small (sm), medium (md) and large (lg)
      color: '#f3f454', //Indicate color with hexagesimal code
      animation: 'swing'//No animation (none), turn (turn), enlarge (enlarge), swing (swing)
    }
    arrowAdd(values);//Arrow initializer
  </script>
  </body>
</html>



Ejemplo sencillo de flecha

<!DOCTYPE html>
<html lang="es" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="https://www.diegosanchez.digital/arrowupjs/arrow.css">
    <title>Flecha de subida</title>
  </head>
  <body>
    <div id="arrow-up"></div>

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js" charset="utf-8"></script>
  <script src="https://www.diegosanchez.digital/arrowupjs/arrow.js" charset="utf-8"></script>
  <script type="text/javascript">
    var values = {
      img: 'flecha10', //Nombre de la imagen que se desea del catálogo de flechas
      position: 'right', //Posición en pantalla de la flecha. Izquierda (left) o derecha (right)
      size: 'md', //Tamaño de la flecha pequeña (sm), mediana (md) y grande (lg)
      color: '#f3f454', //Indicar color con codigo hexagesimal
      animation: 'swing'//Sin animacion (none), giro (turn), ampliacion (enlarge), balanceo (swing)
    }
    arrowAdd(values);//Inicializador de la flecha
  </script>
  </body>
</html>

# avaluaciowaldeycidet

# Descripción

Esta es una avalucio de CIDET de código HTML con CSS y JS DOM para mostrar imágenes grandes y pequeñas y cambiar la imagen grande al pasar el mouse sobre las imágenes pequeñas utilizando mouseover.

## Uso

1. Descarga los archivos de imagen (`sneaker_1200_A.webp`, `sneaker_1200_B.webp`, `sneaker_1200_C.webp` y `sneaker_1200_D.webp`) y colócalos en la carpeta `img`.
2. Abre el archivo `index.html` en tu navegador.

## Código HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Class</title>
</head>
<style>
  /* global */
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body{
    background-color: #fdfdfd;
    color: #fff;
    font-family: Arial, Helvetica, sans-serif;
  }

  .container{
    display: flex;
  }

  .imglarge{
    width: 1400px;
    height: 860px;
    background-color: #fff;
    margin: 10px;
  }

  .imgsmall{
    display: flex;  
    flex-direction: column;
  }

 .box{
   width: 400px;
   height: 200px;
   background-color: #fff;
   margin: 10px;
 }

 .first{
   background: url(img/sneaker_350_A.webp) no-repeat scroll center center;
   background-size: 300px 200px;
 }

 .second{
   background: url(img/sneaker_350_B.webp) no-repeat scroll center center;
   background-size: 300px 200px;
 }

  .third{
    background: url(img/sneaker_350_C.webp) no-repeat scroll center center;
    background-size: 300px 200px;
  }

  .fourth{
    background: url(img/sneaker_350_D.webp) no-repeat scroll center center;
    background-size: 300px 200px;
  }

</style>
<body>

  <div class="container">
    <!-- imagenes pequeñas -->
    <div class="imgsmall">
      <div class="box first"></div>
      <div class="box second"></div>
      <div class="box third"></div>
      <div class="box fourth"></div>
    </div>

    <!-- imagen grande -->
    <div class="imglarge"></div>

  </div>
  
  </body>

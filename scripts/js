// Código del conmutador de imágenes

deja    myImage    =    documento   .   querySelector   (   'img'   )   ;

myImage   .   onclick    =    function   (   )    {
  deje    mySrc    =    myImage   .   getAttribute   (   'src'   )   ;
  if   (   mySrc    ===    'images / firefox-icon.png'   )    {
    myImage   .   setAttribute    (   'src'   ,   'imágenes / firefox2.png'   )   ;
  }    más  {
    myImage   .   setAttribute    (   'src'   ,   'imágenes / firefox-icon.png'   )   ;
  }
}

// Código de mensaje de bienvenida personalizado

deje    myButton    =    documento   .   querySelector   (   'botón'   )   ;
deje    myHeading    =    documento   .   querySelector   (   'h1'   )   ;

function    setUserName   (   )    {
  let    myName    =    prompt   (   'Por favor ingrese su nombre.'   )   ;
  if   (   !   myName   )    {
    setUserName   (   )   ;
  }    más  {
    localStorage   .   setItem   (   'nombre'   ,    miNombre   )   ;
    myHeading   .   innerHTML    =    'Mozilla es genial,'    +    myName   ;
  }
}

if   (   !   localStorage   .   getItem   (   'nombre'   )   )    {
  setUserName   (   )   ;
}    más  {
  deje    almacenadoNombre    =    localStorage   .   getItem   (   'nombre'   )   ;
  myHeading   .   innerHTML    =    'Mozilla es genial,'    +   nombre    almacenado   ;
}

myButton   .   onclick    =    function   (   )    {
  setUserName   (   )   ;
}

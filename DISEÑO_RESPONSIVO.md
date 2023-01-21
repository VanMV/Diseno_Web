Diseño Responsivo es que se pueda ver bien en una computadora, celular y tablet
Nuevo documento html con css
Agregar las 3 etiquetas principales: header, main, footer
Agregamos h1 que diga "Design Responsive"
Agregamos en el main, 3 etiquetas div y dentro del div un h2 y una imagen. 
           <main>
                  <div>
                      <h2>1024px en adelante</h2>
                      <img src="img/compu.jpg" alt="">
                  </div>

Una div por cada imagen: Compu, tablet y cel
  
En CSS, al header le metemos:
            header{
              width: 90%;                                     **
              margin: auto;                                   ** el 10% que resta lo distribuya automaticamente
              height: 30vh;                                   30% de toda la pantalla
              background-color: lightgray;
              display: flex;                                  ** para manipular uno a lado de otro
              justify-content: center;                        ** alinear al centro de ancho
              align-items: center;                            ** alinear al centro de alto
          }
  
            h1{
              color: lightgray;                               **mismo color que el fondo para que la siguiente instrucción le de estilo de contorno
              -webkit-text-stroke: 2px black;;                **para ponerle un contorno
              font-size: 3em;                                 **agrandar las letras    
              letter-spacing: 10px;                           **espacio entre cada letra
              text-shadow: 0 0 5px gray;                      **sombrita en las letras
          }
  ![image](https://user-images.githubusercontent.com/113804525/213888719-593d3a07-b5c8-4f15-a863-cf539e2325b0.png)

En CSS. en main
            main{
                  height: 60vh;                                                         **en header ya pusimos 30vh, ahora 60vh y quedan 10vh para el footer
                  display: flex;
                  align-items: center;
                  justify-content: space-between; distribuir en la pantalla
              }
  
  **************  vh vectores a lo alto
  **************  em tamaño original x veces
  
            footer .img1{
                  width: 10%;
                  display: block;                   **muestra la imagen
              }
            footer .img2{
                  width: 10%;
                  display: none;                    **no muestres la imagen
              }
  
  
Así se vería en tamaño de celular  
  
  ![image](https://user-images.githubusercontent.com/113804525/213889683-c26c0046-5fc8-4dc1-97bf-b1568e6900fb.png)

Hay que adaptarlo en css
  

*** UTILIDAD DE FORMULARIOS ***

1. Recibir datos por correo electrónico
2. Nutrir la página, como un carrito de comprar en Amazon
3. Que los datos se vayan a una base de datos

La etiqueta es FORM

Action significa a donde vas a enviar el formulario, pondremos el nombre de un archivo que va a recibir los datos del formulario.
METHOD significa como se va a enviar los datos
Si no indicas los atributos, solo se van a la página.

![image](https://user-images.githubusercontent.com/113804525/202875253-72175091-673d-4c55-bca0-f3d97da35b68.png)

Para pedir Nombre agregamos "input" de tipo TEXT

Para darle un ejemplo al usuario, usamos un atributo llamado "placeholder"

![image](https://user-images.githubusercontent.com/113804525/202875302-f7b5df0f-1087-40f6-94b7-07aebe39ebae.png)
![image](https://user-images.githubusercontent.com/113804525/202875307-bc484f20-8fcb-4df3-9284-525f9c737d56.png)

MINLEGTH para un mínimo de caracteres

MAXLENGTH para un máximo de cara caracteres

REQUIRED para llenar el dato forzozamente

![image](https://user-images.githubusercontent.com/113804525/202875436-c2486050-8c47-4d0b-8cf1-98d282072c04.png)
![image](https://user-images.githubusercontent.com/113804525/202875421-a056df82-5ac2-4b1e-814b-821fa7534a01.png)

Para pedir Teléfono agregamos "input" de tipo TEL

![image](https://user-images.githubusercontent.com/113804525/202875576-57caffc2-7039-4dfa-896f-e68d17cced21.png)
![image](https://user-images.githubusercontent.com/113804525/202875586-54ffb426-1067-4b90-af52-cace95111c8a.png)

VALUE para dar un dato previo como el LADA +52 ![image](https://user-images.githubusercontent.com/113804525/202875648-a488a42f-54ac-4342-93c1-699d88357e7d.png)

Para pedir CORREO agregamos "input" de tipo email... tipo EMAIL se asegura que al menos tenga un arroba @

![image](https://user-images.githubusercontent.com/113804525/202875731-a9f38f9c-03e7-48d6-99ff-02e8512550b4.png)
![image](https://user-images.githubusercontent.com/113804525/202877476-130d5d5f-9aa0-404c-a5d4-417803b85536.png)


Tipo RADIO para seleccionar entre opciones (CIRCULITO)

![image](https://user-images.githubusercontent.com/113804525/202875893-6e272ad9-abb6-4b0b-9bc8-5e5cb46f8852.png)
![image](https://user-images.githubusercontent.com/113804525/202876029-537654c0-54bd-4c11-8059-7648e5b12be1.png)

Mismo NAME para seleccionar uno u otro   |    Diferente NAME para seleccionar uno o todos

![image](https://user-images.githubusercontent.com/113804525/202876000-5a85b73b-463d-40c3-9124-41d6c0a46189.png)
![image](https://user-images.githubusercontent.com/113804525/202876016-c80b06e8-4641-4372-a663-b58729aa34aa.png)

TEXTAREA para habilitar un cuadro de texto libre

![image](https://user-images.githubusercontent.com/113804525/202876635-7ddf07e5-00bd-4772-ad53-cbf34451f4d3.png)
![image](https://user-images.githubusercontent.com/113804525/202876648-1a7508d2-98a4-44e5-baa9-aecf5fdba70b.png)

INPUT tipo DATE para fecha

![image](https://user-images.githubusercontent.com/113804525/202877763-43e93941-252e-4a67-bbf9-d9b9fed399a7.png)
![image](https://user-images.githubusercontent.com/113804525/202877767-215bda36-a9bd-4b0b-bc50-3c9b3edc52da.png)


SELECT  crea una lista desplegable, el value es lo que nosotros asignamos y las letras blancas, lo que ve el usuario para escoger

![image](https://user-images.githubusercontent.com/113804525/202876809-3ac7e80f-df70-4dd5-a388-1d4717933b20.png)
![image](https://user-images.githubusercontent.com/113804525/202876827-96b6bb41-6c81-4299-9a38-9cf240d4f9e0.png)


INPUT tipo NUMBER para que indiquen el número

![image](https://user-images.githubusercontent.com/113804525/202876933-b9602e0d-acdf-4e20-836c-b7462861a750.png)
![image](https://user-images.githubusercontent.com/113804525/202876957-f9f0f5ed-b5d3-4d03-a754-e280f4b92970.png)

INPUT tipo CHECKBOX para agregar complementos

![image](https://user-images.githubusercontent.com/113804525/202877116-58b8cef4-751b-4188-b4a6-f1059ba3feee.png)
![image](https://user-images.githubusercontent.com/113804525/202877040-4a10d62e-9c3e-406e-a587-4e470e83b8e9.png)

INPUT tipo SUBMIT para un botón que envíe los datos
INPUT tipo RESET para resetear el formulario

![image](https://user-images.githubusercontent.com/113804525/202877436-1b20c030-3754-4330-bf94-20dbb9ce5507.png)
![image](https://user-images.githubusercontent.com/113804525/202877444-17edfba3-e9c7-47b7-9a9f-226934f4b36d.png)


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario</title>
</head>
<body>
    <H1>FORMULARIO DE TAQUERIA</H1>
    <H2>Menú</H2>
    <h3>Tacos</h3>
    <ul>
        <li>Pastor......................$ 15</li>
        <li>Suadero...................$ 15</li>
        <li>Tripa.......................$ 15</li>
        <li>Bistec......................$ 15</li>
        <li>Arrachera................$ 15</li>
    </ul>
    <h3>Especialidades</h3>
    <dl>
        <dt>Con piña.......................$ 20</dt>
        <dd>con rebanadas de piña dulce</dd>
        <dt>Con queso....................$ 20</dt>
        <dd>americano, manchego o gouda</dd>
        <dt>Piña y queso.................$ 20</dt>
        <dd>americano, manchego o gouda y rodajas de piña dulce</dd>
        <dt>Volcanes......................$ 20</dt>
        <dd>tostada con queso gratinado</dd>
    </dl>
    <h2>¡HAZ TU PEDIDO AHORA!</h2>
    <!-- FORM es para iniciar los formularios -->
    <!-- ACTION es a donde envias los datos -->
    <!-- METHOD es como se envian los datos -->
    <form action="" method="">
        <!-- INPUT tipo TEXT para habilitar el cuadro para ingresar texto -->
        <!-- INPUT tipo TEL para habilitar el cuadro para número -->
        <!-- INPUT tipo EMAIL para habilitar el cuadro para correo electrónico -->
        <!-- PLACEHOLDER para dar un ejemplo al usuario como tipo marca de agua, ayuda visual -->
        <!-- MINLEGTH para un mínimo de caracteres -->
        <!-- MAXLENGTH para un máximo de cara caracteres -->
        <!-- REQUIRED para llenar el dato forzozamente -->
        Nombre <input type="text" placeholder="Ejemplo: Juan Pérez" minlength="3" maxlength="30" required> <br><br>
        <!-- VALUE para dar un dato previo como la LADA +52-->
        Teléfono <input type="tel" min="10" max="10" placeholder="Sin LADA, solo números" value="+52"> <br><br>
        <!-- El tipo EMAIL es para asegurarse que tenga un @ -->
        Correo <input type="email" placeholder="abc123@hotmail.com">
        <p>¿Es para llevar o comer en local?</p>
        <!-- RADIO para seleccionar entre opciones -->
        <!-- Mismo NAME para seleccionar uno u otro -->
        <!-- Diferente NAME para seleccionar uno o todos -->
        <input type="radio" value="Llevar" name="Llevar"> Para llevar <br>
        <input type="radio" value="Local" name="Llevar"> Para comer en el local
        <!-- TEXTAREA para un cuadrito que ingresen texto libre -->
        <P>Ingresa tu dirección</P> <textarea name="" id="" cols="40" rows="5" placeholder="Calle y número, Colonia, C.P."></textarea> <br><br>
        
        <!-- INPUT tipo DATE para fecha  -->
        ¿Para cuándo es tu orden?
        <input type="date" value="2022-11-19" min="2022-11-19" max="2022-12-31">
        
        <br><br>
        ELIGE TUS TACOS<br>
        <!-- SELECT para una lista desplegable -->
        <!-- VALUE es lo que vas a recibir, pero no se ve en página -->
        <select name="ORDEN 1" id="">
            <option value="Pastor">Pastor</option>
            <option value="Suadero">Suadero</option>
            <option value="Tripa">Tripa</option>
            <option value="Bistec">Bistec</option>
            <option value="Arrachera">Arrachera</option>
        </select>
        <!-- INPUT tipo NUMER para escoger un número de tacos -->
        <input type="number" min="1" max="20">
        <!-- INPUT tipo CHECKBOX para agregar complementos -->
        <input type="checkbox" value="limones" name="Si"> limones
        <input type="checkbox" value="cebolla" name="Si"> cebolla
        <input type="checkbox" value="cilantro" name="Si"> cilantro
        <input type="checkbox" value="verde" name="Si"> salsa verde
        <input type="checkbox" value="roja" name="Si"> salsa roja

        <br>

        <select name="ORDEN 2" id="">
            <option value="Pastor">Pastor</option>
            <option value="Suadero">Suadero</option>
            <option value="Tripa">Tripa</option>
            <option value="Bistec">Bistec</option>
            <option value="Arrachera">Arrachera</option>
        </select>
        <!-- INPUT tipo NUMER para escoger un número de tacos -->
        <input type="number" min="1" max="20">
        <!-- INPUT tipo CHECKBOX para agregar complementos -->
        <input type="checkbox" value="limones" name="Si"> limones
        <input type="checkbox" value="cebolla" name="Si"> cebolla
        <input type="checkbox" value="cilantro" name="Si"> cilantro
        <input type="checkbox" value="verde" name="Si"> salsa verde
        <input type="checkbox" value="roja" name="Si"> salsa roja

        <br>

        <select name="ORDEN 3" id="">
            <option value="Pastor">Pastor</option>
            <option value="Suadero">Suadero</option>
            <option value="Tripa">Tripa</option>
            <option value="Bistec">Bistec</option>
            <option value="Arrachera">Arrachera</option>
        </select>
        <!-- INPUT tipo NUMER para escoger un número de tacos -->
        <input type="number" min="1" max="20">
        <!-- INPUT tipo CHECKBOX para agregar complementos -->
        <input type="checkbox" value="limones" name="Si"> limones
        <input type="checkbox" value="cebolla" name="Si"> cebolla
        <input type="checkbox" value="cilantro" name="Si"> cilantro
        <input type="checkbox" value="verde" name="Si"> salsa verde
        <input type="checkbox" value="roja" name="Si"> salsa roja

        <br>

        <select name="ORDEN 4" id="">
            <option value="Pastor">Pastor</option>
            <option value="Suadero">Suadero</option>
            <option value="Tripa">Tripa</option>
            <option value="Bistec">Bistec</option>
            <option value="Arrachera">Arrachera</option>
        </select>
        <!-- INPUT tipo NUMER para escoger un número de tacos -->
        <input type="number" min="1" max="20">
        <!-- INPUT tipo CHECKBOX para agregar complementos -->
        <input type="checkbox" value="limones" name="Si"> limones
        <input type="checkbox" value="cebolla" name="Si"> cebolla
        <input type="checkbox" value="cilantro" name="Si"> cilantro
        <input type="checkbox" value="verde" name="Si"> salsa verde
        <input type="checkbox" value="roja" name="Si"> salsa roja

        <br><br>

        <!-- INPUT tipo SUBMIT para un botón que envíe los datos -->
        <!-- INPUT tipo RESET para resetear el formulario -->
        <input type="submit" value="ORDENA"> 
        <input type="reset" value="ACTUALIZAR">

    </form>
   
    <form action="">
        <!-- INPUT tipo COLOR para escoger colores-->
        Escoge un color
        <input type="color"> <br><br>
        <!-- INPUT tipo PASSWORD pone puntitos para esconder los caracteres -->
        Password
        <input type="password"> <br><br>
        
        <!-- INPUT tipo FILE para subir un archivo -->
        <input type="file">

    </form>
</body>
</html>

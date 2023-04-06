# Proyecto-Final-Python-Loscalzo Bruno Facundo.
Este proyecto es desarrollado en Python utilizando el framework Django. 
El proyecto trata de una app web la cual va a renderizar la información que se encuentra almacenada en nuestra base de datos y la va a mostrar en las diferentes vistas dependiente cual sea nuestra necesidad.

# Video Demostración.
https://drive.google.com/file/d/1hda0fNsDWiLLLGxU-A-Ppwtj4uiP_zWB/view?usp=sharing

# Inicio

1. Pararse en la carpeta del proyecto

    ```
    cd Proyecto-Final-Python-Loscalzo-Bruno-Facundo
    ```

2. Ejecutar

    ```
    python manage.py runserver
    ```

    para levantar el servidor

3. Abrir el navegador en la dirección http://localhost:8000/AppCoder

# Uso

Rutas: 
 - /AppCoder/ Home de la página. Desde aquí se puede tanto iniciar sesión con un usuario ya creado o crear un nuevo usuario para poder loguearse.
 
# Una vez Logueado

 - /AppCoder/leerMascota nos permite ver nuestra base de datos de Mascotas ingresadas, con el botón "Agregar" podemos agregar un nuevo registro (Nombreanimal, Edad, Tipo, Motivo, Fecha y costo).
 Desde aquí mismo podemos "Borrar" o "Actualizar" cualquiera de nuestros registros dándole click sobre su botón correspondiente. 
 - /AppCoder/leerPersona nos permite ver nuestra base de datos de Dueños ingresados, con el botón "Agregar" podemos agregar un nuevo registro (Nombre, Apellido y Teléfono).
 Desde aquí mismo podemos "Borrar" o "Actualizar" cualquiera de nuestros registros dándole click sobre su botón correspondiente.
 - /AppCoder/leerVeterinario/ nos permite ver nuestra base de datos de Profesionales ingresados, con el botón "Agregar" podemos agregar un nuevo registro (Nombre, Apellido y Matricula).
 A diferencia de los formularios anteriores, en este solo vamos a poder dar de alta nuevos profesionales, para modificar o dar de baja un profesional se tendrá que solicitar permiso a usuario con permisos de superusuario.
 - AppCoder/busquedaMascota nos permite buscar en nuestra base de datos de Mascotas a través del nombre de la misma.
 - Botón DropDown:
    - Editar Perfil: Nos permite actualizar el mail del usuario.
    - Agregar Avatar: Nos permite agregar o cambiar nuestro Avatar.
    - Cerrar Sesión: Finaliza la sesión.
 - Botones redes sociales: Haciendo click sobre cualquiera de los tres iconos (Facebook, Twitter o Instagram) nos redirigirá a la red social solicitada.

 - /admin/ se utiliza para acceder al panel de administrador.
Para acceder al panel de administrador usar:
Usuario admin - Password admin123

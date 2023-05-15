# How To Use Git

En este tutorial aprenderas como iniciarte en el uso Git de forma simple.

# Paso 1.
Crea una cuenta en https://github.com/signup?source=login

# Paso 2.
Desarrolla el turorial Hello world
https://guides.github.com/activities/hello-world/

# Paso 3
**Control de versiones de proyectos y tesis**

Instala Github desktop para mantener el control de versiones de tu tesis y de los proyectos del lab.  
[Desktop Github Download](https://desktop.github.com/) 

[Información instalación Github desktop avanzado](https://docs.github.com/es/desktop/installing-and-configuring-github-desktop/installing-github-desktop)

## Configurar tu cuenta de Git (nombre de usuario y mail) en tu desktop

Esto es importante porque cualquier cambio que hagas a un repositorio requiere que los "commits" de Git tengan esta información.

**Configurar globalmente para todos los repositorios actuales y futuros*

En la terminal ejecuta los siguientes comandos para modificar el siguiente archivo (~/.gitconfig):

      git config --global user.name "Your Name Here"  
      git config --global user.email "your@email.com"

Comprueba tu configuración con 

      git config --list

# Paso 4.
**Crear Personal access tokens (classic)** 
Desde el 13 de agosto de 2021 será necesario crear un token para usar github desde tu PC. Este token no reemplaza, cambia, ni elimina tu password para acceder a github, pero es necesario para poder realizar cambios (push) o clonar (clone) un repositorio. 

Para crear un token sigue estas [instrucciones](https://docs.github.com/es/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token). Guarda tu token en un lugar seguro, pues lo necesitarás cada vez que desees **clonar** un repositorio o cuando hagas un **push**.

# Paso 5 (Opcional)
Si deseas integrar Rstudio Desktop con Github puedes siguir este tutorial
https://youtu.be/JN6rzv4zSJ4

# Paso 6 (Opcional)

Para clonar un repositorio de tu perfil de hithub a tu computadora. Ejecuta este comando este comando en la terminal (cambia tu nombre de usuario y nombre de repositorio antes de clonar).

      git clone https://github.com/YourUserNameHere/RepoNameHere.git
      Username: Tu_nombre_de_usuario_aqui
      Password: Tu_token_aquí

# Paso 7 (Opcional)

Para realizar un pull/push a un repositorio. Ejecuta los siguientes comandos en la terminal (recuerda reemplazar tu token y tu repositorio):

      git pull https://<TU_TOKEN_AQUI>@github.com/<NOMBRE_REPOSITORY_AQUI>.git
      git push https://<TU_TOKEN_AQUI>@github.com/<NOMBRE_REPOSITORY_AQUI>.git
    
Ejemplo uso de token en el repositorio **Protocolos** de nuestro laboratorio:    
    
   ![image](https://user-images.githubusercontent.com/70146916/129455914-93994ff7-78f2-4961-8a3b-ed00840a889a.png)

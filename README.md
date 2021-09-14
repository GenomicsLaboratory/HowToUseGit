# How To Use Git

En este tutorial aprenderas como iniciarte en el uso Git de forma simple.

# Paso 1.
Crea una cuenta en https://github.com/

# Paso 2.
Desarrolla el turorial Hello world

https://guides.github.com/activities/hello-world/

# Paso 3
Instala git en tu desktop

[Download git](https://docs.github.com/es/desktop/installing-and-configuring-github-desktop/installing-github-desktop)

## Configurar tu cuenta de Git (nombre de usuario y mail) en tu desktop

Esto es importante porque cualquier cambio que hagas a un repositorio requiere que los "commits" de Git tengan esta información.

**Configurar globalmente para todos los repositorios actuales y futuros*

En la terminal ejecuta los siguientes comandos para modificar el siguiente archivo (~/.gitconfig):

git config --global user.name "Your Name Here"  
git config --global user.email "your@email.com"

Comprueba tu configuración con 

git config --list

# Paso 4.
**Crear y usar token** 
Desde el 13 de agosto de 2021 será necesario crear un token para usar github desde tu PC. Este token no reemplaza, cambia, ni elimina tu password para acceder a github, pero es necesario para poder realizar cambios (push) o clonar (clone) un repositorio. 

Para crear un token sigue estas [instrucciones](https://docs.github.com/es/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token). Guarda tu token en un lugar seguro, pues lo necesitarás cada vez que desees **clonar** un repositorio o cuando hagas un **push**.

Ejemplo clonar un repositorio de tu perfil. Ejecuta este comando este comando en la terminal.

        git clone https://github.com/YourUserNameHere/RepoNameHere.git
        Username: your_username
        Password: your_token

Ejemplo realizar un push a un repositorio. Ejecuta este comando este comando en la terminal:

    git push https://<TU_TOKEN_AQUI>@github.com/<NOMBRE_REPOSITORY_AQUI>.git
    
Ejemplo uso de token en el repositorio Protocolos de nuestro laboratorio:    
    
   ![image](https://user-images.githubusercontent.com/70146916/129455914-93994ff7-78f2-4961-8a3b-ed00840a889a.png)



# Paso 5
Si deseas integrar Rstudio con Git sigue este tutorial
https://youtu.be/JN6rzv4zSJ4

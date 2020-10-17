# Instalación y configuración basica de git.

Para esta configuracion he siguido el taller de git que hizo el Deiit en el siguiente [enlace](https://www.youtube.com/watch?v=W5nfCKC0IBM).

## Instalación.



## Cofiguraciones globales git.

### Añadimos nuestro nombre de usuario y nuestro correo, para que cuando hagamos algun commit salga nuestro usuario de forma correcta para ello usamos los dos siguientes comandos que salen en la imagen:

  ![Configuraciones globales git]()

# Creación llave pública/privada.

## Creamos todo lo necesario en nuestro pc.

### Lo primero es crear las claves para ello he usado la siguiente [guía](https://docs.github.com/es/free-pro-team@latest/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent).

1. Genero mis claves:
   
   ![Genero mis claves]() 
   

2. Iniciamos y agregamos la llave privada a nuestro ssh-agent:
   
   ![ssh-agent]() 
   

## Introducir clave ssh en github.

Copiamos la clave pública en el apartado de Settings SSH and  GPP keys de GitHub:
1. Le damos a new ssh key y pegamos la clave pública copiada de nuestro equipo y la guardamos.
   
   ![SSH GitHub](https://github.com/kaizensamuel/Proyecto-CC-20-21/blob/main/imgs/s1-configuraciones/github-ssh.png) 

# Creación y configuración de repositorios para la asignatura.

He creado dos repositorios para la asignatura:

1. Repositorio para los ejercicios:
   
   ![Repo para los ejercicios]() 

2. Repositorio para el proyecto de la asignatura:
   
   ![Repo para el proyecto]() 

y por último he echo fork del proyecto de la asignatura:

![Repo para el proyecto]() 
   
## Configuro el remoto para la copia local del repositorio de la asignatura. (Para esto se usa la orden de puesta en el repositorio de la asignatura)
1.  Añado el remoto: 
    
    ![Remoto]() 

2. Actualizo mi repo local con el remoto:
   
   ![Actualizar remoto]()


# Adicional: Creacion de git-pages para nuestro proyecto. Para esto he seguido la siguiente [guía](https://docs.github.com/es/free-pro-team@latest/github/working-with-github-pages/creating-a-github-pages-site).

Para esto tenemos que crear una rama:

  ![Direccion gh-pages del proyecto]()

# Perfil configurado:
![Perfil GitHub](https://github.com/kaizensamuel/Proyecto-CC-20-21/blob/main/imgs/s1-configuraciones/perfil.png) 
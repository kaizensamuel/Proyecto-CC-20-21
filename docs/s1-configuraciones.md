# Instalación y configuración basica de git.

Para esta configuracion he siguido el taller de git que hizo el Deiit en el siguiente [enlace](https://www.youtube.com/watch?v=W5nfCKC0IBM).

## Instalación.

![Instalacion git](https://github.com/kaizensamuel/Proyecto-CC-20-21/blob/main/imgs/s1-configuraciones/install-git.png)
  

## Cofiguraciones globales git.

### Añadimos nuestro nombre de usuario y nuestro correo, para que cuando hagamos algun commit salga nuestro usuario de forma correcta para ello usamos los dos siguientes comandos que salen en la imagen:

  ![Configuraciones globales git](https://github.com/kaizensamuel/Proyecto-CC-20-21/blob/main/imgs/s1-configuraciones/global-config-git.png)

# Creación llave pública/privada.

## Creamos todo lo necesario en nuestro pc.

### Lo primero es crear las claves para ello he usado la siguiente [guía](https://docs.github.com/es/free-pro-team@latest/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent).

1. Genero mis claves:
   
   ![Genero mis claves](https://github.com/kaizensamuel/Proyecto-CC-20-21/blob/main/imgs/s1-configuraciones/claves-ssh-generadas.png) 
   

2. Iniciamos y agregamos la llave privada a nuestro ssh-agent:
   
   ![ssh-agent](https://github.com/kaizensamuel/Proyecto-CC-20-21/blob/main/imgs/s1-configuraciones/ssh-agent.png) 
   

## Introducir clave ssh en github.

Copiamos la clave pública en el apartado de Settings SSH and  GPP keys de GitHub:
1. Le damos a new ssh key y pegamos la clave pública copiada de nuestro equipo y la guardamos.
   
   ![SSH GitHub](https://github.com/kaizensamuel/Proyecto-CC-20-21/blob/main/imgs/s1-configuraciones/github-ssh.png) 

# Creación y configuración de repositorios para la asignatura.

He creado dos repositorios para la asignatura:

1. Repositorio para los ejercicios:
   
   ![Repo para los ejercicios](https://github.com/kaizensamuel/Proyecto-CC-20-21/blob/main/imgs/s1-configuraciones/repo-ejercicios.png) 

2. Repositorio para el proyecto de la asignatura:
   
   ![Repo para el proyecto](https://github.com/kaizensamuel/Proyecto-CC-20-21/blob/main/imgs/s1-configuraciones/rrepo-proyecto.png) 

y por último he echo fork del proyecto de la asignatura:

![Fork del proyecto](https://github.com/kaizensamuel/Proyecto-CC-20-21/blob/main/imgs/s1-configuraciones/fork.png) 
   
## Configuro el remoto para la copia local del repositorio de la asignatura. (Para esto se usa la orden de puesta en el repositorio de la asignatura)

Añado el remoto: 
    
    ![Remoto](https://github.com/kaizensamuel/Proyecto-CC-20-21/blob/main/imgs/s1-configuraciones/add-remoto.png) 
    ![Remoto](https://github.com/kaizensamuel/Proyecto-CC-20-21/blob/main/imgs/s1-configuraciones/remoto.png) 


# Adicional: Creacion de git-pages para nuestro proyecto. Para esto he seguido la siguiente [guía](https://docs.github.com/es/free-pro-team@latest/github/working-with-github-pages/creating-a-github-pages-site).

Para esto tenemos que crear una rama llamada gh-pages e ir a settings :

  ![Direccion gh-pages del proyecto](https://github.com/kaizensamuel/Proyecto-CC-20-21/blob/main/imgs/s1-configuraciones/gh-pages.png)

# Perfil configurado:
![Perfil GitHub](https://github.com/kaizensamuel/Proyecto-CC-20-21/blob/main/imgs/s1-configuraciones/perfil.png) 


#Servidores que se pueden usar gratis, con una limitacion de creditos o tiempo, a partir de los cuales te cobran:

- [Azure](https://azure.microsoft.com/es-es/free/)
- [Amazon web services)[](https://aws.amazon.com/es/free/?nc2=h_ql_pr_ft)
- [Google Cloud Platform](https://cloud.google.com/?hl=es)
- [Digital Ocean](https://www.digitalocean.com/)
- [Linode](https://www.linode.com/es/pricing/#row--faqs)

# Habiilitar Seguridad en dos pasos:

![Seguridad GitHub](https://github.com/kaizensamuel/Proyecto-CC-20-21/blob/main/imgs/s1-configuraciones/two-factor.png) 




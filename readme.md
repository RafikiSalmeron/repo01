- [Ejercicio 1](#ejercicio-1)
  - [1.1 Crea un directorio llamado repo01 e inicia el repositorio en local](#11-crea-un-directorio-llamado-repo01-e-inicia-el-repositorio-en-local)
  - [1.2 Añade un documento llamado readme.md y documenta en su interior todos los pasos que vas realizando para crear un repositorio.](#12-añade-un-documento-llamado-readmemd-y-documenta-en-su-interior-todos-los-pasos-que-vas-realizando-para-crear-un-repositorio)
  - [1.3 Añade el fichero al staging area y haz un snapshot hacia el repositorio en local.](#13-añade-el-fichero-al-staging-area-y-haz-un-snapshot-hacia-el-repositorio-en-local)
  - [1.4 Crea un repositorio remoto llamado repo01, asócialo a tu repositorio local y sube los cambios al repositorio remoto](#14-crea-un-repositorio-remoto-llamado-repo01-asócialo-a-tu-repositorio-local-y-sube-los-cambios-al-repositorio-remoto)

# Ejercicio 1
## 1.1 Crea un directorio llamado repo01 e inicia el repositorio en local
Creamos el directorio -> ```mkdir repo01```  
Nos colocamos dentro del directorio -> ``` cd repo01 ```  
Iniciamos el repositorio -> ``` git init ```  

## 1.2 Añade un documento llamado readme.md y documenta en su interior todos los pasos que vas realizando para crear un repositorio.
Creamos el fichero readme.md -> ```touch readme.md```  
A continuación vamos documentando el fichero con su correspondiente sintaxis (**Markdown**).  

## 1.3 Añade el fichero al staging area y haz un snapshot hacia el repositorio en local.
Añadimos el fichero al staging area -> ``` git add . ```  
Realizamos el snapshot hacia el repositorio en local --> ```git commit -m "Este es el primer commit" ```   

## 1.4 Crea un repositorio remoto llamado repo01, asócialo a tu repositorio local y sube los cambios al repositorio remoto
Creamos el repositorio remoto, en mi caso en github.  
Después asociamos el repositorio remoto al local -> ``` git remote add origin https://github.com/USUARIO/repo01.git ```  
Nos colocamos en la rama main -> ``` git branch -M main ```  
Actualizamos el repositorio remoto -> ``` git push -u origin main ```

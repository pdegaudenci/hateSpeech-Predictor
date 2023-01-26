
<h1 align="center">HateSpeech-Predictor (NPL-Analisis de sentimientos con python/ DJANGO / ML y Redes neuronales ) ((EN DESARROLLO))</h1>
<p align="center"><img src=""/></p> 

## Tabla de contenidos:
---
- [Descripción y contexto](#descripción-y-contexto)
- [Guía de usuario](#guía-de-usuario)
- [Guía de instalación](#guía-de-instalación)
- [Despliegue](#Despliegue)
- [Construido con](#Construido-con)
- [Información adicional](#información-adicional)
- [Licencia](#licencia)
- [Limitación de responsabilidades - Solo BID](#limitación-de-responsabilidades)


## Descripción y contexto
---

Se desarrolla una solucion de Procesamiento del lenguaje natural con Inteligencia Artificial aplicada al analisis de sentimientos. 
El objetivos es analizar un conjunto de comentarios perteneciente a un video de un canal de  Youtube y poder detectar aquellos comentarios que sean de odio.

La solución propuesta es desarrollar un modelo predictivo usando Machine Learning (Aprendizaje supervisado) a través de un algoritmo de clasificacion en primera instancia, y en función de su rendimiento, si es necesario implementar una solucion basado en una red neuronal. 

Una vez obtenido el modelo óptimo para detectar comentarios de odio, se creará la aplicación cliente que consumirá dicho modelo , mediante una interfaz web. La aplicación cliente web será desarrollada con el framework de python DJANGO. Esta aplicación permitirá el ingreso por parte del usuario de la URL que contiene el video de youtube, a fin de extraer sus comentarios, los cuales serán preprocesados y enviados a la aplicación del lado del servidor, donde el modelo de ML los analizará y detectará si existen comentarios de odio. Finalmente, enviará esta informacion para que sea visualizada por el usario en la interfaz web

## Guía de usuario
---
### Comenzando 🚀

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._

Mira **Deployment** para conocer como desplegar el proyecto.


### Pre-requisitos 📋

_Que cosas necesitas para instalar el software y como instalarlas_

```
Da un ejemplo
```

_Finaliza con un ejemplo de cómo obtener datos del sistema o como usarlos para una pequeña demo_
 	
## Guía de instalación  🔧
---

_Una serie de ejemplos paso a paso que te dice lo que debes ejecutar para tener un entorno de desarrollo ejecutandose_

_Dí cómo será ese paso_

```
Da un ejemplo
```
Paso a paso de cómo instalar la herramienta digital. En esta sección es recomendable explicar la arquitectura de carpetas y módulos que componen el sistema.

Según el tipo de herramienta digital, el nivel de complejidad puede variar. En algunas ocasiones puede ser necesario instalar componentes que tienen dependencia con la herramienta digital. Si este es el caso, añade también la siguiente sección.

La guía de instalación debe contener de manera específica:
- Los requisitos del sistema operativo para la compilación (versiones específicas de librerías, software de gestión de paquetes y dependencias, SDKs y compiladores, etc.).
- Las dependencias propias del proyecto, tanto externas como internas (orden de compilación de sub-módulos, configuración de ubicación de librerías dinámicas, etc.).
- Pasos específicos para la compilación del código fuente y ejecución de tests unitarios en caso de que el proyecto disponga de ellos.

### Dependencias
Descripción de los recursos externos que generan una dependencia para la reutilización de la herramienta digital (librerías, frameworks, acceso a bases de datos y licencias de cada recurso). Es una buena práctica describir las últimas versiones en las que ha sido probada la herramienta digital. 

    Puedes usar este estilo de letra diferenciar los comandos de instalación.

## Despliegue 📦

_Agrega notas adicionales sobre como hacer deploy_

## Construido con 🛠️

_Menciona las herramientas que utilizaste para crear tu proyecto_

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - El framework web usado
* [Maven](https://maven.apache.org/) - Manejador de dependencias
* [ROME](https://rometools.github.io/rome/) - Usado para generar RSS


## Información adicional
---
Esta es la sección que permite agregar más información de contexto al proyecto como alguna web de relevancia, proyectos similares o que hayan usado la misma tecnología.

## Licencia 
---

La licencia especifica los permisos y las condiciones de uso que el desarrollador otorga a otros desarrolladores que usen y/o modifiquen la herramienta digital.

Incluye en esta sección una nota con el tipo de licencia otorgado a esta herramienta digital. El texto de la licencia debe estar incluído en un archivo *LICENSE.md* o *LICENSE.txt* en la raíz del repositorio.

Si desconoces qué tipos de licencias existen y cuál es la mejor para cada caso, te recomendamos visitar la página https://choosealicense.com/.

Si la herramienta que estás publicando con la iniciativa Código para el Desarrollo ha sido financiada por el BID, te invitamos a revisar la [licencia oficial del banco para publicar software](https://github.com/EL-BID/Plantilla-de-repositorio/blob/master/LICENSE.md)


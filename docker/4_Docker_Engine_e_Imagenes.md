### Contenedores e Imagenes.

##### Imagenes.

- Plantilla de solo lectura para crear nuestros contenedores.
- Creadas por nosotros u otros usuarios de la comunidad.
- Se pueden guardar en un registro interno o público.

##### Contenedores.
- Aplicación aislada.
- Contiene todo lo necesario para ejecutar nuestra aplicación.
- Basados en una o mas imagenes.

##### Imagenes.
- sitio de imagenes públicas (https://hub.docker.com)
- Utilización de docker CLI - 'docker search'
- Imagenes locales. 

##### Imagenes - Formato.
- El formato de las imagenes se compone de **repositorio:tag**
- Una misma imagen puede tener multiples tags.
- El tag por defecto de una imagen es latest.

##### Descargando imagenes.
- Para descargar una imagen del repositorio externo, se utiliza el comando 'docker pull'
- Cuando se ejecuta un contenedor con el comando 'docker run' las imagenes son descargadas automaticamente sino se encuentran en el repositorio local copy is found.

### Ciclo de vida de los contenedores.
- Ciclo de vida clasico.
  * Se crea el contenedor a partir de una imagen.
  * Se ejecuta un proceso determinado en el contenedor.
  * El proceso finaliza y el contenedor se detiene.
  * Se destruye el contenedor.
- Ciclo de vida avanzado.
  * Se crea el contenedor a partir de una imagen.
  * Se ejecuta un proceso determinado en el contenedor.
  * Realizar acciones dentro de contenedor.
  * Detener el contenedor.
  * Lanzar el contenedor nuevamente.
  
### Creando nuestro primer contenedor.
- Utilizando el comando *docker run*
- El comando *docker run* realiza 2 acciones
  * Crea el contenedor con la imagen especificada.
  * Ejecuta el contenedor.
- Sintaxis
  `
  docker run [opciones] [imagen] [comando] [args]
  `
- El formato de la imagen es *repository:[tag]  



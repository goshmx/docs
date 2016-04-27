## Contenedores
Contenedor = namespaces + cgroups + chroot + ...

**Namespaces.** 
Vistas de los recursos de SO.

Permite a mi aplicacion que se ejecucta en un contenedor, tener una vista de los recursos del sistema operativo, puede ver procesos, recursos de red, io etc.

**Cgroups.**
Limitan y miden los recursos del SO.
Yo puedo decir que mi aplicacion en un contenedor tenga cierto bandwich, recursos etc.

**Chroot.**
Cambia el root directory de un proceso.
Tener una lista de un filesystem, las carpetas, archivos definidas para un contenedor.

### Ventajas de un Contenedor

-Los contenedores con mas livianos que las VMs.
-No es necesario instalar un OS por contenedor.
-Menor utilización de recursos.
-Mayor cantidad de contenedores por equipo fisico.
-Mayor portabilidad.

# Tarea03 - Manipulación Avanzada de repositorios en Git.

Vamos a realizar una serie de ejercicios que tiene como objetivo aprender el uso de comandos avanzados de git que nos permitirán trabajar en nuestros proyectos con esta poderosa herramienta.

## Ejercicio 1.

El primero consiste en crear una carpeta __capitulos__ , iniciarla como repositorio y realizar los siguientes pasos:

* Crear el fichero __capitulo1.txt__ con el texto siguiente.

```
Git es un sistema de control de versiones ideado por Linus Torvalds.
```
* Guardar los cambios y realizar un commit con el mensaje pertinente.

* Ver los cambios que se han realizado con el comando para ver el historial.

__SOLUCIÓN__

Crear una carpeta __capitulos__ e iniciar el repositorio.

![02-crear-repositorios](capturas\ej1\02-crear-repositorios.png)


Ver los cambios del repositorio.

![03-historia-libro](capturas/ej1/03-historia-libro.png)

Crear un fichero capitulo1.txt y guadar los cambios.

![04-fichero-capitulo](capturas/ej1/04-fichero-capitulo.png)


![05-crear-fichero](capturas/ej1/05-crear-fichero.png)


Crear un commit y volver a ver los cambios del repositorio

![06-realizar-commit](capturas/ej1/06-realizar-commit.png)


## Ejercicio 2.

En este vamos a realizar los pasos como en el anterior:

* Creamos el fichero __capitulo2.txt__ con la siguiente información.

```
El flujo de trabajo básico con Git consiste en: 
1- Hacer cambios en el repositorio. 
2- Añadir los cambios a la zona de intercambio temporal. 
3- Hacer un commit de los cambios.

```

* Luego guardamos y realizamos el commit pertinente.

* Ahora vamos a ver las diferencias de los cambios entre la ultima y las dos anteriores versiones.

__SOLUCIÓN__

Crear el fichero "capitulo2.txt".

![01-crear-fichero](capturas/ej2/01-crear-fichero.png)

Añadir y realizar un commit los nuevos cambios.

![02-añadir-fichero](capturas/ej2/03-añadir-fichero.png)

Ver la diferencias de la ultima con las 2 anteriores versiones del repositorio.

![04-comprobacion](capturas/ej2/04-comprobacion.png)

## Ejercicio 3.

Lo mismo de antes pero con __capitulo3.txt__, con el siguiente mensaje.

```
Git permite la creación de ramas lo que permite tener distintas versiones del mismo proyecto y trabajar de manera simultanea en ellas.

```

* Al terminar lo anterior, obtener los cambios de la primera y la ultima versión.

__SOLUCIÓN__

Crear el fichero “capitulo3.txt” e introducir la siguiente información.

![01-crear-fichero](capturas/ej3/01-crear-fichero01.png)

![02-crear-fichero02](capturas/ej3/02-crear-fichero02.png)

Añadir los cambios y realizar el commit con el siguiente mensaje.

![03-añadir-capitulo](capturas/ej3/03-añadir-capitulo.png)

Comprobar los cambios entre la primera y la ultima versión.

![04-comprobacion-primera-con-ultima](capturas/ej3/04-comprobacion-primera-con-ultima.png)


## Ejercicio 4.

Ahora vamos aV crear el fichero __indice.txt__ y le añadimos la siguiente información.

```
Indice de los capítulos, con conceptos avanzados de git
```

* Como antes guardar los cambios y realizar el commit.

* Ver quien a realizado modificaciones en el fichero que acabamos de crear.

__SOLUCIÓN__

Crear y añadir información al fichero.

![01-crear-indice01](capturas/ej4/01-crear-indice01.png)

![02-crear-indice02](capturas/ej4/02-crear-indice02.png)

Guardar los cambios y realizar el commit.

![03-añadir-fichero](capturas/ej4/03-añadir-fichero.png)

Ver quien a realizado cambios en el fichero.

![04-consultar-cambios](capturas/ej4/04-consultar-cambios.png)


## Ejercicio 5.

* Vamos a crear una rama _bibliografia_ .
* ver todas las ramas del repositorio.

__SOLUCIÓN__

Crear y mostrar ramas

![01-crear-indice01](capturas/ej5/01-crear-y-consultar-ramas.png)


## Ejercicio 6.

Creamos el archivo __capitulo4.txt__ dentro de __capitulos__ y introducimos la siguiente información:

```
  En este capítulo veremos cómo usar GitHub para alojar repositorios en remoto.

```
* Guardamos los cambios y realizamos el commit.

* Ver el historial con las ramas.

__SOLUCIÓN__

Crear el fichero.

![01-crear-fichero01](capturas/ej6/01-crear-fichero01.png)

![02-crear-fichero02](capturas/ej6/02-crear-fichero02.png)

Añadir los cambios a la zona de intercambio temporal.

![03-git-add](capturas/ej6/03-git-add.png)

Realizar el commit.

![04-crear-commit](capturas/ej6/04-crear-commit.png)

Ver la información de cambios y las ramas.

![05-historial-con-ramas](capturas/ej6/05-historial-con-ramas.png)

## Ejercicio 7.

* Nos movemos a la rama __bibliografia__.

* Crear un nuevo fichero con el nombre __bibliografia.txt__ y con la siguiente información:

```
Chacon, S. and Straub, B. Pro Git. Apress.

```

* Guardamos los cambios y realizamos el commit.

* Ver el historial con las ramas.

__SOLUCIÓN__

Cambiar de rama.
![01-cambiar-rama](capturas/ej7/01-cambiar-rama.png)

Crear el fichero.

![02-crear-fichero01](capturas/ej7/02-crear-fichero01.png)

![03-crear-fichero02](capturas/ej7/03-crear-fichero02.png)

Crear el commit.

![04-añadir-fichero](capturas/ej7/04-añadir-fichero.png)

Ver toda la información con las ramas.

![05-consultar-cambios-y-ramas](capturas/ej7/05-consultar-cambios-y-ramas.png)


## Ejercicio 8.

* Unimos las ramas __bibliografia__ con la rama principal.

* Ver todos los cambios de todas las ramas.

* Borramos __bibliografia__.

* Volvemos a mostrar los cambios de todas las ramas.

__SOLUCIÓN__

Fusionamos las ramas.

![02-fusion](capturas/ej8/02-fusion.png)

![01-mensaje-fusion](capturas/ej8/01-mensaje-fusion.png)

Vemos los cambios con las ramas

![03-historial-cambios](capturas/ej8/03-historial-cambios.png)

Borramos la rama __bibliografia__.

![04-eliminar-rama](capturas/ej8/04-eliminar-rama.png)

Volvemos a consultar los cambios.

![05-historia-ramas](capturas/ej8/05-historia-ramas.png)


## Ejercicio 9.

* Volvemos a crear la rama __blibliografia__, Y nos desplazamos hacia ella.

* Volvemos a crear el fichero __bibliografia.txt__ con la siguiente información.

```
Scott Chacon and Ben Straub. Pro Git. Apress.
Ryan Hodson. Ry’s Git Tutorial. Smashwords (2014)
```
* Guardamos los cambios y realizamos el commit.

* Nos movemos a la rama principal.

* Modificamos el fichero __bibliografia.txt__ de la rama principal con el siguiente texto:
```
Chacon, S. and Straub, B. Pro Git. Apress.
Loeliger, J. and McCullough, M. Version control with Git. O’Reilly.

```

* Guardamos los cambios y realizamos el commit.

* Ahora intentamos fusionar las ramas al igual que antes.

* Resolver el conflicto entre las ramas seleccionando los cambios de la rama principal.

* Guardar los cambios y realizar el commit con el siguiente mensaje "Resuelto conflicto de bibliografia.".

* Ver los cambios junto con las ramas.

__SOLUCIÓN__

Crear y cambiar de rama.

![01-crear-acceder-rama](capturas/ej9/01-crear-acceder-rama.png)

Crear el fichero.

![02-modificar-fichero](capturas/ej9/02-modificar-fichero.png)

Cambiar a la rama principal.
![03-cambiar-rama](capturas/ej9/03-cambiar-rama.png)

Modificar el fichero.

![04-volver-a-modifcar](capturas/ej9/04-volver-a-modifcar.png)

Guardar los cambios y realizar el commit.

![05-añadir-fichero](capturas/ej9/05-añadir-fichero.png)

Fusionar las ramas.
![06-merge](capturas/ej9/06-merge.png)

Resolver el conflicto del merge.
![07-conflicto-fichero](capturas/ej9/07-conflicto-fichero.png)

Guardas los cambios y realizar el commit del conflicto resuelto.

![08-resuelto-conflico](capturas/ej9/08-resuelto-conflico.png)

Ver los cambios junto con las ramas.

![09-historial-ramas](capturas/ej9/09-historial-ramas.png)


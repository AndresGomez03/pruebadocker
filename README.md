# Frontend - Ventas

## Requisitos

- Tener Docker Desktop instalado

## Instalación (entorno de desarrollo)

1. Clonar el repositorio en el directorio deseado:

*Para esto debe ubicarse desde su terminal en donde desee clonar el repositorio, ejemplo "C:\Users\Admin\Desktop" y ejecutar lo siguiente:*

```bash
git clone https://github.com/AndresGomez03/pruebadocker
cd pruebadocker
```

2. Desde la terminal ubicandose en el directorio creado (C:\Users\Admin\Desktop\frontend-ventas) y teniendo Docker Desktop instalado ejecute el siguiente comando:

```bash
docker build -t front-ventas
```
*Esto construirá la imagen dentro de su Docker con todas las dependencias necesarias para correr el sistema de forma local*

3. Para correr la imagen, ejecute:

```bash
docker run -p 3000:3000 front-ventas
```
*Esto correrá su app en el puerto 3000, si accede a "http://localhost:3000" verá la aplicación corriendo*

## Contribución

1. Crea una rama para tu funcionalidad/tarea:

```bash
git switch -c feature/<nombre-funcionalidad/tarea>
```

2. Realiza cambios y haz commit:

```bash
git add <archivos-cambiados>
git commit -m "<descripcion pequeña del cambio>"
```

3. Pushea tus cambios de la rama:

```bash
git push origin feature/<nombre-funcionalidad/tarea> 
```

4. Crea un Pull Request (PR) a la rama ´develop´ desde GitHub para que sea revisado por otro desarrollador

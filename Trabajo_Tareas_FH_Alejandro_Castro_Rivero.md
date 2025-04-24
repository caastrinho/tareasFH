
# Trabajo Tareas FH - Alejandro Castro Rivero

## 1. Creación de máquinas virtuales

Primero creamos las dos máquinas virtuales de Ubuntu y les cambiamos los puertos y los redireccionamos.

## 2. Creación de usuarios

- En la **máquina A** creamos el usuario `Alex`.

![Creación usuario Alex](imagenes_trabajo/image1.png)

- En la **máquina B** creamos el usuario `Brais`.

![Creación usuario Brais](imagenes_trabajo/image2.png)

## 3. Conexión entre máquinas

Ahora nos conectamos desde A a B.

![Conexión A a B](imagenes_trabajo/image3.png)

En A hacemos lo mismo:

![Configuración en A](imagenes_trabajo/image4.png)

Y en B igual:

![Configuración en B](imagenes_trabajo/image5.png)

## 4. Transferencia de directorios

Ahora transmitimos directorios al escritorio.

![Transferencia de archivos](imagenes_trabajo/image6.png)

## 5. Prueba de carga de archivos

Ahora creamos **prueba 3** con 200 archivos.

![Prueba con 200 archivos](imagenes_trabajo/image7.png)

## 6. Generación de clave SSH

Creamos la clave SSH y nos conectamos con **passphrase**.

![Generación de clave SSH](imagenes_trabajo/image8.png)

## 7. Conexión con clave SSH

Después nos conectamos con este comando y listo:

```bash
ssh usuario@ip -p puerto
```

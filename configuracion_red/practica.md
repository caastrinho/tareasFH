
# Configuración de red

## AÑADIMOS LA ISO A VIRTUAL BOX

La primera es la primera que nos manda crear la tarea y la segunda es la clonación que también nos manda hacer.

![Imagen 1](configuracion_red/imagenes_configuracion_red/img1.png)

Ahora añadimos un segundo adaptador de red en cada una de las dos máquinas.

![Imagen 2](configuracion_red/imagenes_configuracion_red/img2.png)

Y hacemos lo mismo con la clonación.

![Imagen 3](configuracion_red/imagenes_configuracion_red/img3.png)

Después iniciamos las máquinas.

Seleccionamos este adaptador de red que es el que pusimos en red interna y lo configuramos de la siguiente manera.

![Imagen 4](configuracion_red/imagenes_configuracion_red/img4.png)

Ahora hacemos lo mismo en la clonación pero con los siguientes datos.

![Imagen 5](configuracion_red/imagenes_configuracion_red/img5.png)

## CONFIGURACIÓN EN LA MÁQUINA ORIGINAL

Abrimos la terminal en la máquina original.

Ponemos el siguiente comando para que nos abra la configuración que queremos.

![Imagen 6](configuracion_red/imagenes_configuracion_red/img6.png)

Y nos abre esta configuración.

Ponemos esa configuración con los datos que aparecen en la imagen.

![Imagen 7](configuracion_red/imagenes_configuracion_red/img7.png)

Aplicamos la configuración con el siguiente comando.

![Imagen 8](configuracion_red/imagenes_configuracion_red/img8.png)

## CONFIGURACIÓN EN LA MÁQUINA B

Nos vamos a la máquina B, abrimos la terminal y ponemos la siguiente configuración.

Se nos va a abrir la siguiente configuración.

![Imagen 9](configuracion_red/imagenes_configuracion_red/img9.png)

Entramos en "Modificar una conexión".

Entramos en "Conexión cableada 2".

Y ponemos los datos como aparecen en la captura.

![Imagen 10](configuracion_red/imagenes_configuracion_red/img10.png)

Le damos a **guardar** y vamos para atrás.

Ahora le damos a "Activar una conexión".

![Imagen 11](configuracion_red/imagenes_configuracion_red/img11.png)

Activamos la "Conexión 2".

Le damos para atrás, salir y guardamos.

## VERIFICAMOS CONECTIVIDAD

### Desde la máquina B a la A:
![Imagen 12](configuracion_red/imagenes_configuracion_red/img12.png)

Se recibe conexión, así que va perfecto.

### Desde la máquina A a la B:
![Imagen 13](configuracion_red/imagenes_configuracion_red/img13.png)

También se recibe conexión, así que va perfecto.

---

**ALEJANDRO CASTRO RIVERO**  
1ª ASIR  
CIFP A CARBALLEIRA

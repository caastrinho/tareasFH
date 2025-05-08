
# Configuración de red

## AÑADIMOS LA ISO A VIRTUAL BOX

La primera es la máquina que nos manda crear la tarea y la segunda es la clonación que también nos manda hacer.

![Imagen - ISO en VirtualBox](img1.png)

Ahora añadimos un segundo adaptador de red en cada una de las dos máquinas:

![Imagen - Adaptador de red](img2.png)

Y hacemos lo mismo con la clonación:

![Imagen - Adaptador en clonación](img3.png)

Después iniciamos las máquinas.

Seleccionamos este adaptador de red que es el que pusimos en red interna y lo configuramos de la siguiente manera:

![Imagen - Configuración adaptador](img4.png)

Ahora hacemos lo mismo en la clonación pero con los siguientes datos.

![Imagen - Configuración clonación](img5.png)

## CONFIGURACIÓN EN LA MÁQUINA ORIGINAL

Abrimos la terminal en la máquina original:

Ponemos el siguiente comando para que nos abra la configuración que queremos.

![Imagen - Terminal Netplan](img6.png)

Y nos abre esta configuración.

Ponemos esa configuración con los datos que aparecen en la imagen.

![Imagen - Configuración Netplan](img7.png)

Aplicamos la configuración con el siguiente comando:

![Imagen - Netplan apply](img8.png)

## CONFIGURACIÓN EN LA MÁQUINA B

Nos vamos a la máquina B, abrimos la terminal y ponemos la siguiente configuración.

Se nos va a abrir la siguiente configuración.

![Imagen - NetworkManager configuración](img9.png)

Entramos en "Modificar una conexión".

Entramos en "Conexión cableada 2".

Y ponemos los datos como aparecen en la captura.

![Imagen - Configuración cableada 2](img10.png)

Le damos a **guardar** y vamos para atrás.

Ahora le damos a "Activar una conexión".

![Imagen - Activar conexión](img11.png)

Activamos la "Conexión 2".

Le damos para atrás, salir y guardamos.

## VERIFICAMOS CONECTIVIDAD

### Desde la máquina B a la A:
![Imagen - Ping B a A](img12.png)

Se recibe conexión, así que va perfecto.

### Desde la máquina A a la B:
![Imagen - Ping A a B](img13.png)

También se recibe conexión, así que va perfecto.

---

**ALEJANDRO CASTRO RIVERO**  
1ª ASIR  
CIFP A CARBALLEIRA

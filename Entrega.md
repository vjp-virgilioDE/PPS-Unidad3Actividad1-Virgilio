## Documentación

Lo primero que hacemos es descargarnos el docker-compose.yml del repositorio.

Una vez descargado lo levantamos mediante el comando `docker-compose up -d` para levantar el contenedor en modo detached.

![](/Entrega/Imagen1.png)

![](/Entrega/Imagen2.png)

Ahora visto que estan activas todas las máquinas, vamos levantando una a una por su puerto de localhost

## DVWA

![](/Entrega/Imagen3.png)

## BWAPP

![](/Entrega/Imagen4.png)

![](/Entrega/Imagen5.png)

## OWASP Multillidae ii

![](/Entrega/Imagen6.png)

Localhost:81

![](/Entrega/Imagen7.png)

## Ldap

![](/Entrega/Imagen8.png)


## Entorno de pruebas

Paramos el docker que ya teniamos

![](/Entrega/Imagen9.png)

Nos clonamos el repositorio donde se encuentra el entorno de pruebas

![](/Entrega/Imagen10.png)

Entramos en el docker.compose.yml y en el sample.env, vemos los puertos.

![](/Entrega/Imagen11.png)

![](/Entrega/Imagen12.png)

Para una mayor seguridad , deberiamos cambiar el puerto de las maquinas, y cambiar el usuario y contraseña.

![](/Entrega/Imagen13.png)

Iniciamos el entorno de pruebas

![](/Entrega/Imagen14.png)

Vemos que todo se ha levantado correctamente

![](/Entrega/Imagen15.png)
# Configuracion TCP/IP

## Windows

### ipconfig

Muestra la información de nuestro equipo como:
>**Descripción** - Nombre del adaptador o tarjeta de red utilizado en la conexión.

>**Dirección IPV4** - Es la dirección IP asignada al equipo en la red local.

>**Puerta de enlace predeterminada** - Es la dirección IP del equipo que funciona como servidor y que tiene acceso a internet.

![](../img/Captura1.PNG)

### ipconfig /all
Muestra la información de nuestro equipo como:
>**Descripción** - Nombre del adaptador o tarjeta de red utilizado en la conexión.

>**Dirección IPV4** - Es la dirección IP asignada al equipo en la red local.

>**Puerta de enlace predeterminada** - Es la dirección IP del equipo que funciona como servidor y que tiene acceso a internet.

>**Servidores DNS** - Son los servidores con los cuales el equipo anterior gestiona en la red la relación nombre de dominio/Dirección IP de las paginas solicitadas.

>**Estado de DHCP** - Configuración dinámica de host, eso significa que siempre se utilizara una dirección IP estática o fija entre el equipo y el host.

![](../img/Captura2.png)
### getmac
Este comando habilita al administrador para poder mostrar la dirección MAC de uno o mas adaptores de red de un equipo.

![](../img/Captura3.png)
## Linux
### ifconfig
La orden ifconfig se utiliza para configurar y mostrar los interfaces de red de Linux. Se indican varios parámetros:

* La dirección IP de la maquina.
* La mascara de la red local.
* La dirección de broadcast.
* La dirección Mac.

![](../img/Captura4.png)
### ifconfig -a
La orden ifconfig -a se utiliza para configurar y mostrar los interfaces de red en Linux incluyendo las interfaces que no están activas.

![](../img/Captura5.png)
### ip address show
La orden ip address show se utiliza para configurar y mostrar los interfaces de red de Linux incluyendo las que no están activas. Se indican varios parámetros:

* La dirección IP de la maquina.
* La mascara de la red local.
* La dirección de broadcast.
* La dirección Mac.

![](../img/Captura6.png)
### ip address list
La orden ip address show se utiliza para configurar y mostrar los interfaces de red de Linux incluyendo las que no están activas. Se indican varios parámetros:

* La dirección IP de la maquina.
* La mascara de la red local.
* La dirección de broadcast.
* La dirección Mac.

![](../img/Captura7.png)
## Mikrotik
### interface print
La orden **interface print** nos muestra las de todas las tarjetas de red que tiene.

![](../img/Captura8.png)
### ip address print
La orden **ip address print** nos muestra las IPs de todas las tarjetas de red que tiene asi como tambien las networks de cada tarjeta de red.

![](../img/Captura9.png)
# Enrutamiento/Tabla de rutas
## Windows
### route print
Nos muestra todos los destinos de red asi como tambien la mascara de red, la puerta de enlace y la interfaz de la tarjeta de red.

![](../img/Captura10.png)
## Linux
### netstat -r
El comando **netstat -r** nos muestra las network de nuestros equipos asi como tambien las puertas de enlace.

![](../img/Captura11.png)
### route -n
El comando **route -n** nos muestra las network de nuestros equipos asi como tambien las puertas de enlace.

![](../img/Captura12.png)
### ip route show
El comando **ip route show** nos muestra las network de nuestros equipos asi como tambien las puertas de enlace.

![](../img/Captura13.png)
## Mikrotik
### ip route print
El comando **ip route print** nos muestra las network de cada tarjeta de red.

![](../img/Captura14.png)

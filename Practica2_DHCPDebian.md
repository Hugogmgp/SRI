# PRACTICA 2: configuracion DHCP en Debian

## Instalar el servidor DHCP en la maquina de Debian

![ej1_a](/img_dhcpdebian/ej1_A.PNG)
--
## Configurar el DHCP
![ej1_b1](/img_dhcpdebian/ej1_B1.PNG)
--
 ## Aqui vamos a configurar el rango de ip, la mascara, el servidor DNS, la puerta de enlace y los lease times
![ej1_dhcp](/img_dhcpdebian/ej1_configdhcp.PNG)
--


## vamos a reservar una ip para la maquina de ubuntu

![reserva_ubuntu](/img_dhcpdebian/ej1_reservaUbuntu.PNG)
--
## reiniciamos el servicio para que se active y ejecute

![restart](/img_dhcpdebian/ej1_restart.PNG)
--

## Configuramos Windows comprobamos ip por dhcp
 
 ![ip_windows](/img_dhcpdebian/ej2_ipWIn.PNG)
--

 ## Lo mismo con Ubuntu

 ![ip_Ubuntu](/img_dhcpdebian/ej2_ipLinux.PNG)
--
## Comprobamos las concesiones en el servidor en el archivo dhcp.leases
![concesion](/img_dhcpdebian/ej2_concesiones.PNG)
--

## Comprobamos la conectividad entre los equipos
![ping1](/img_dhcpdebian/ej2_linuxping.PNG)
![ping2](/img_dhcpdebian/ej2_winping.PNG)
--

## Comprobamos que hagan ping a internet
![pinggoogle1](/img_dhcpdebian/ej2_linuxpinginternet.PNG)
![pinggoole2](/img_dhcpdebian/ej2_winpinginternet.PNG)
--

## Revisamos el journalctl de servidor DHCP

![journal](/img_dhcpdebian/journal.PNG)
--

# Descripción del Laboratorio
Despliegue de puertas de enlace ExpressRoute

Para conectar su red virtual Azure y su red local a través de ExpressRoute, primero debe crear una puerta de enlace de red virtual. Una puerta de enlace de red virtual tiene dos finalidades: intercambiar rutas IP entre las redes y enrutar el tráfico de red.

Tipos de puerta de enlace

Cuando cree una puerta de enlace de red virtual, deberá especificar varios parámetros. Una de ellas, "-GatewayType", especifica si la pasarela se utiliza para tráfico ExpressRoute o VPN. Los dos tipos de pasarela son:

- VPN - Para enviar tráfico cifrado a través de la Internet pública, se utiliza el tipo de pasarela 'VPN'. También se denomina puerta de enlace VPN. Las conexiones de sitio a sitio, de punto a sitio y de VNet a VNet utilizan una pasarela VPN.
- ExpressRoute - Para enviar tráfico de red en una conexión privada, se utiliza el tipo de pasarela 'ExpressRoute'. También se denomina puerta de enlace ExpressRoute y es el tipo de puerta de enlace que se utiliza al configurar ExpressRoute.

Cada red virtual sólo puede tener una puerta de enlace de red virtual por tipo de puerta de enlace. Por ejemplo, puede tener una puerta de enlace de red virtual que utilice -GatewayType VPN, y otra que utilice -GatewayType ExpressRoute.

En este ejercicio, usted:

- Tarea 1: Crear la VNet y la subred de la puerta de enlace
- Tarea 2: Crear la puerta de enlace de la red virtual



## Desarrollo del Laboratorio
![Logo](/AZ-700-Designing%20%20and%20Implementing%20Microsoft%20Azure%20Networking%20Solutions/M03%20-%20Unit%204%20Configure%20an%20ExpressRoute%20Gateway/screenshots/Unit04.png)

## Video
https://youtu.be/daFK7kG__gw


## About me
- [@jonko-u](https://github.com/jonko-u)

## Recursos
- [go deploy](https://lms.godeploy.it/)



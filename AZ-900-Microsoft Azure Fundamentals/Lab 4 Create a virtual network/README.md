# Introducción
Las redes virtuales en Azure(VNet) es un bloque fundamental de construcción en la plataforma de la nube de Microsoft Azure, que provee un entorno de red seguro y  aislado para el despliegue y la ejecución de varios recursos de Azure. Funciona como un componente crucial para la creación de infraestructuras flexibles, escalables, e interconectadas dentro de la nube de Azure.

## Descripción del Laboratorio
En este laboratorio, crearemos una red virtual, desplegaremos dos máquinas virtuales dentro de una red virtual y entonces los configuraremos para permitir que un se puedan hacer ping entre las máquinas dentro de la red virtual.

## Cosas a tener en cuenta cuando se crean redes virtuales
- Cuando creas una red virtual, necesitas definir un espacio de dirección IP para la red.
- Planificar usar un espacio de dirección IP que no esté en uso en tu organización.
    - El espacio de dirección para la red puede también ser en las instalaciones(on-premises) o en la nube, pero no en ambas.
    - Una vez crees el espacion de direcciones IP, este no puede ser cambiado. Si planifica su espacio de direcciones para redes virtuales sólo en la nube, es posible que más adelante decida conectar un sitio local.
    ```bash
    Ejemplo:
    - A la red virtual se le asigna el espacio de direcciones IP 10.0.0.0/16. 
    Este espacio de direcciones esta planeado para su uso de red virtual sólo en la nube dentro de Azure.
    
    Ahora, considere un futuro escenario donde decides establecer conectividad entre tus redes en local y tu red virtual en Azure.
    Si tu red local utiliza el rango de direcciones IP 192.168.1.0/24, puede encontrarse con conflictos.

    Para evitar conflictos de conectividad en un futuro, es recomendable planificar tu espacio de direcciones IP iniciales en Azure.
    Espacio de Direcciones de IP REVISADO: 192.168.0.0/16
    - Esta planificacion permite flexibilidad para potencial conectividad en locales en el futuro sin conflictos de IP.
    ```

- Para crear una red virtual, almenos necesitas definir una subred.
    - Cada subred contiene un rago de direcciones IP que caen dentro del espacio de direcciones de la red virtual.
    - El rango de direcciones para cada subred debe ser único dentro del espacio de direcciones para la red virtual.
    - El rango para una subred no puede solaparse(overlap) con otros rangos de direcciones IP de subred en la misma red virtual. 
- Puedes crear una red virtual desde el portal de Azure. Provee una suscripción, un grupo de recursos, un nombre de la red virtual, y una región del servicio para la red virtual.
- ***La plafinicación es muy importante***

## Desarrollo del Laboratorio
![Logo](/AZ-900-Microsoft%20Azure%20Fundamentals/Lab%204%20Create%20a%20virtual%20network/screenshots/Lab4.png)

## Topología de la red virtual del laboratorio
![Logo](/AZ-900-Microsoft%20Azure%20Fundamentals/Lab%204%20Create%20a%20virtual%20network/screenshots/Lab4-View%20the%20topology%20of%20an%20Azure%20virtual%20network.png)

## About me
- [@jonko-u](https://github.com/jonko-u)

## Bibliografía
- [Microsoft Certified: Azure Fundamentals](https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/)
- [Create virtual networks](https://learn.microsoft.com/en-gb/training/modules/configure-virtual-networks/4-create-virtual-networks?WT.mc_id=ilt_partner_webpage_wwl&ocid=4704327)
- [go deploy](https://lms.godeploy.it/)

# Introducción
Los contenedores de Azure proveen un entorno de virtualización que habilita el despliegue y gestión de aplicaciones de una manera ligera, dinámica y escalable. Ofrecen una alternativa a las máquinas virtuales tradicionales, permitiendo la ejecución de varias instancias de una aplicación en un único equipo anfitrión.

## Descripción del Laboratorio
En este laboratorio, aprenderás a crear una aplicación web de Azure App Service utilizando el portal de Azure.

## Conceptos clave
- ***Comparando Contenedores con Máquinas virtuales***
    - Las máquinas virtuales estan limitadas a un único sistema operativo por instancia.
    - Los contenedores ofrecen un método más ágil, también, responden rápidamente a los cambios de la demanda, y son más ligeros en términos de uso de recursos.
- ***Azure Container Instances(ACI)*** 
    - ACI ofrece una manera sencilla para ejecutar contenedores en Azure sin gestionar máquinas virtuales.
    - PaaS que gestiona la ejecución de contenedores sin gestión adicional de máquinas virtuales.
- ***Azure Kubernetes Service(AKS)*** 
    - El servicio de orquestación de contenedores que gestiona el ciclo de vida de los contenedores.
    - Simplifica la gestión de flotas cuando se despliega y gestiona un gran número de contenedores.

## Uso de contenedores en soluciones

- ***Arquitectura de microservicios*** 
    Los contenedores son comunmente empleados en una arquitectura de microservicios, que rompen las soluciones en más pequeños, componentes independientes. ***¡Divide y vencerás!***
    
- ***Escalabilidad e Independencia*** 
    - Los contenedores facilitan el escalado de componentes especificos independientemente de la mejora del rendimiento global.
    - Cambiar un componentes, ya sea modificando el front end o almacenamiento, puede ser hecho sin impactar otros componentes.
## Desarrollo del Laboratorio
![Logo](/AZ-900-Microsoft%20Azure%20Fundamentals/Lab%203%20Deploy%20Azure%20Container%20Instances/screenshots/Lab3.png)

## About me
- [@jonko-u](https://github.com/jonko-u)

## Bibliografía
- [Microsoft Certified: Azure Fundamentals](https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/)
- [Describe Azure Containers](https://learn.microsoft.com/en-gb/training/modules/describe-azure-compute-networking-services/5-containers?WT.mc_id=ilt_partner_webpage_wwl&ocid=4704327)
- [go deploy](https://lms.godeploy.it/)

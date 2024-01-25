# Introducción
Los Servicios de Almacenamiento de Azure forman un conjunto robusto y versátil de soluciones de almacenamiento de datos dentro de la plataforma en la nube Microsoft Azure, ofreciendo una gama de servicios para satisfacer diversos requisitos de almacenamiento. Estos servicios desempeñan un papel fundamental en la gestión, la seguridad y el acceso a los datos para diversas aplicaciones y cargas de trabajo. 
## Descripción del Laboratorio
En este laboratorio, crearemos una cuenta de almacenamiento, entonces trabajaremos con archivos de almacenamiento blob.

## Componentes Clave:
- ***Azure Blobs*** - Un objeto de almacenamiento altamente escalable diseñado para almacenar bastante cantidad de texto y datos binarios. Soporta analiticas de big data a través del Data Lake Storage Gen2. En casos prácticos, son ideales para servir imágenes, acceso distribuido a archivos, streaming multimedia, copias de seguridad y restauración, recuperación ante desastres y análisis de datos.
- ***Azure Files*** - Archivos gestionados se comparten ofreciendo la completa gestión de los despliegues en nube o en locales. Entre los beneficios, se permite el acceso compartido totalmente gestionado con capacidades de scripting, alta resistencia y programabilidad familiar.
- ***Azure Queues*** - Provee almacenamiento para grandes cantidades de mensajes accesibles globalmente mediante llamadas de autenticación usando HTTP o HTTPS. El uso común es crear backlogs de trabajo para el procesamiento asíncrono, a menudo integrado con Azure Functions.
- ***Azure Disks*** - Volúmenes de almacenamiento a nivel de bloque gestionados por Azure para VM de Azure. Ofrece discos virtualizados para mejorar la resistencia. Entre las características principales se encuentran la simplificación del aprovisionamiento, la gestión y el mantenimiento de discos para las máquinas virtuales de Azure.
- ***Azure Tables*** - Almacén de datos NoSQL para datos estructurados y no relacionales a gran escala. Acepta llamadas autenticadas desde dentro y fuera de Azure.
## Conceptos a tener en cuenta sobre contenedores y blobs
Echemos un vistazo a las características de configuración de los contenedores y blobs.
- Todos los blobs deben estar en un contenedor.
- Un contenedor puede almacenar un número ilimitado de blobs.
- Una cuenta de Almacenamiento de Azure puede contener un número ilimitado de contenedores.
- Puedes crear un contenedor en el portal de Azure.
- Subes blobs a un contenedor.
## Desarrollo del Laboratorio
![Logo](/AZ-900-Microsoft%20Azure%20Fundamentals/Lab%205%20Create%20Blob%20Storage/screenshots/Lab5.png)


## About me
- [@jonko-u](https://github.com/jonko-u)

## Bibliografía
- [Microsoft Certified: Azure Fundamentals](https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/)
- [Describe Azure storage services](https://learn.microsoft.com/en-gb/training/modules/describe-azure-storage-services/4-describe-azure-storage-services?WT.mc_id=ilt_partner_webpage_wwl&ocid=4704327)
- [Configure Azure Blob Storage: Create blob containers](https://learn.microsoft.com/en-gb/training/modules/configure-blob-storage/3-create-blob-containers?WT.mc_id=ilt_partner_webpage_wwl&ocid=4704327)

- [go deploy](https://lms.godeploy.it/)

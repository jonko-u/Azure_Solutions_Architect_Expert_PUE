# Descripción del Laboratorio
Creará un Private Endpoint para una aplicación web Azure e implementará una máquina virtual para probar la conexión privada.
Los Private Endpoints se pueden crear para diferentes tipos de servicios Azure, como Azure SQL y Azure Storage.
Requisitos previos
Una Azure Web App con un plan de servicio de aplicaciones PremiumV2-tier o superior desplegado en su suscripción Azure.
Busque y abra parameters.json en la carpeta M07. Ábralo en el Bloc de notas y busque la línea "value": "GEN-UNIQUE". Sustituya el marcador de posición GEN-UNIQUE por un valor único para el nombre de su aplicación web. Guarde este cambio.
En el portal Azure, abra la sesión PowerShell dentro del panel Cloud Shell.
En la barra de herramientas del panel Cloud Shell, haga clic en el icono Upload/Download files, en el menú desplegable, haga clic en Upload y cargue los siguientes archivos template.json y parameters.json en el directorio de inicio de Cloud Shell.
Si decide instalar y utilizar PowerShell localmente, este ejemplo requiere el módulo Azure PowerShell versión 5.4.1 o posterior. Ejecute Get-Module -ListAvailable Az para encontrar la versión instalada. Si necesita actualizar, consulte Instalar el módulo Azure PowerShell. Si está ejecutando PowerShell localmente, también necesita ejecutar Connect-AzAccount para crear una conexión con Azure.
En este ejercicio, deberás:
- Tarea 1: Crear un grupo de recursos
- Tarea 2: Crear una red virtual y un host bastión
- Tarea 3: Crear una máquina virtual de prueba
- Tarea 4: Crear un Endpoint Privado
- Tarea 5: Configurar la zona DNS privada
- Tarea 6: Probar la conectividad con el Endpoint Privado

## Desarrollo del Laboratorio
![Logo](/AZ-700-Designing%20%20and%20Implementing%20Microsoft%20Azure%20Networking%20Solutions/M07%20-%20Unit%206%20Create%20an%20Azure%20Private%20Endpoint%20using%20Azure%20PowerShell/screenshots/Unit06.png)

## Video
https://youtu.be/zbK5V-0qsIU

## About me
- [@jonko-u](https://github.com/jonko-u)

## Recursos
- [go deploy](https://lms.godeploy.it/)



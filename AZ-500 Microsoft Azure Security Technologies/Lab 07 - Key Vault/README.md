# Descripción del Laboratorio
Se le ha pedido que cree una aplicación de prueba de concepto que haga uso del soporte de Azure SQL Database para la funcionalidad Always Encrypted. Todos los secretos y claves utilizados en este escenario deben almacenarse en Key Vault. La aplicación debe ser registrada en Microsoft Entra ID con el fin de mejorar su postura de seguridad. Para lograr estos objetivos, la prueba de concepto debe incluir:

- Crear una Bóveda de Claves Azure y almacenar claves y secretos en la bóveda.
- Crear una Base de Datos SQL y encriptar el contenido de las columnas en las tablas de la base de datos utilizando Always Encrypted.

Nota: Para todos los recursos en este laboratorio, estamos utilizando la región Este de EE.UU.. Verifique con su instructor que esta es la región a utilizar para la clase.

Para mantener el foco en los aspectos de seguridad de Azure, relacionados con la construcción de esta prueba de concepto, se partirá de un despliegue automatizado de plantillas ARM, configurando una Máquina Virtual con Visual Studio 2019 y SQL Server Management Studio 19.

Objetivos

En este laboratorio, completarás los siguientes ejercicios:

- Ejercicio 1: Desplegar la infraestructura base desde una plantilla ARM.
- Ejercicio 2: Configurar el recurso Key Vault con una clave y un secreto
- Ejercicio 3: Configurar una base de datos Azure SQL y una aplicación basada en datos
- Ejercicio 4: Demostrar el uso de Azure Key Vault en el cifrado de la base de datos Azure SQL


## Desarrollo del Laboratorio
![Logo](/AZ-500%20Microsoft%20Azure%20Security%20Technologies/Lab%2007%20-%20Key%20Vault/screenshots/Lab07.png)

## Video
https://youtu.be/awM3RYoOPfE

## About me
- [@jonko-u](https://github.com/jonko-u)

## Recursos
- [go deploy](https://lms.godeploy.it/)



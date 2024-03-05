# Descripción del Laboratorio
SSH es un protocolo de conexión cifrado que permite el inicio de sesión seguro a través de conexiones no seguras. SSH es el protocolo de conexión predeterminado para las máquinas virtuales Linux alojadas en Azure. Aunque SSH por sí mismo proporciona una conexión cifrada, el uso de contraseñas con conexiones SSH aún deja a la VM vulnerable a ataques de fuerza bruta o adivinación de contraseñas. Un método más seguro y preferido para conectarse a una VM utilizando SSH es mediante el uso de un par de claves pública-privada, también conocidas como claves SSH.

- La clave pública se coloca en su VM Linux, o en cualquier otro servicio que desee utilizar con criptografía de clave pública.

- La clave privada en su sistema local es utilizada por un cliente SSH para verificar su identidad cuando se conecta a su máquina virtual Linux. Proteja esta clave privada. No la comparta.

- Dependiendo de las políticas de seguridad de su organización, puede reutilizar un único par de claves pública-privada para acceder a varias máquinas virtuales y servicios de Azure. No necesita un par de claves distinto para cada máquina virtual o servicio al que desee acceder.

Su clave pública puede compartirse con cualquiera, pero sólo usted (o su infraestructura de seguridad local) debe poseer su clave privada.


## Desarrollo del Laboratorio
![Logo](/AZ-500%20Microsoft%20Azure%20Security%20Technologies/Lab%20105%20-%20VM%20Secure%20Admin%20-Access%20-%20Additional%20Lab/screenshots/Lab105.png)

## Video
https://youtu.be/yHxgcwvrqyY

## About me
- [@jonko-u](https://github.com/jonko-u)

## Recursos
- [go deploy](https://lms.godeploy.it/)



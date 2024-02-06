
## Descripción del Laboratorio
Las etiquetas se aplican a los recursos Azure proporcionando metadatos para organizarlos lógicamente en una taxonomía. Cada etiqueta consta de un nombre y un par de valores. Por ejemplo, puede aplicar el nombre "Entorno" y el valor "Producción" a todos los recursos en producción.

Después de aplicar etiquetas, puede recuperar todos los recursos de su suscripción con ese nombre de etiqueta y valor. Las etiquetas le permiten recuperar recursos relacionados de diferentes grupos de recursos. Este enfoque es útil cuando se necesita organizar los recursos para la facturación o la gestión.

Su taxonomía debe considerar una estrategia de etiquetado de metadatos de autoservicio además de una estrategia de etiquetado automático para reducir la carga de los usuarios y aumentar la precisión.

The following limitations apply to tags:

- Each resource or resource group can have a maximum of 15 tag name/value pairs. This limitation applies only to tags directly applied to the resource group or resource. A resource group can contain many resources that each have 15 tag name/value pairs. If you have more than 15 values that you need to associate with a resource, use a JSON string for the tag value. The JSON string can contain many values that are applied to a single tag name. This article shows an example of assigning a JSON string to the tag.
- The tag name is limited to 512 characters, and the tag value is limited to 256 characters. For storage accounts, the tag name is limited to 128 characters, and the tag value is limited to 256 characters.
- Virtual Machines are limited to a total of 2048 characters for all tag names and values.
- Tags applied to the resource group are not inherited by the resources in that resource group.
- Tags can't be applied to classic resources such as Cloud Services.
- Tag names can't contain these characters: <, >, %, &, , ?, /
## Desarrollo del Laboratorio
![Logo](/AZ-104-Microsoft%20Azure%20Administrator/Lab%202B%20-%20Manage%20Governance%20via%20Azure%20Policy/screenshots/Lab2B.png)

## Video
https://youtu.be/mP-H7CUyYi0

## About me
- [@jonko-u](https://github.com/jonko-u)

## Bibliografía

- [go deploy](https://lms.godeploy.it/)

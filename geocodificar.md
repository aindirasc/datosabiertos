---
description: >-
  Localiza de forma masiva lugares ubicados en el Distrito Capital a partir de
  direcciones, sitios de interés o coordenadas
---

# Geocodificar

**1.Inicia sesión:** Da clic en el menú principal ![](.gitbook/assets/menu_1.jpg)\(ubicado en el costado superior izquierdo de la pantalla\), luego da clic en el botón ["Iniciar sesión"](https://mapasbogota.gitbook.io/ayuda/iniciar-sesion)

![](.gitbook/assets/image%20%28110%29.png)

{% hint style="warning" %}
_**Tenga en cuenta:** El servicio de geocodificación únicamente esta disponible para los funcionarios del Distrito que tengan permisos previos para acceder a su uso._ 
{% endhint %}

**2.Ingresa a Geocodificar:** Da clic en el menú principal y luego da clic en el botón Geocodificar.

![](.gitbook/assets/image%20%28101%29.png)

**3.Organiza tu archivo:** Antes de cargar el archivo ten en cuenta las siguientes recomendaciones, de acuerdo al método a utilizar:

{% tabs %}
{% tab title="Geocodificación directa" %}
_**Herramienta para la localización de un lugar conociendo su dirección o sitio de interés.**_

El geocodificador acepta archivos de hasta máximo 500.000 registros, con la siguiente estructura:

■ **Archivos XLS, XLSX o CSV** 

     -  Deben contener las columnas: identificador; DIRECCION; CIUDAD \(Separadas por ;\)

          _**Ejemplo:** 1;_ KR 38 8A 29; Bogotá.

![](.gitbook/assets/image%20%28228%29.png)

■  **Archivos JSON** 

     - Organizado así: {"row":\[{"identificador":"01","ciudad":"BOGOTA","direccion":"KR 38 8A 29"} \] }

{% hint style="warning" %}
El formato Json debe cumplir con el estándar RFC 4327, RFC 7159 o ECMA-404
{% endhint %}

{% hint style="success" %}
_Cuando descargues el archivo el campo identificador corresponderá al nombre **cod\_id**_ 
{% endhint %}
{% endtab %}

{% tab title="Geocodificación inversa" %}
_**Herramienta para la localización de un lugar conociendo sus coordenadas.**_

{% hint style="info" %}
Sistema de referencia en coordenadas geográficas MAGNA-SIRGAS EPSG: 4686.
{% endhint %}

El geocodificador acepta archivos de hasta máximo 500.000 registros, con la siguiente estructura:

■ **Archivos XLS, XLSX o CSV** 

     -  Deben contener las columnas: identificador, LONGUITUD, LATITUD \(Separadas por ;\)

          _**Ejemplo:**_ 1; -74,07711; 4,647659

![](.gitbook/assets/image%20%2842%29.png)

■  **Archivos JSON** 

     - Organizado así: {"row":\[{"identificador":"01","longuitud":"-74,07711","latitud":4,647659"} \] }

{% hint style="warning" %}
El formato Json debe cumplir con el estándar RFC 4327, RFC 7159 o ECMA-404
{% endhint %}

{% hint style="success" %}
Cuando descargues el archivo el campo identificador corresponderá al nombre _**cod\_id**_ 
{% endhint %}
{% endtab %}
{% endtabs %}

**4.Sube tu archivo:** Da clic en el botón seleccionar, busca en tu equipo el archivo que vas a transformar, selecciona el tipo de geocodificación y luego da clic en el botón "_**Geocodificar".**_

![](.gitbook/assets/image%20%2863%29.png)

**5.Revisa el estado del proceso:** Verifica en tu correo electrónico las notificaciones sobre el estado del proceso de geocodificación.

![](.gitbook/assets/image%20%2853%29.png)

**6. Descarga tu archivo:** En tu correo electrónico recibirás un mensaje con las estadísticas del proceso de geocodificación, luego podrás descargar el archivo dando clic en el enlace relacionado con el formato de tu interés.

![](.gitbook/assets/image%20%2858%29.png)


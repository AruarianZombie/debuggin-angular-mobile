# Debuggear Proyecto de Angular desde dispositivo móvil

El proposito de la siguiente documentación es **plantear** de manera sencilla los pasos a seguir para **debuggear** una aplicación web **Angular**; teniendo en cuenta que nuestra aplicación puede necesitar comunicarse a un **backend** o utilizar algun motor de base de datos en memoria como **Redis**. A continuación 

- [Debuggear Proyecto de Angular desde dispositivo móvil](#debuggear-proyecto-de-angular-desde-dispositivo-m%c3%b3vil)
  - [# Configurando nuestro dispositivo móvil](#h1-id%22configurando-nuestro-dispositivo-mc3b3vil-412%22configurando-nuestro-dispositivo-m%c3%b3vilh1)


# Configurando nuestro dispositivo móvil
---

Para poder realizar el *"debugging"* en tiempo real de nuestra aplicación movil desde nuestro dispositivo es necesario activar el **modo desarrollador** para activar las funcionalidades/herramientas que este modo ofrece. [^test]

> **Importante:** En dado caso de tener habilitado el modo en tu dispositivo puedes omitir este paso.

> **Importante!!!:** El proceso para activar el **modo desarrollador** puede diferir entre modelos de dispositivos.

Para habilitar el **modo desarrollador** es necesario **acceder a las siguientes opciones** de nuestro dispositivo:

1. **Ajustes**
2. **Acerca del teléfono**
3. **Información de software**

<!--![developerModeOff](resources/img/Screenshot_20200319-122937_Settings.jpg =150x50)-->

<img src="resources/img/Screenshot_20200319-122937_Settings.jpg" title="developerModeOff" width="25%" height="25%">

Una vez nos encontremos en la interfaz de **Información de software** solo tienes que **presionar 7 veces** la opción **Número de compilación**.

<img src="resources/img/Screenshot_20200319-122958_Settings.jpg" title="developerModeOn" width="25%" height="25%">

Desde este momento tu dispositivo ya cuenta con el **modo desarrollador** activado y las **opciones de desarrollador** deben encontrarse visibles y disponibles en la interfaz de **ajustes**.

<img src="resources/img/Screenshot_20200319-123017_Settings.jpg" title="developerOptions" width="25%" height="25%">

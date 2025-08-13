---
title: Intro to Branches
deprecated: false
hidden: false
link:
  new_tab: false
metadata:
  title: ''
  description: ''
  robots: index
---
🚧 Beta

Esta característica está en desarrollo activo y puede cambiar antes del lanzamiento final. Siempre se agradecen los comentarios en [beta@readme.com](beta@readme.com).

Las ramas permiten a los administradores de ReadMe guardar cambios en las páginas sin que se publiquen inmediatamente. ¡Con las ramas, puedes seguir editando como siempre lo has hecho! Las ramas son un flujo de trabajo opcional que ofrece flexibilidad en tu proceso de escritura. Los escritores usan las ramas para:

*   Realizar cambios y revisarlos en un entorno de vista previa antes de que estén activos.
*   Enviar cambios a los compañeros de equipo para su revisión.
*   Realizar cambios en varias páginas.

<Callout icon="💁‍♂️" theme="default">
  **Nota:** Las opciones de revisión adicionales solo están disponibles en los planes Enterprise.
</Callout>

***

## Creando una Rama

Hay tres formas de crear una rama:

1.  Navega al menú de versiones y ramas. Una vez allí, puedes crear nuevas ramas a partir de una versión.
2.  Mientras editas una versión, en lugar de guardar, puedes guardar en una nueva rama.
3.  Si estás [sincronizando con GitHub](https://docs.readme.com/main/docs/bi-directional-sync), las ramas creadas en GitHub aparecerán en ReadMe. ¡Y las ramas creadas en la interfaz de usuario de ReadMe aparecerán automáticamente en GitHub!

Una vez creada tu rama, ¡puedes empezar a escribir! Los cambios no se publicarán hasta que fusiones tu rama en una versión pública.

<Image align="center" src="https://files.readme.io/66750bb4ffdf062a43e77e2ce1a3bfc6d36a2c6fa670e3968b621159ab7b177a-branches_1.png" />

No hay límite de tiempo ni vencimiento en las ramas. Cualquier administrador de tu equipo puede ver, editar, fusionar y eliminar cualquier rama.

## Fusionando una Rama

Una vez que estés listo para que los cambios se publiquen, puedes fusionar desde el menú de ramas:

<Image align="center" src="https://files.readme.io/51f1614616e3ee1fac70268bd784076acd002ec15809843ee495b576f0a31086-branches_2.png" />

Al fusionar, se realizará una comprobación para asegurar que no haya conflictos de fusión. Si hay conflictos que deben resolverse, recomendamos [resolver los conflictos desde GitHub](https://docs.readme.com/main/docs/branches#/handling-conflicts). Si tu proyecto no se sincroniza con GitHub, puedes ignorar el conflicto y fusionar forzosamente tus cambios, con preferencia a los cambios en la rama.

Una vez fusionadas, tus ramas no se eliminan para que puedas revisar los cambios antes de eliminarlas.

<Callout icon="💁‍♂️" theme="default">
  Los usuarios de GitHub también pueden fusionar una rama en una versión, incluso a través de Pull Requests.
</Callout>

***

## Sincronizando con GitHub

No tienes que sincronizar con GitHub para usar ramas.

Al crear ramas desde GitHub, su nombre debe tener el formato para incluir su versión: `{version}_{rama}`. Ejemplos:

```
v2.0_reescribir-empezar
v2.0_agregar-nueva-funcion
v2.0_corregir-error
```

### Acceso y Permisos

Los permisos de ReadMe y GitHub son independientes. Los usuarios con acceso a las ramas de tu proyecto de GitHub tendrán acceso a cualquier cambio de contenido. Para que los usuarios puedan ver los cambios de contenido realizados en las ramas a través de GitHub, necesitarán una cuenta de ReadMe con acceso a la rama de tu proyecto.

### Manejo de Conflictos

Al fusionar desde GitHub, el usuario puede resolver los conflictos a través del editor de GitHub o la herramienta de fusión de su elección localmente antes de hacer push.

Al fusionar desde ReadMe, los cambios que ves al previsualizar siempre coincidirán con lo que se publica al fusionar. Los cambios conflictivos de GitHub no aparecerán.

***

## Preguntas Frecuentes

<Accordion title="¿Quién puede ver una rama?" icon="fa-help-circle">
  En este momento, cualquiera con el enlace puede ver una rama.
</Accordion>

<Tabs>
  <Tab title="Primera Pestaña">
    Bienvenido al contenido que solo puedes ver dentro de la primera pestaña.
  </Tab>

  <Tab title="Segunda Pestaña">
    Aquí tienes contenido que solo está dentro de la segunda pestaña.
  </Tab>

  <Tab title="Tercera Pestaña">
    Aquí tienes contenido que solo está dentro de la tercera pestaña.
  </Tab>
</Tabs>
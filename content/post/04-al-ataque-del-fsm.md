---
title: "04 Al ataque del FSM"
date: 2013-04-08T19:10:00
categories:
- Misc
tags:
- Desarrollo
- Personal
---

Mientras tomo un café recuerdo cuando inicié un proyecto hace un par de años
hice las cosas de mejor manera, implementé una estructura de archivos
usaba los estándares de calidad de código, empezé a investigar sobre pruebas
unitarias, implementé un par de test de ejemplo y empezé mi desarrollo usando
el mejor framework en la última versión que podia encontrar.

Con el tiempo, debido a presiones de tiempo empezé a creer que algunas cosas
sobraban, dejé de lado los tests por que consumían tiempo, deje de consultar
a mi cliente as cosas hasta tener funcionalidades completas para evitarme su
charla de 10 minutos sobre como tendría que ir la lógica, empezé a solucionar
los posibles errores en el lugar donde ocurría programé alocadamente con el fin
de llegar a tiempo y me empezaba a sentir mal por ser tan lento en desarrollo.

<!-- more -->

Por (buena o mala) suerte estaba trabajando solo asi que podia entender todo lo
que hacía y podía seguir así en adelante, pero no duro por mucho, empezamos a
poner el sistema en producción, es cuando uno cae del cielo al infierno y es
cuando tu cliente deja de sonreirte.

Todos los *pequeños bugs* que dejé de lado aparecían (y no eran tan pqeueños
como me lo imaginé) hacer una correccion era un salto al vacio por que no
podias estar seguro de que otra cosa se rompa, los cambios *extras* que hice
no se hicieron en el lugar correcto y por ende tengo la lógica de la aplicacion
en varios lugares distintos.

Gastaba más tiempo corrigiendo cosas anteriores que desarrollando cosas futuras,
mi productividad decreció y empece a aburrirme de mi trabajo.

Cambie de empleo, aprendí nuevas cosas recordé muchas y siempre tengo muy
presente los errores que cometí antes para no volverlos a hacer.

Ahora termino mi cafe, me espera una jornada muy dura pues tengo que volver a
luchar contra el Mounstro Espaguetti Volador pero ahora si tengo la técnica
y se como enfrentarme a él se que poco a poco sera un codigo mejor.

Cosas que aprendí de esto:

* Las mejores herramientas no sirven de mucho, si no te apoyas en una buena
  arquitectura.
* Un bug es un eufenismo de error, no es algo casual, si hiciste un error en tu
  código corrígelo, se duro, es tu error.
* Piensa con calma al plantear una solución tiene repercusión en al futuro
* Tu cliente/jefe es tu amigo, es una sociedad tu mejoras como desarrollador
  y el mejora su empresa con tu sistema.
* Siempre haz pruebas y automatízalas existe algo llamado TDD practícalo no te
  defraudará.
* La calidad no se negocia, no sacrifiques tiempo por ello por que al final
  podrias parar días solo corrigiendo errores.

En conclusíon, si vas a hacer las cosas, hazlas bien! es la única forma de
avanzar sin arrepenirte después, no digo que mi codigo apeste del todo pero
podría ser mejor.

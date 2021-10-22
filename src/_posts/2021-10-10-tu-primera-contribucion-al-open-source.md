---
layout: post
title:  "Tu primera contribucion"
date:   2021-10-10 12:00:42 -0500
categories: updates
---
Bueno... pues aqui voy 🏃🏻

Estoy a unas cuantas horas de dar una charla en una comunidad por lo del Hacktoberfest, en la cual compartiré algunos consejos practicos acerca de como contribuir al open source, asi como, cual ha sido mi experiencia contribuyendo a este. Y bueno, a pesar de que queria llevar esta charla de forma casual y "a capela", me parecio buena idea dejar estas mismas ideas por escrito.

Cabe mencionar que no soy una persona que contribuya frecuentemente, ni que haya hecho contribuciones a los proyectos mas importantes que estan ahi fuera, pero creo que tengo algunas ideas que compartir  que espero sean de utilidad.

Dicho eso, solo dejo un friendly reminder de que esto no es una guia definitiva, solo son consejos y experiencias que queria compartir.

## Por dónde empiezo? 🤔

Como requisito indispensable tenemos que saber usar Git. Creo que no podría hablar acerca de como contribuir sin mencionar esta super herramienta, pero no te preocupes, no voy a meterme en detalles acerca de como crear una rama o como hacer un commit y mucho menos en como hacer un rebase.; pero considero que si era necesario mencionar que es la primer herramienta que necesitaras para poder contribuir.  Considera aprender a usarla, ya que muchos de los proyectos open source la usan para tener control y versionado del código.

Supongamos que ya sabes usar Git y que no hay problema en ello... y ahora? Que repo puedo clonar y llenar de PR's?

Y yo te dire: "Cual es la prisa?"

Tristemente no tengo la receta magica para poder decirte: "Puedes ir a este repositorio y ahi hacer contribuciones. Anda, ve y manda código para que no te ganes tu playera". Honestamente no es mi intención.

Se que parte del Hacktoberfest es el cumplir con cierto numero de contribuciones, para que puedas ser una de las personas que se lleven ese flamante swag, pero me gustaria ir un poco mas alla...

Empezando por...

## El codigo NO es la unica forma de contribuir

Desde hace un tiempo tengo la creencia de que la forma mas facil de contribuir a un proyecto es actualizando la documentacion. Esta es una buena forma de:

1. Familiarizarte con el proyecto (conceptos, alcance, uso, etc).
2. Compartir lo que aprendiste y mantener al dia la documentacion o guias.
3. Ayudar a bajar la barrera de entrada, y que asi sea mas facil que el proyecto se adopte.
4. Le ahorras tiempo a la comunidad, y si trabajas en un proyecto que use esa libreria, muy probablemente le ahorres tiempo a tu equipo para comprender como es que esta funciona, e incluso, por que no, a tu yo del futuro (en caso que seas una persona super olvidadiza como yo 😂)

Ademas de eso, hay varios proyectos de traduccion de documentacion. Si hay algun proyecto que sea de tu interes, es una buena oportunidad para aprender y contribuir.

## Reportar un problema es otra forma de contribuir

Si al momento de estar usando un framework, notas que una funcion no se comporta como se esperaria, puedes reportarlo e incluso pedir ayuda. Por lo general proveen un canal de soporte por medios como discord, slack, algun foro como discourse o en la misma plataforma donde alojen el proyecto.

Esta es una forma de contribuir que el Hacktoberfest no considera, pero que ayuda mucho a que los proyectos mejoren y a que sigan madurando.

Hay ocasiones en las que los errores no son problema de la libreria, sino de otras dependencias externas, y las conversaciones que se tienen en esos espacios o foros ayudan a obtener soluciones. Soluciones que quedan publicas y que sirven como documentación para la comunidad.

En lo personal me he beneficiado de muchos thread en GitHub que me han ayudado a resolver muuuucho problemas 😂

## Desde tu propia comezon

> I kind of write code these days based on my own needs or interest
- Kelsey Hightower

De las formas mas faciles de contribuir a un proyecto open source es resolviendo tus propios problemas... "Rascando tu propia comezon"

Imagina lo dificil que ha de ser llegar a un proyecto, ya con cierta madurez como: Rails, Django, React, Vue, Phoenix... etc, y querer hacer un cambio al proyecto sin antes haberlo usado o sin saber como funcionan.

Muy distinto seria resolver problemas conforme se nos presentan, conforme vamos haciendo uso de las herramientas y nos vamos familiarizando con el proyecto.

Es verdad que muchos proyectos tienen issues etiquetados como "Friendly begginer". Esa es otra forma de empezar a contribuir a un proyecto, pero mi recomendacion es que lo hagas en proyectos que sean de tu interes, o que ya estes usando y que te daran cierto grado de expertiz en un lenguaje o ecosistema. NO hay ninguna presion por contribuir, por el contrario, puedes ir contribuyendo conforme se vayan dando las oportunidades y conforme vayas aprendiendo en el camino.

Y esto no aplica solo para proyectos ya existentes, sino que puedes open sourcear cualquier proyecto que te haya servido para solucionar un problema. Comparemos lo siguiente:

1. Inventar un problema y una solucion para poder open sourcear un proyecto
2. Open sourcear un codigo que ya te soluciono una necesidad que tenias y que puedes abstraer y compartir con la comunidad.

En el segundo escenario ya tienes la solucion y el codigo, solo hace falta hacerlo open source.

Esta es una filosofia que evangelizan mucho compañias como Basecamp, figuras del open source como Evan You (mantainer de Vue), Kelsey Hightower (Principal Software Eng en Google y mantainer de Kubernetes) y es una filosofia que me gusta seguir a mi tambien 😄

## Hazlo por diversion

> When I published it, wasn't really saying "I want to publish it as somewhat sustainable project. I'd say it was like a music enthusiast just making an album for fun
- Evan You

Hacer codigo por diversion y hacerlo open source es otra forma de contribuir.

Han habido proyectos como Vue, los cuales eran meramente experimentales, que terminaron siendo usados en organizaciones como la NASA. Nunca se sabe hasta donde va a llegar tu codigo, huh?!

Aunque, no todos los proyectos tienen que resolver una super necesidad para la industria, puede ser simplemente por pasar un buen rato o para hacer mas "ergonomico" tu setup.

Por ejemplo, uno de mis mejores amigos y mentor, Juan Carlos Ruiz (@JuanCrg90), hizo una CLI para poder mejorar su flujo de trabajo. Esta CLI te deja abrir PR's o commits desde la terminal y asi evitar distraerte con cualquier otra cosa en el navegador. Tal vez no suene a un problema grande, pero sin querer es una de las primeras utilerias que instalo en mi terminal cada que cambio de maquina y que creo que ha mejorado mi workflow mucho (soy una persona que se distrae facilmente) 😅. Ademas de que en ese proyecto pude hacer mis primeras contribuciones, con el creador del CLI, mientras tomabamos unas cervezas 🍻

Asi que con eso, puedo confirmar que hacer open-source puede ser divertido.

## Tu código no tiene que ser perfecto

No esperes a que tu código luzca perfecto para poder liberarlo. La unica forma de saber si este funciona es si alguien mas empieza a usarlo.

Lo mismo aplica al momento de contribuir a un proyecto ya existente. Hasta que no hayas creado un Pull request, no vas a recibir comentarios o retroalimentación. 
Hay muchas cosas que se aprenden al recibir comentarios, es algo normal y NO es una critica a tu codigo ni mucho menos a tu persona. Es mejor tomarlo como una oportunidad para aprender mas acerca del framework y sobre todo, para mejorar tus habilidades de programacion.

De hecho, si revisas proyectos como Rails, veras que muchos pull-request pasan por un proceso de retroalimentación antes de que se lleguen a master/main. Y lo mismo pasa otros proyectos.

## Como reducir la friccion en un Pull Request

Por ultimo, hablemos de como hacer mas facil el review de nuestros pull-requests

Por que, al final del dia, un PR es una forma de comunicar el "por que" de los cambios. Me refiero a que, el codigo esta ahi... los cambios se ven, pero hay algunas cosas que podemos hacer para que nuestro cambios sean mas faciles de comprender. Y son cosas super sencillas, tampoco es cosa del otro mundo, cosas como:

1. Seguir las guias de contribucion si es que las tienen
2. Seguir el mismo estilo de codigo del proyecto: Esto ayuda mucho a que el codigo se sienta familiar. Es un detalle que se aprecia y que ayuda a que el proyecto sea consistente.
3. Un titulo consico, breve y descriptivo
4. Una descripcion de lo que se esta intentando resolver sin entrar en detalles tecnicos. Es mas valioso mencionar cosas como _que se esta agregando o resolviendo_ y _el porque_. En caso de  ser un bug que ya habia sido reportado, agregar las referencias se aprecia mucho.
5. De ser posible, y si el proyecto sigue esta practica: Agregar pruebas unitarias
6. Si se requiere probar algo manualmente, instrucciones claras de como probarlo, o screenshots en caso de que sean cambios visuales. 😄

Y bueno, eso es todo lo que queria compartir haha, en serio muchas gracias si llegaste hasta aqui. Solo para no dejarte con el pendiente, termine esto 1 hora antes del evento!, asi que no esta tan mal, huh!? 😂

Espero que lo que comparto te sea de utilidad o cualquier tipo de retroalimentacion tambien es super bien recibida. Mis DM estan abiertos en Twitter (`@eduardohgto` )

Por ultimo, si estos son de tus temas de interes, te invito a que participes en Calzada Code. Es una comunidad en la que participo en mi ciudad, Leon, Guanajuato. Actualmente operamos de forma virtual, con charlas en vivo una vez al mes, ademas de que nos reunimos despues de la charla para hacer un poco de networking, jugar videojuegos o simplemente echar una cerveza virtual.

Muchas gracias de nuevo y que el codigo te acompañe 🤖

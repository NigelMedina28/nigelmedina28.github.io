---
layout: post
title: "Proceso de Ingenieria de software"
excerpt: "Es el grado con el que un sistema, componente o proceso cumple los requerimientos especificados y las necesidades o expectativas del cliente o usuario."
categories:
  - Unidad 1
tags:
  - Definicion
---

## Factores de calidad del software

### Calidad del Software

Es el grado con el que un sistema, componente o proceso cumple los requerimientos especificados y las necesidades o expectativas del cliente o usuario.

Factores que determinan la calidad del software. Se pueden clasificar en dos grandes grupos (Pressman):

* Medidas Directas

    La medida o medición decimos que es directa, cuando disponemos de un instrumento de medida que nos muestra un resultado (generalmente numérico).

* Medidas Indirectas

    Cuando hablamos de sistemas informáticos no siempre es posible realizar una medida directa, porque no disponemos del instrumento adecuado que nos permita realizar esa medición

### Métricas del Software

Son las que están relacionadas con el desarrollo del software como funcionalidad, complejidad, eficiencia.

* Métricas técnicas

    Se centran en las características del software. Aquí medimos la complejidad lógica y el grado de modularidad del sistema. Mide la estructura del sistema, el cómo está hecho.

* Métricas de calidad

    Son todas las métricas de software que definen de una u otra forma la calidad del software; tales como corrección, exactitud,integridad, facilidad de uso, estructuración o modularidad, pruebas, facilidad de mantenimiento, reusabilidad, cohesión del módulo, acoplamiento del módulo, etc.

Proporcionan una indicación de cómo se ajusta el software a los requisitos implícitos y explícitos del cliente. Es decir cómo voy a medir para que mi sistema se adapte a los requisitos que me pide el cliente.

**Corrección:** es el grado en que el software desempeña la función para la que fue creado y se mide en defectos por KLDC.

**Facilidad de Mantenimiento:** es la sencillez con que un programa puede corregirse si se encuentra un error, al adaptarse si su entorno cambio o mejorar si el cliente cambia los requisitos y se mide en forma indirecta en TMC (Tiempo Medio de Cambio).

**Integridad:** es la habilidad de un sistema para resistir ataques que requiere la definición de amenaza y seguridad y se calcula: integridad = 1 – (amenaza * (1 – seguridad)).

**Facilidad de uso:** Es el intento por cuantificar la sencillez de una aplicación al utilizarla.

* Métricas de Productividad

    Se centran en el rendimiento del proceso de la ingeniería del software. Es decir qué tan productivo va a ser el software que voy a diseñar. Se refiere a las características del software.

* Métricas de costo

    se centra en el costo total del sistema informático.

* Métricas orientadas al tamaño

    Esta nos permite conocer el tiempo en el que se terminará el software y cuántas personas se necesitan para su desarrollo, aquí medimos las variables con las que desarrollamos el software.

Con los datos registrados durante la elaboración del proyecto podemos generar al final de dicho proyecto el siguiente conjunto de métricas:

1. Productividad = KLDC /Esfuerzo
2. Calidad = Errores / LDC
3. Documentación = Pp.doc./LDC
4. costo = $(000)/LDC

* Métricas orientadas a la función o puntos de función

    Las métricas de función se centran en la funcionalidad o utilidad del programa. Los puntos de función nos indican la medida de la productividad.

## Problemas en el desarrollo de software

### ¿Qué es un proyecto software?

Según la definición del IEEE, "software es la suma total de los programas de ordenador, procedimientos, reglas, la documentación asociada y los datos que pertenecen a un sistema de cómputo", y "un producto de software es un producto diseñado para un usuario".

El software puede dividirse en dos grandes categorías:

**Software de aplicaciones:** se usan para proveer servicios a clientes y ejecutar negocios de forma más eficiente. El software de aplicaciones puede ser un sistema pequeño o uno grande integrado. Como ejemplos de este tipo de software estarían un sistema de cuentas, un sistema de planificación de recursos.

**Software de sistemas:** El software de sistemas se usa para operar y mantener un sistema informático. Permite a los usuarios usar los recursos del ordenador directamente y a través de otro software. Algunos ejemplos de este tipo de software son los sistemas operativos, compiladores y otras utilidades del sistema.

## Ingeniería del software

Los proyectos software tienen características específicas que los hacen diferentes de otros proyectos de ingeniería. La Ingeniería del Software es la rama de la ingeniería que crea y mantiene las aplicaciones de software usando tecnologías y prácticas de las ciencias de la computación, manejo de proyectos, ingeniería, el ámbito de la aplicación, y otros campos.

El software se **desarrolla**, no se **fabrica** en el sentido clásico de la palabra. Ambas actividades se dirigen a la construcción de un "producto", pero los métodos son diferentes. Los costes del software se encuentran en la ingeniería, esto implica que los proyectos no se pueden gestionar como si lo fueran de fabricación.

La juventud de la ingeniería del software con respecto a otras ingenierías, la mayoría del software se construye a **medida**, en vez de **ensamblar** componentes previamente creados. Aunque ya se están dando importantes pasos en esta dirección, que facilitaría en gran medida el desarrollo de aplicaciones informáticas.

El software no se estropea, pero se **deteriora**. Durante su vida, el software sufre cambios (**mantenimiento**). Conforme se hacen los cambios, es bastante probable que se introduzcan nuevos defectos, lo que hace que el software se vaya deteriorando debido a estos cambios.

## Visión general del proceso de ingeniería del software

Con independencia del área, tamaño o complejidad del proyecto, cualquier proyecto se encontrará al menos en una de las siguientes fases:

* Definición ~ Análisis (del sistema, del sw).
* Desarrollo ~ Diseño, codificación, prueba.
* Mantenimiento.

### Definición

¿Qué debe hacer el sistema?

* Información que ha de manejar el sistema.
* Necesidades de rendimiento.
* Restricciones de diseño.
* Interfaces del sistema con los usuarios y con otros sistemas.
* Criterios de validación.

### Desarrollo

¿Cómo construir el sistema?

* Se diseñan las estructuras de los datos y los programas.
    * Como se caracterizan las interfaces.
    * Como realizar el paso del diseño al lenguaje de programación.
    * Como ha de realizarse la prueba.
* Se escriben y documentan los programas.
* Y se prueba el software construido.

### Mantenimiento

* Comienza una vez construido el sistema.
* Se centra en el **cambio**.
* El software es sometido a reparaciones y modificaciones cada vez que se detecta un fallo o se necesita cubrir una nueva necesidad de los usuarios.
* En esta fase recae el mayor porcentaje del costo de un sistema.
* Un buen sistema no es sólo un conjunto de programas que funcionan bien => **Debe ser fácil de mantener**

#### Tipos de mantenimiento.

* **Correctivo.** El programa no funciona correctamente, hay que modificarlo.
* **Perfectivo.** Se modifica el programa para obtener más eficiencia o nuevas funcionalidades no especificadas en la definición del sistema.
* **Adaptativo.** Adaptar el programa a los cambios en su entorno (cambio de SO, de CPU, de legislación, …)
* **Preventivo.** El software se deteriora con los cambios, este mantenimiento hace cambios para que los programas se puedan corregir, adaptar y mejorar más rápidamente -> Reingeniería del SW.
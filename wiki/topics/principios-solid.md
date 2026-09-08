---
title: "Principios SOLID"
aliases: ["SOLID principles"]
sources: ["OFF-004"]
related: ["diseno-de-software", "orientacion-a-objetos", "arquitectura-de-software"]
prerequisites: ["orientacion-a-objetos"]
---

# Principios SOLID

## Overview

SOLID reúne cinco principios sobre las dependencias y relaciones entre clases: responsabilidad única, abierto/cerrado, sustitución de Liskov, segregación de interfaces e inversión de dependencias. [OFF-004, p. 2]

## Conceptos centrales

El principio de responsabilidad única asocia la responsabilidad de una clase con sus actores: una clase debe tener una sola razón de cambio, proveniente de un actor que requiere ese cambio. [OFF-004, p. 3]

El principio abierto/cerrado busca cambiar el comportamiento sin modificar el código fuente y se apoya en abstraer e invertir dependencias. No pretende anticipar todos los cambios: protege frente a cambios que se conocen como posibles. La presentación contrasta el diseño anticipado con un diseño ágil, iterativo, evolutivo y reactivo. [OFF-004, p. 3]

La sustitución de Liskov exige que los subtipos no sorprendan a sus clientes al alterar el comportamiento del tipo padre; para este fin, la relación «puede usarse como» es más precisa que solo «es un». [OFF-004, p. 4]

La segregación de interfaces descompone abstracciones grandes e incoherentes en otras más pequeñas y cohesivas; las interfaces se relacionan con sus usuarios antes que con sus implementadores. [OFF-004, p. 5]

La inversión de dependencias distingue el flujo de control en ejecución de las dependencias de código fuente y compilación. Permite crear límites y establece que los módulos de bajo nivel deben depender de los módulos de alto nivel. [OFF-004, p. 5]

## Relaciones

Estos principios refinan el [diseño de software](diseno-de-software.md) orientado a objetos. La inversión de dependencias es central para la [arquitectura de software](arquitectura-de-software.md) presentada en el curso.

## Fuentes

- [OFF-004, pp. 2-5]

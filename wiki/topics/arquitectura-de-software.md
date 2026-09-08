---
title: "Arquitectura de software"
aliases: ["software architecture", "clean architecture"]
sources: ["OFF-003"]
related: ["diseno-de-software", "orientacion-a-objetos", "principios-solid"]
prerequisites: ["diseno-de-software"]
---

# Arquitectura de software

## Overview

La arquitectura busca preservar la capacidad de cambio del software. La clase presenta la arquitectura limpia y sostiene que el software debe permanecer flexible. [OFF-003, pp. 3, 7]

## Conceptos centrales

Entre las responsabilidades del arquitecto aparecen las decisiones sobre paradigma y lenguaje de programación, frameworks, patrones de diseño, base de datos, interfaz, documentación, metodología de desarrollo y hardware de despliegue. El rol debe posponer esas decisiones el mayor tiempo posible para mantener abiertas la mayor cantidad de opciones durante el mayor tiempo posible. [OFF-003, pp. 4-5, 8]

La descomposición del software distingue políticas de detalles. Las reglas de negocio corresponden a las políticas, mientras que los detalles dependen de esas reglas. [OFF-003, pp. 9, 15, 17]

La dirección de dependencias se orienta a las interfaces: el ejemplo usa las abstracciones `Reader` y `Writer` desde el componente de negocio y deja las implementaciones de consola como detalles. El componente `Main` instancia y conecta esas implementaciones concretas. [OFF-003, pp. 16, 18-20]

## Relaciones

La arquitectura extiende el [diseño de software](diseno-de-software.md) a las decisiones de estructura y dependencias. La inversión de dependencias se vincula directamente con los [principios SOLID](principios-solid.md) y se expresa sobre abstracciones propias de la [orientación a objetos](orientacion-a-objetos.md).

## Fuentes

- [OFF-003, pp. 3-20]

---
title: "Trabajo integrador — Entrega 1"
aliases: ["CertiFlow", "módulo de dominio"]
sources: ["OFF-001"]
related: ["diseno-de-software", "arquitectura-de-software", "principios-solid"]
prerequisites: []
---

# Trabajo integrador — Entrega 1

## Overview

La primera entrega del trabajo integrador consiste en modelar el dominio de una plataforma de inspección, habilitación y certificación de activos. La consigna enfatiza la calidad del modelado, la separación de responsabilidades y la extensibilidad, además del funcionamiento del sistema. [OFF-001, p. 1]

## Dominio y alcance

La entidad certificadora inspecciona activos técnicos. Cada tipo de activo tiene un esquema de inspección compuesto por criterios, evidencias obligatorias, niveles de severidad y reglas de aprobación. Los esquemas se versionan: una inspección debe conservar las reglas vigentes al iniciarse aunque luego se publique una nueva versión. [OFF-001, p. 1]

El sistema debe administrar activos y esquemas versionados; asignar y ejecutar inspecciones; registrar respuestas, mediciones, evidencias y observaciones; determinar evaluaciones y hallazgos; gestionar acciones correctivas y el ciclo de vida de certificados; conservar auditoría e informar resultados. Una inspección cerrada no se altera libremente: las correcciones se realizan por una rectificación auditable. [OFF-001, pp. 1-2]

## Entrega requerida

El entregable central es un módulo de dominio Java compilable y probado, con modelos de negocio, contratos y casos de uso relevantes implementados. Debe incluir tests unitarios y de integración para los casos de negocio relevantes, un repositorio con la URL y el hash del commit de entrega, y un archivo `DESIGN.md` que documente decisiones, alternativas descartadas y patrones no aplicados. [OFF-001, p. 2]

No se exige API REST, persistencia real, frontend, seguridad ni despliegue en esta entrega. [OFF-001, p. 2]

## Relaciones

El trabajo aplica [diseño de software](diseno-de-software.md), [arquitectura de software](arquitectura-de-software.md) y [principios SOLID](principios-solid.md) al módulo de dominio solicitado.

## Relevancia para la entrega

La consigna exige explícitamente demostrar en código la comprensión del dominio y un diseño extensible, además de documentar las decisiones principales. [OFF-001, p. 2]

## Fuentes

- [OFF-001, pp. 1-2]

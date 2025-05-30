---
date: '2025-03-09T16:59:40-03:00'
draft: false
title: 'Dinámica del Comportamiento'
weight: 2_000
---

Identificar los componentes fundamentales del análisis de sistemas es un desafío. A menudo imponemos estructuras jerárquicas, pero estas pueden entrar en conflicto con la complejidad de las interacciones sistémicas. Además, comenzar con un modelo demasiado simplista o excesivamente complejo puede generar problemas a medida que se desarrolla el análisis.

Ofreceremos un modelo denominado **Dinámica del Comportamiento**. Este modelo contiene un fenómeno sistémico principal (**Comportamiento**) y tres entidades sistémicas principales (**Sistema**, **Miembro**, **Medio**).

- **COMPORTAMIENTO**: La transformación de un medio por los miembros del sistema.

- **SISTEMA**: Un entorno donde los miembros interrelacionados expresan su comportamiento.

- **MIEMBRO**: Una unidad que expresa un comportamiento dentro de un sistema.

- **MEDIO**: Componentes de un sistema transformados por sus miembros para expresar su comportamiento.

```mermaid
---
title: Dinámica del Comportamiento
---
flowchart LR
    A(Sistema)
    B(Miembro)
    C(Medio)
    A <-- comportamiento --> B
    B <-- comportamiento --> C
    C <-- comportamiento --> A
```

La existencia de las tres entidades principales y el comportamiento sistémico son simultáneos e interrelacionados. En esencia, este esquema analítico es simplemente un recurso intelectual para explorar su interacción. Ampliaremos este modelo en futuras discusiones, ya que nuestro enfoque aquí es la Conciliatórica. Sin embargo, necesitábamos un marco de partida para el siguiente análisis.

Otros modelos sistémicos de partida, similares a la Dinámica del Comportamiento, pueden ser compatibles con la Conciliatórica, siempre que no obstaculicen sus propósitos. Agradecemos las conexiones analíticas con otros modelos para ampliar la cobertura de la Conciliatórica. Y si posteriormente se encuentra un mejor modelo de partida (ya sea endógeno o por sugerencia externa), lo adaptaremos al resto del trabajo.


# ¿Qué es un Servicio?

Un **servicio** representa una **unidad lógica y funcional del sistema**, diseñada para abordar una tarea específica o un conjunto de tareas relacionadas

## Responsabilidades y límites

Las responsabilidades de un servicio buscan:

- Claridad en su propósito
- Reducción de la complejidad
- Independencia y cohesión

Esto facilita:

- Escalabilidad
- Flexibilidad
- Reutilización
- Modularidad

---

# Domain-Driven Design (DDD)

## Enfoque

DDD se centra en **comprender el dominio del problema** y reflejar esa comprensión en el diseño del software

## Principios básicos

- Lenguaje ubicuo
- Contextos delimitados (Bounded Contexts)
- Entidades
- Objetos de valor
- Agregados

## Pros vs. Contras

### Pros

- Software y procesos más flexibles
- Claridad ante problemas complejos
- Comunicación efectiva entre expertos y desarrolladores
- Código bien organizado y aislado

### Contras

- Aislar la lógica de negocio lleva mucho tiempo
- Se necesita un experto de dominio
- Curva de aprendizaje alta
- No recomendado para aplicaciones simples o CRUD

---

# Acoplamiento (Alto vs. Bajo)

## Definición

El **acoplamiento** es el grado de interdependencia entre los componentes de un sistema

## Importancia en Microservicios

El **bajo acoplamiento** es clave para:

- Independencia
- Escalabilidad
- Flexibilidad
- Mantenibilidad

## Acoplamiento Bajo

### Beneficios

- Promueve independencia y modularidad
- Facilita reutilización y despliegue independiente
- Permite mayor flexibilidad ante cambios

### Tips para lograr bajo acoplamiento

- Definir interfaces claras
- Segregar la base de datos por servicio
- Implementar patrones de mensajería
- Aplicar principios SOLID
- Evitar acoplamiento directo
- Descomponer funcionalidades complejas

---

# Descomposición de un Monolito

## Razones para migrar

- Escalabilidad independiente
- Flexibilidad tecnológica
- Despliegues continuos y rápidos
- Mejora de la resiliencia
- Facilita la colaboración
- Evolución progresiva del sistema

## Estrategias para una descomposición gradual

- Identificar dominios contextuales
- Crear capas de servicios
- Usar facades o adaptadores
- Aplicar patrones Gateway o Proxy
- Separar funcionalidades por módulos
- Refactorizar de forma incremental


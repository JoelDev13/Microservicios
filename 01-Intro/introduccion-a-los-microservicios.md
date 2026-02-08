# Microservicios — Notas de Repaso

## Idea clave
**No todo debe ser microservicios**  
La arquitectura depende del contexto, equipo, tiempo y dinero

---

## Monolitos 

### Qué son?
- Una sola aplicación
- Una sola base de código
- Un solo despliegue
- Generalmente una sola base de datos

### Pros 
- Fácil de desarrollar
- Fácil de desplegar
- Fácil de monitorear
- Sin latencia interna
- Menos decisiones técnicas

### Contras 
- Escalar partes específicas es costoso
- Cambios pequeños pueden romper todo
- Difícil de modificar al crecer
- Stack tecnológico limitado

### Ejemplo 
Una app Django que maneja:
- Artículos
- Pagos
- Envíos
- API

Todo vive junto

### Cuándo usar monolitos? 
- Proyectos nuevos
- Poco presupuesto 
- Equipos pequeños
- Tiempo limitado

---

## Microservicios 

### Qué son?
- Muchas aplicaciones pequeñas
- Cada una es independiente
- Corren en procesos separados
- Se comunican por HTTP / APIs

### Pros 
- Escalabilidad independiente
- Flexibilidad tecnológica
- Servicios desacoplados
- Datos descentralizados

### Contras 
- Comunicación compleja
- Sincronización de datos
- Latencia de red
- Monitoreo avanzado
- Versionamiento
- Más costos
- Más personas
- Seguridad más compleja

---

## Monolitos o Microservicios?
**Ambos pueden coexistir**

- Arquitecturas híbridas son comunes
- Ejemplo:
  - React (cliente)
  - Django (backend)

---

## Regla práctica 
Empieza monolito, migra a microservicios **solo cuando el problema lo exija**

---
Fecha de creación: 2025-08-04 23:53
Fecha de Modificación: 2025-08-04 23:53
tags:
  - arquitectura
Topic:
---

---

## 📚 Idea/Concepto 

La arquitectura de software microkernel es un estilo de diseño donde el sistema se divide en una parte central mínima (el microkernel) y varios módulos o plug-ins que añaden funciones adicionales. El núcleo maneja las tareas básicas y la comunicación, mientras que las funciones específicas se implementan como componentes separados registrados en un Registry, que permite su descubrimiento e integración. Este modelo mantiene el núcleo simple y estable, reduciendo la complejidad y facilitando la extensión, el mantenimiento y las pruebas del sistema.

## 📌 Puntos Claves (Opcional)
- **Microkernel:** núcleo mínimo que gestiona tareas básicas y comunicación.
- **Módulos o plug-ins:** añaden funciones específicas de forma independiente.
- **Registry:** permite descubrir e integrar componentes externos.
- **Ventajas:** núcleo estable, fácil extensión, mantenimiento y pruebas.

## 🔗 Connections
- [[Cohesión en desarrollo de software]]
- [[Acoplamiento en desarrollo de software]]
{Aquí se agregan los links a otras notas relacionadas. Solamente ponga \[\[ Nombre de nota \]\] sin los "\"}
## 💡 Personal Insight (Opcional)
- {reflexiones personales sobre el concepto que desean capturar, ideas que quieran explorar después o potenciales usos}
## 🧾 Recursos (Opcional)
- {cualquier link a material donde se hable del concepto que quieran recordar}
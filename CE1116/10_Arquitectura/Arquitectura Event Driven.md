---
Fecha de creación: 2025-08-04 23:53
Fecha de Modificación: 2025-08-04 23:53
tags:
  - arquitectura
Topic:
---

---

## 📚 Idea/Concepto 

Es un estilo de diseño donde los componentes se comunican de forma asíncrona mediante eventos, que son hechos inmutables que ya ocurrieron. Los productores publican eventos y los consumidores se suscriben a ellos usando el patrón Publish/Subscribe, lo que permite un alto desacoplamiento y facilita la escalabilidad y el mantenimiento del sistema. El flujo se gestiona a través de un event hub o backbone, que distribuye y registra los eventos, permitiendo incluso reanálisis de datos históricos. Sin embargo, este desacoplamiento implica que los consumidores deben mantener su propio estado, lo que añade complejidad en la gestión y coherencia de los datos

## 📌 Puntos Claves (Opcional)
- **Comunicación asíncrona:** basada en eventos inmutables ya ocurridos.
- **Patrón Publish/Subscribe:** productores publican, consumidores se suscriben.
- **Event hub/backbone:** distribuye, registra y permite reanálisis de eventos.
- **Desacoplamiento alto:** mejora escalabilidad pero complica la coherencia del estado.

## 🔗 Connections
- [[Broker en arquitecturas Event Driven]]
{Aquí se agregan los links a otras notas relacionadas. Solamente ponga \[\[ Nombre de nota \]\] sin los "\"}
## 💡 Personal Insight (Opcional)
- {reflexiones personales sobre el concepto que desean capturar, ideas que quieran explorar después o potenciales usos}
## 🧾 Recursos (Opcional)
- {cualquier link a material donde se hable del concepto que quieran recordar}
---
Fecha de creación: 2025-08-04 23:53
Fecha de Modificación: 2025-08-04 23:53
tags:
  - arquitectura
Topic:
---


---

## 📚 Idea/Concepto 

Es un sistema intermedio que recibe y distribuye los eventos entre los diferentes componentes. Gracias a él, los productores pueden enviar eventos sin saber quién los recibirá, y los consumidores pueden suscribirse para reaccionar a ellos. Esto permite una comunicación asíncrona y más ordenada, haciendo que el sistema sea más flexible y fácil de escalar. Además, en esta variante con broker, los eventos se distribuyen mediante el patrón Publish/Subscribe, donde el broker realiza un broadcast de los mensajes a todos los consumidores suscritos. Este modelo mejora la integración y el desacoplamiento entre servicios. Existen distintos tipos de brokers, entre ellos los light brokers, como RabbitMQ o ActiveMQ, que son ampliamente utilizados por su ligereza y eficiencia en sistemas distribuido

## 📌 Puntos Claves (Opcional)
- **Broker de eventos:** intermediario que recibe y distribuye eventos.
- **Comunicación asíncrona:** productores y consumidores independientes.
- **Patrón Publish/Subscribe:** el broker hace broadcast a suscriptores.
- **Tipos comunes:** light brokers como RabbitMQ y ActiveMQ.

## 🔗 Connections
- [[ Scrum]]
{Aquí se agregan los links a otras notas relacionadas. Solamente ponga \[\[ Nombre de nota \]\] sin los "\"}
## 💡 Personal Insight (Opcional)
- {reflexiones personales sobre el concepto que desean capturar, ideas que quieran explorar después o potenciales usos}
## 🧾 Recursos (Opcional)
- {cualquier link a material donde se hable del concepto que quieran recordar}
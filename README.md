# 🍽️ El Huarique: Sistema de Reservas y Gestión de Mesas

> Un motor de reservas inteligente que optimiza la asignación de espacios en un restaurante mediante el uso de estructuras de datos dinámicas y lógica de colas de prioridad.

---

## 🎯 El Desafío
La gestión de un restaurante requiere una asignación dinámica que evite mesas vacías y tiempos de espera innecesarios.
* **Problema:** Coordinar el flujo de clientes con diferentes tamaños de grupo y la disponibilidad de mesas con capacidades variables.
* **Solución:** Implementación de un sistema que procesa las solicitudes en orden de llegada y busca el "mejor ajuste" (Best Fit) recorriendo la infraestructura física del local de forma eficiente.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Java (Lógica de estructuras y algoritmos).
* **Estilos:** CSS (Personalización de la interfaz de usuario).
* **Entorno:** POO (Programación Orientada a Objetos).

## 🧠 Estructuras de Datos Implementadas
El corazón de este proyecto es el uso estratégico de memoria dinámica:
* **Cola (Queue):** Gestión de reservas entrantes bajo el principio **FIFO** (First In, First Out). Los clientes son atendidos estrictamente por orden de llegada.
* **Lista Doblemente Enlazada:** Utilizada para la gestión de mesas. Permite un recorrido bidireccional eficiente para buscar mesas disponibles que coincidan con la capacidad requerida.
* **Lista Simple:** Implementada para el historial de clientes, permitiendo un registro ligero y secuencial de la actividad del restaurante.

## ✨ Características Técnicas
* ✅ **Asignación Inteligente:** El sistema valida la capacidad de la mesa vs. el número de comensales antes de permitir la reserva.
* ✅ **Control de Estados:** Bloqueo automático de mesas asignadas para evitar errores de sobreventa o duplicidad.
* ✅ **Persistencia de Historial:** Registro de la experiencia del cliente para consultas posteriores.
* ✅ **Gestión de Espera:** Las reservas permanecen en la cola de forma segura hasta que una mesa adecuada se libera.

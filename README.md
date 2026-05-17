<img width="563" height="298" alt="screenshot-1775444271894" src="https://github.com/user-attachments/assets/91297c6d-0ea2-4afb-be80-e991ec2a4822" />


#  Índice del Proyecto

- [1. Análisis de Requisitos](#1-análisis-de-requisitos)
  - [1.1 Necesidad del Negocio](#11-necesidad-del-negocio)
  - [1.2 Objetivo del Proyecto](#12-objetivo-del-proyecto)
- [2. Definición del Problema](#2-definición-del-problema)
  - [2.1 Datos de Entrada (Estado Actual)](#21-datos-de-entrada-estado-actual)
  - [2.2 Proceso de Análisis y Estrategia](#22-proceso-de-análisis-y-estrategia)
  - [2.3 Datos de Salida (Solución Propuesta)](#23-datos-de-salida-solución-propuesta)
- [3. Algoritmo Lógico del Sistema](#3-algoritmo-lógico-del-sistema)
  - [3.1 Estructura del Menú Principal](#31-estructura-del-menú-principal)
  - [3.2 Flujo de Opciones y Navegación](#32-flujo-de-opciones-y-navegación)
  - [3.3 Módulo de Agendamiento de Citas (Lógica de Validación)](#33-módulo-de-agendamiento-de-citas-lógica-de-validación)
---

## 1. Análisis de Requisitos
* **Necesidad:** El establecimiento actualmente presenta una baja visibilidad en el mercado debido a la falta de presencia digital. Los clientes se ven obligados a agendar citas por teléfono o esperar largas filas en el local, limitando las oportunidades de captar nuevos clientes.
* **Objetivo:** Desarrollar una página web informativa y funcional que permita aumentar la visibilidad del negocio en internet, mostrar el catálogo de servicios y facilitar el agendamiento de citas en línea para los usuarios.

# 2. Diseno del sistema 
*Estructura del software
El sistema sera modular y se dividira en tres partes:

*Modulo de cliente: Para ver servicios, precios y agendar citas.
*Modulo de administrador: Para que el barbero gestione la egenda y horarios.
*Modulo de notificaciones: Para enviar confirmaciones y recordatorios automaticos.

Interfaz (diseno UX\UI)
* Estetica: Estilo moderno y limpio, con colores que identifiquen a la barberia.
* Navegacion: Menu sencillo (Inicio, servicios, equipo) optimizado para celulares, con un boton destacado de "agendar cita".

   Base de datos
  Se usara una base de datos relacional con las siguientes tablas:
  * Clientes: Datos de contacto e historial.
  * Barberos: Nombres, especialidades y horarios.
  * Servicos: Tipos de corte, precios y duracion.
  * Citas: Registro de que cliente se atiende, con que barbero, la fecha y hora.
    Arquitectura
  * Frontend: Pantallas rapidas y faciles de usar para el usuario.
  * Backend: Logica que procesa las reservas y evita que se dupliquen citas a la misma hora.
  * Integracion: Conexion con mensajeria (como WhatsApp o coreo) para enviar los recordatorios de las citas.
 
  ---
# Finalidad del proyecto
 La finalidad del proyecto es desarrollar una pagina web para la barberia que permita aumentar su visibilidad en internet y facilitar el acceso a informacion relevante para los clientes.
 A traves de esta plataforma, se busca promocionar los servicios, mejorar la comunicacion con los usuarios y ofrecer opciones como el agendamiento de citas em linea.
 Con ello la barberia podra atraer a mas clientes, fortalecer su imagen profesional y mejorar su competividad en el mercado.
 ---

## 3. Definición del Problema
El negocio carece de presencia digital y de un sistema automatizado de reservas. Esto provoca dos problemas principales: la perdida de clientes potenciales que buscan barberias en internet y la desorganizacion de la agenda al gestionar las citas manualmente.

### Datos de Entrada
* Falta de presencia digital de la barbería.
* Bajo nivel de visibilidad en internet y redes.
* Información de servicios y precios no disponible en línea.
* Acceso limitado de los clientes a horarios disponibles y barberos del staff.

### Proceso
* Análisis de la situación actual y flujos de atención del local.
* Identificación de necesidades digitales (promoción, tarifas, captación de clientes).
* Evaluación del comportamiento de los usuarios al buscar servicios estéticos en su zona.
* Planteamiento de estrategias lógicas para el registro automatizado de turnos.

### Datos de Salida
* Identificación clara del problema: baja captación de clientes por falta de un canal digital.
* Propuesta de implementación de una plataforma web interactiva.
* Objetivo cumplido de automatizar las citas, optimizar tiempos de espera y mejorar la competitividad.

---
- # Propuesta de solucion
 Para resolver la baja visibilidad y captacion de clientes, se propone el desarrollo de una pagina web profesional para la barberia, que funcionara como canal digital de promocion y comunicacion.
La plataforma incluira los servicios (cortes, barba), precios, ubicacion, horarios y la integracion de un sistema de agendamiento de citas em linea.
Asimismo, se complementara con estrategias de marketing digital (SEO local y vinculacion con redes sociales como instagram o Tik Tok) para aumentar el alcance y atraer a mas usuarios interesados
Con esta solucion, la barberia mejorara su presencia en internet, generara mayor confianza y aumentara el numero de citas, contribuyendo a su crecimiento y competividad.

## 4. Algoritmo\Pseudocodigo Lógico del Sistema

1. Mostrar página de inicio con menú de bienvenida.
2. Mostrar menú con opciones:
   * **1. Ver Servicios:** Desplegar cortes de cabello, perfilado de barba, tintes y tratamientos faciales.
   * **2. Información del local:** Mostrar ubicación física, horarios de atención y barberos disponibles.
   * **3. Contacto:** Mostrar teléfono, enlaces a redes sociales y formulario.
   * **4. Agendar cita:** Iniciar módulo de reserva de turnos.
   * **5. Salir**
3. Esperar acción del usuario.

4. **Si** el usuario selecciona "Ver Servicios", **entonces**:
   * Mostrar lista de tratamientos estéticos masculinos y sus respectivos costos.
5. **Si** el usuario selecciona "Información del local", **entonces**:
   * Mostrar dirección exacta, horarios (Lunes a Sábado) y galería de barberos.
6. **Si** el usuario selecciona "Contacto", **entonces**:
   * Mostrar teléfono de soporte y correo electrónico.
7. **Si** el usuario selecciona "Agendar cita", **entonces**:
   * Mostrar formulario en pantalla.
   * Solicitar datos: Nombre del cliente, teléfono celular, fecha de la cita y hora solicitada.
   * Validar consistencia de los datos ingresados.
   * **Si los datos son correctos, entonces**:
     * Guardar la cita de manera interna en el sistema.
     * Mostrar un mensaje de confirmación en pantalla.
   * **Si no**:
     * Mostrar alerta de error y solicitar corrección de campos.
8. Preguntar si desea realizar otra acción en la página.
9. **Si** la respuesta es afirmativa, regresar al paso 2 (Menú principal).
10. **Si no**, finalizar la ejecución de la sesión.
    

file:///C:/Users/angel/Downloads/Documento%20sin%20t%C3%ADtulo.pdf

 

---

## 1. Análisis de Requisitos
* **Necesidad:** El establecimiento actualmente presenta una baja visibilidad en el mercado debido a la falta de presencia digital. Los clientes se ven obligados a agendar citas por teléfono o esperar largas filas en el local, limitando las oportunidades de captar nuevos clientes.
* **Objetivo:** Desarrollar una página web informativa y funcional que permita aumentar la visibilidad del negocio en internet, mostrar el catálogo de servicios y facilitar el agendamiento de citas en línea para los usuarios.

## 2. Definición del Problema
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

## 3. Algoritmo Lógico del Sistema

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

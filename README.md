## Documentación del Proyecto en GitHub 📂

Para cumplir con las buenas prácticas de gestión de proyectos y los requisitos de la actividad, se ha documentado el **caso de estudio de la empresa de distribución de alimentos** en este repositorio.

### Listado de Requerimientos (Caso de Estudio)
A continuación, se definen los requerimientos del sistema, divididos en funcionales (lo que el sistema debe hacer) y no funcionales (cómo debe ser el sistema).

* **Requerimientos Funcionales:**
    * **RF-01:** El sistema debe permitir que los usuarios se registren e inicien sesión utilizando sus cuentas de Gmail.
    * **RF-02:** El sistema debe permitir a los clientes seleccionar productos para agregarlos a un carro de compras.
    * **RF-03:** El sistema debe calcular automáticamente el costo del despacho a domicilio basado en el monto total de la compra y la distancia en kilómetros.
    * **RF-04:** El despacho debe ser gratuito (`$0`) para compras de un monto superior a $50,000 pesos, dentro de un radio de 20 km.
    * **RF-05:** Se debe aplicar una tarifa de `$150` por kilómetro recorrido para compras cuyo total esté entre $25,000 y $49,999.
    * **RF-06:** Se debe aplicar una tarifa de `$300` por kilómetro recorrido si el total de la compra es menor a $25,000.

* **Requerimientos No Funcionales:**
    * **RNF-01:** La aplicación debe ser compatible con los sistemas operativos móviles más comunes (Android/iOS).
    * **RNF-02:** La interfaz de usuario debe ser intuitiva y fácil de usar.
    * **RNF-03:** El sistema debe garantizar la seguridad y privacidad de los datos de los usuarios.
    * **RNF-04:** El cálculo del costo de despacho debe ser procesado y mostrado en menos de 2 segundos.

### Historias de Usuario
Se redactaron historias de usuario para describir las funcionalidades desde la perspectiva del cliente.

* **HU-1: Registro Simplificado**
    * **Como** un nuevo cliente, **quiero** registrarme usando mi cuenta de Gmail, **para** poder acceder a la aplicación de forma rápida.
    * **Criterios de Aceptación:** El usuario puede autenticarse a través del flujo de Google y, tras un inicio de sesión exitoso, es redirigido a la página principal de la aplicación.

* **HU-2: Cálculo Transparente de Despacho**
    * **Como** un cliente que finaliza su compra, **quiero** que el sistema calcule y muestre el costo de mi despacho de forma automática, **para** conocer el monto total a pagar antes de confirmar el pedido.
    * **Criterios de Aceptación:** El costo de despacho debe aparecer desglosado en el resumen de la compra y debe actualizarse correctamente según las reglas de negocio.

### Cronograma Inicial del Proyecto 🗓️
Se utilizó la herramienta **GitHub Projects** para elaborar un cronograma inicial que especifica la planificación detallada del proyecto.

* **Fase 1: Planificación y Análisis (1 Semana):** Definición detallada de requerimientos y diseño de la arquitectura.
* **Fase 2: Diseño de UI/UX (1 Semana):** Creación de wireframes y prototipos de la interfaz.
* **Fase 3: Desarrollo (4 Semanas):** Implementación de la autenticación, catálogo de productos, carro de compras y lógica de cálculo.
* **Fase 4: Pruebas (2 Semanas):** Pruebas unitarias, de integración y de aceptación de usuario (UAT).
* **Fase 5: Despliegue (1 Semana):** Publicación de la aplicación en las tiendas y cierre del proyecto.

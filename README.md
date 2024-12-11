# Documento de Visión del Proyecto: Libro de Registros para Hoteles y Residencias en Chile

## 1. Introducción

Este documento presenta la visión y el alcance del proyecto para desarrollar un sistema de gestión de registros destinado a hoteles y residencias ubicados en diversas ciudades de Chile. El sistema permitirá a los usuarios administrar reservas, visitas y datos de hospedaje de manera eficiente y segura.

## 2. Objetivos del Proyecto

- **Facilitar la gestión de reservas y visitas** para hoteles y residencias.
- **Proporcionar una plataforma centralizada** que permita a los administradores, hospedajes y visitantes interactuar de manera efectiva.
- **Implementar un sistema de autenticación seguro** utilizando correo electrónico y Google.
- **Ofrecer una interfaz de usuario intuitiva y elegante**, basada en tecnologías web modernas.

## 3. Alcance del Proyecto

El sistema incluirá las siguientes funcionalidades:

- **Autenticación de Usuarios:**

  - Registro y login mediante correo electrónico y Google.
  - Recuperación de contraseña.
- **Gestión de Visitas y Reservas:**

  - Formularios para agregar, editar y firmar visitas (con validación mediante Gmail).
  - Creación y edición de reservas.
- **Dashboards Personalizados:**

  - **Admin:** Visualización y gestión de usuarios, registros y reservas.
  - **Hospedaje:** Registro y filtro de visitas (vigentes, antiguas), gestión de reservas con CRUD, modificación de información del hospedaje.
  - **Visita:** Visualización y filtrado de registros, creación de reservas.

## 4. Roles de Usuario

- **Administrador (Admin):** Tiene acceso completo al sistema, incluyendo la gestión de usuarios, hospedajes y visitas.
- **Hospedaje:** Gestiona las visitas y reservas de su establecimiento, además de modificar la información del mismo.
- **Visita:** Puede ver sus registros, filtrar información y realizar reservas.

## 5. Tecnologías a Utilizar

- **Backend:** Node.js con Express y Nodemon.
- **Frontend:** HTML, CSS con metodología BEM, JavaScript, Bootstrap y FontAwesome.
- **Base de Datos:** Firebase.

## 6. Historias de Usuario

A continuación, se presentan las historias de usuario clave para el desarrollo del sistema:

### 6.1. Autenticación de Usuarios

- **Registro de Usuario:**

  - *Como* visitante,
  - *quiero* registrarme en la plataforma utilizando mi correo electrónico o cuenta de Google,
  - *para* acceder a las funcionalidades del sistema.
- **Inicio de Sesión:**

  - *Como* usuario registrado,
  - *quiero* iniciar sesión con mi correo electrónico o cuenta de Google,
  - *para* acceder a mi perfil y funcionalidades asociadas.
- **Recuperación de Contraseña:**

  - *Como* usuario,
  - *quiero* recuperar mi contraseña en caso de olvido,
  - *para* restablecer el acceso a mi cuenta.

### 6.2. Gestión de Visitas y Reservas

- **Agregar Visita:**

  - *Como* hospedaje,
  - *quiero* registrar una nueva visita,
  - *para* llevar un control de los visitantes en mi establecimiento.
- **Editar Visita:**

  - *Como* hospedaje,
  - *quiero* modificar los detalles de una visita existente,
  - *para* mantener la información actualizada.
- **Firma de Visita:**

  - *Como* visita,
  - *quiero* firmar mi registro de visita utilizando mi cuenta de Gmail,
  - *para* validar mi presencia en el hospedaje.
- **Crear Reserva:**

  - *Como* visita,
  - *quiero* realizar una reserva en un hospedaje,
  - *para* asegurar mi estadía en las fechas deseadas.
- **Editar Reserva:**

  - *Como* visita,
  - *quiero* modificar los detalles de mi reserva,
  - *para* ajustar mi estadía según mis necesidades.

### 6.3. Dashboards Personalizados

- **Dashboard de Admin:**

  - *Como* administrador,
  - *quiero* ver y gestionar todos los usuarios, hospedajes y visitas,
  - *para* mantener el control y supervisión del sistema.
- **Dashboard de Hospedaje:**

  - *Como* hospedaje,
  - *quiero* ver y filtrar las visitas (vigentes, antiguas) y gestionar reservas,
  - *para* administrar eficientemente mi establecimiento.
- **Dashboard de Visita:**

  - *Como* visita,
  - *quiero* ver mis registros y reservas, y realizar nuevas reservas,
  - *para* gestionar mis estadías en los hospedajes.

## 7. Supuestos y Dependencias

- **Supuestos:**

  - Los usuarios cuentan con acceso a internet y dispositivos compatibles con navegadores modernos.
  - Los hospedajes están dispuestos a digitalizar sus procesos de registro y reserva.
- **Dependencias:**

  - Integración con servicios de autenticación de Google.
  - Disponibilidad y confiabilidad de los servicios de Firebase.

## 8. Criterios de Aceptación

- El sistema debe permitir el registro e inicio de sesión de usuarios mediante correo electrónico y Google.
- Los hospedajes deben poder gestionar visitas y reservas de manera intuitiva.
- Las visitas deben poder realizar y gestionar sus reservas fácilmente.
- La interfaz debe ser responsive y cumplir con los estándares de usabilidad y accesibilidad.

## 9. Exclusiones

- No se incluirá en esta fase la implementación de un sistema de pagos en línea.
- No se considerará la integración con sistemas externos de gestión hotelera.

## 10. Riesgos Identificados

- **Riesgo:** Posibles dificultades en la integración con servicios de autenticación de Google.

  - *Mitigación:* Contar con documentación actualizada y soporte técnico de Google.
- **Riesgo:** Dependencia de la disponibilidad de los servicios de Firebase.

  - *Mitigación:* Implementar mecanismos de respaldo y recuperación de datos.

## 11. Planificación de Sprints

El desarrollo se estructurará en sprints semanales, priorizando las funcionalidades esenciales para el MVP y ajustándose según el feedback recibido.

## 12. Aprobación

Este documento ha sido revisado y aprobado por los interesados clave del proyecto, sirviendo como guía para el desarrollo y asegurando el cumplimiento de los objetivos establecidos.

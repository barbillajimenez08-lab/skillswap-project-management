
# Alcance del proyecto — SkillSwap AI

## 1. Descripción general

SkillSwap AI será una plataforma web Fullstack de intercambio de habilidades y mentorías.

El sistema permitirá que los usuarios publiquen conocimientos, busquen mentores, realicen reservas y administren créditos virtuales.

## 2. Usuarios y roles

### Usuario
- Registrarse e iniciar sesión.
- Crear y editar su perfil.
- Buscar habilidades.
- Solicitar mentorías.
- Administrar sus reservas.
- Consultar su billetera.

### Mentor
- Publicar habilidades.
- Administrar sus publicaciones.
- Gestionar solicitudes de reserva.
- Confirmar o rechazar sesiones.
- Consultar su historial.

Un usuario podrá desempeñarse como aprendiz y mentor.

### Administrador
- Administrar usuarios.
- Supervisar publicaciones.
- Gestionar incidencias.
- Consultar información general.
- Supervisar operaciones de la plataforma.

## 3. Funcionalidades del sistema

### Módulo 1 — Autenticación
- Registro.
- Inicio de sesión.
- Verificación por correo.
- Recuperación de contraseña.
- Cierre de sesión.
- Autorización por roles.

### Módulo 2 — Perfiles
- Datos personales.
- Fotografía de perfil.
- Biografía.
- Habilidades ofrecidas.
- Habilidades que desea aprender.

### Módulo 3 — Marketplace
- Crear publicaciones.
- Editar publicaciones.
- Eliminar publicaciones.
- Listar habilidades.
- Buscar y filtrar.
- Consultar perfiles de mentores.

### Módulo 4 — Reservas
- Solicitar sesiones.
- Confirmar solicitudes.
- Rechazar solicitudes.
- Finalizar sesiones.
- Consultar historial.

Estados:
- Pendiente.
- Confirmada.
- Finalizada.
- Cancelada.

### Módulo 5 — Créditos virtuales
- Consultar saldo.
- Comprar paquetes.
- Consultar movimientos.
- Registrar débitos y créditos.
- Gestionar operaciones de mentorías.

### Módulo 6 — Inteligencia artificial
- Analizar necesidades de aprendizaje.
- Recomendar mentores.
- Generar sugerencias personalizadas.
- Crear itinerarios de aprendizaje.

### Módulo 7 — Integraciones
- Nodemailer para correos.
- Cloudinary para imágenes.
- MercadoPago para pagos.
- API LLM para inteligencia artificial.

### Módulo 8 — Administración
- Gestión de usuarios.
- Gestión de publicaciones.
- Supervisión de reservas.
- Supervisión de transacciones.

## 4. Alcance de la primera versión (MVP)

La primera versión deberá contar con:

- Autenticación funcional.
- Perfiles de usuarios.
- Publicaciones de habilidades.
- Búsqueda y filtros.
- Reservas.
- Billetera de créditos.
- Compra de créditos.
- Recomendador inteligente.
- Panel administrativo.

## 5. Funcionalidades futuras

Se consideran mejoras posteriores:

- Videollamadas.
- Chat en tiempo real.
- Suscripciones.
- Certificados.
- Aplicación móvil.
- Sistema avanzado de reputación.

## 6. Restricciones

- El desarrollo será individual.
- El tiempo de planificación institucional es de cuatro semanas.
- Se utilizará el stack tecnológico establecido por RollingCode.
- El frontend y backend tendrán repositorios independientes.
- Las integraciones deberán utilizar credenciales protegidas mediante variables de entorno.

## 7. Criterio de finalización

Una funcionalidad se considerará terminada cuando:

1. Su implementación esté completa.
2. Se hayan realizado pruebas.
3. No presente errores conocidos que impidan su funcionamiento.
4. Su documentación esté actualizada.
5. Sus cambios estén registrados en GitHub.

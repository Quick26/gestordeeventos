faseIV

GestorDeEventos App

Resumen Ejecutivo

Descripción
GestorDeEventos es una aplicación móvil que ayuda a los usuarios a gestionar eventos de manera sencilla. Permite crear, organizar y compartir eventos, mejorando la experiencia tanto para los organizadores como para los asistentes.

Problema Identificado
La planificación y gestión de eventos puede ser complicada debido a la falta de herramientas centralizadas y accesibles, lo que dificulta la promoción y el monitoreo de los eventos.

Solución
GestorDeEventos proporciona una plataforma intuitiva donde los usuarios pueden:

Crear eventos personalizados.
Compartir eventos con contactos y en redes sociales.
Monitorear asistencia y participación en tiempo real.
Arquitectura
Frontend: Flutter (compatible con Android e iOS).
Backend: Node.js con Express.
Base de datos: PostgreSQL.
Despliegue: Heroku para el backend.
Tabla de Contenidos

Descripción
Problema Identificado
Solución
Arquitectura
Requerimientos
Instalación
Configuración
Uso
Contribución
Roadmap
Producto Final
Requerimientos

Tecnologías Utilizadas
Framework de Frontend: Flutter.
Backend: Node.js con Express.
Base de Datos: PostgreSQL.
Paquetes Adicionales
dotenv: Gestión de variables de entorno.
jsonwebtoken: Implementación de autenticación.
nodemailer: Notificaciones por correo electrónico.
Versiones Necesarias
Flutter SDK: 3.x.
Node.js: 16 o superior.
PostgreSQL: 13 o superior.
Instalación

Ambiente de Desarrollo
Clona este repositorio:
git clone https://github.com/Quick26/gestordeeventos.git  
Backend:
Navega al directorio del backend:
cd backend  
Instala las dependencias necesarias:
npm install  
Configura el archivo .env (ver la sección Configuración).
Inicia el servidor:
npm start  
Frontend:
Navega al directorio del frontend:
cd frontend  
Instala las dependencias necesarias:
flutter pub get  
Ejecuta la aplicación:
flutter run  
Despliegue en Producción
Despliegue del Backend:
Realiza el despliegue en Heroku:
git push heroku main  
Publicación del Frontend:
Sube el frontend a Google Play Store o Apple App Store (opcional).
Configuración

Variables de Entorno
Crea un archivo .env en el directorio del backend con el siguiente contenido:

DATABASE_URL=postgres://admin:admin123@localhost:5432/eventosdb  
JWT_SECRET=clave_secreta  
SMTP_HOST=smtp.mailtrap.io  
SMTP_USER=admin@mailtrap.io  
SMTP_PASS=contraseña123  
Uso

Manual para Usuarios Finales
Registro: Crea una cuenta con tu correo electrónico.
Creación de Eventos: Ingresa detalles como nombre, fecha y lugar del evento.
Compartir Eventos: Comparte el enlace generado con tus contactos o en redes sociales.
Manual para Administradores
Gestión de Eventos: Accede al panel administrativo para visualizar y editar eventos.
Reportes: Genera reportes de asistencia y participación de los usuarios.
Contribución

Clona este repositorio:
git clone https://github.com/Quick26/gestordeeventos.git  
Crea un branch para tus cambios:
git checkout -b feature/nueva-funcionalidad  
Haz tus cambios y realiza un commit:
git add .  
git commit -m "Descripción de los cambios"  
Envía un pull request:
Abre un pull request en GitHub para revisión.
Roadmap

 Notificaciones Push: Implementar notificaciones en tiempo real.
 Sistema de Calificación: Permitir a los asistentes calificar eventos.
 Soporte Multilingüe: Agregar soporte para varios idiomas.
Producto Final

Video de Demostración
Enlace al video

Acceso al Producto
Despliegue en la nube: https://gestordeeventos.heroku.com , https://app.flutterflow.io/project/gestion-de-eventos-tt3185?tab=uiBuilder&page=InicioDeSesion 
Descarga: Enlace al archivo WAR/JAR

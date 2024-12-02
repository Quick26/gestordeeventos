GestorDeEventos App

Resumen Ejecutivo

Descripción
GestorDeEventos es una aplicación móvil que permite a los usuarios gestionar eventos de manera sencilla y eficiente. La aplicación está diseñada para ser intuitiva, brindando herramientas clave para crear, organizar y compartir eventos, además de monitorizar asistencia y participación en tiempo real.

Problema Identificado
La gestión de eventos muchas veces resulta complicada por la falta de plataformas centralizadas y fáciles de usar. Esto genera dificultades al momento de planificar, promocionar y hacer seguimiento a los eventos.

Solución
GestorDeEventos ofrece una solución integral que incluye:

Creación de eventos personalizados con detalles específicos.
Compartir eventos fácilmente mediante enlaces o redes sociales.
Seguimiento en tiempo real de asistencia y participación de los usuarios.
Arquitectura
Frontend: Desarrollado con Flutter, asegurando compatibilidad con dispositivos Android e iOS.
Backend: Implementado con Node.js y Express para manejar solicitudes y la lógica del negocio.
Base de datos: PostgreSQL como sistema de almacenamiento de datos.
Despliegue: Utilizando Heroku para alojar el backend y Firebase Hosting para el frontend.
Tabla de Contenidos

Resumen Ejecutivo
Requerimientos
Instalación
Configuración
Uso
Contribución
Roadmap
Producto Final
Requerimientos

Tecnologías Utilizadas
Frontend: Flutter.
Backend: Node.js con Express.
Base de datos: PostgreSQL.
Paquetes Adicionales
dotenv: Para la gestión de variables de entorno.
jsonwebtoken: Para la autenticación basada en tokens.
nodemailer: Para el envío de notificaciones por correo electrónico.
Versiones Necesarias
Flutter SDK: 3.x o superior.
Node.js: 16 o superior.
PostgreSQL: 13 o superior.
Instalación

Configuración del Ambiente de Desarrollo
Clonar el Repositorio

Primero, clona este repositorio en tu máquina local:

git clone https://github.com/Quick26/gestordeeventos.git  
Backend

Navega al directorio del backend:
cd backend  
Instala las dependencias necesarias:
npm install  
Configura las variables de entorno (ver sección Configuración).
Inicia el servidor:
npm start  
Frontend

Navega al directorio del frontend:
cd frontend  
Instala las dependencias necesarias:
flutter pub get  
Ejecuta la aplicación:
flutter run  
Despliegue en Producción
Backend

Configura el entorno de producción en Heroku:
git push heroku main  
Frontend

Publica la aplicación en Google Play Store o Apple App Store (opcional).
Configuración

Variables de Entorno
Crea un archivo .env en el directorio del backend con el siguiente contenido:

DATABASE_URL=postgres://admin:admin123@localhost:5432/eventosdb  
JWT_SECRET=clave_secreta_super_segura  
SMTP_HOST=smtp.mailtrap.io  
SMTP_USER=usuario@mailtrap.io  
SMTP_PASS=contraseña123  
Uso

Manual para Usuarios Finales
Registro: Crea una cuenta ingresando tu correo electrónico.
Creación de Eventos: Proporciona detalles como el nombre, fecha, ubicación y descripción del evento.
Compartir Eventos: Genera un enlace que puedes compartir con tus contactos o en redes sociales.
Manual para Administradores
Gestión de Eventos: Administra los eventos creados por los usuarios desde el panel de control.
Reportes: Genera reportes detallados sobre la participación de los usuarios y el desempeño de los eventos.
Contribución

Pasos para Contribuir
Clona este repositorio:
git clone https://github.com/Quick26/gestordeeventos.git  
Crea un nuevo branch para tus cambios:
git checkout -b feature/nueva-funcionalidad  
Realiza tus cambios y realiza un commit:
git add .  
git commit -m "Descripción de los cambios realizados"  
Envía un pull request:
Abre un pull request en GitHub para revisión.
Roadmap

Funcionalidades Futuras
Notificaciones Push: Envío de notificaciones en tiempo real para recordar eventos.
Sistema de Calificación: Permitir a los asistentes calificar los eventos.
Soporte Multilingüe: Implementar soporte para varios idiomas.
Sincronización de Calendarios: Integración con Google Calendar y Outlook.
Producto Final

Video de Demostración
Ver el video aquí

Acceso al Producto
Despliegue en la nube: https://gestordeeventos.heroku.com, https://gestion-de-eventos-tt3185.flutterflow.app/
Descarga del Producto: WAR/JAR para descarga

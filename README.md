# BreakBuddy

Aplicación móvil Android desarrollada en equipo para fomentar pausas activas, interacción social y bienestar dentro de organizaciones.

La aplicación permite a los usuarios autenticarse, gestionar su perfil, participar en grupos, realizar check-ins y actividades, comunicarse mediante chat y recibir notificaciones.

## Funcionalidades principales

- Registro e inicio de sesión.
- Autenticación con Google.
- Gestión de perfil e intereses.
- Creación, unión y administración de grupos.
- Chat entre integrantes.
- Check-ins y actividades.
- Misiones y dinámicas de participación.
- Notificaciones push.
- Gestión de organizaciones y usuarios.
- Persistencia y sincronización de datos mediante Firebase.

## Tecnologías

- Kotlin
- Android SDK
- AndroidX
- ViewModel y LiveData
- Jetpack Navigation
- View Binding
- Firebase Authentication
- Cloud Firestore
- Firebase Cloud Messaging
- Google Sign-In
- Gradle

## Arquitectura

El proyecto separa la lógica de acceso a datos mediante repositorios para usuarios, grupos y organizaciones, mientras que las pantallas utilizan ViewModels y componentes de AndroidX para gestionar el estado y la navegación.

Firebase se utiliza como backend para autenticación, persistencia de información y notificaciones.

## Ejecución

### Requisitos

- Android Studio
- JDK 11
- Android SDK 35
- Dispositivo o emulador con Android 7.0 (API 24) o superior

### Configuración

1. Clonar el repositorio.

2. Abrir el proyecto en Android Studio.

3. Configurar un proyecto de Firebase compatible con la aplicación.

4. Agregar el archivo:

   `app/google-services.json`

5. Sincronizar las dependencias de Gradle.

6. Ejecutar la aplicación desde Android Studio o mediante:

```bash
./gradlew assembleDebug

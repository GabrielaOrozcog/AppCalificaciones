## Cómo probar la aplicación

### Opción 1 — Instalar el APK directamente (recomendado para probar rápido)

1. Descarga `AppCalificaciones.apk` de este repositorio a tu teléfono Android.
2. Ve a **Ajustes > Seguridad** (o Ajustes > Apps) y habilita **"Instalar apps de orígenes desconocidos"** para tu navegador o gestor de archivos.
3. Abre el archivo APK descargado y toca **Instalar**.
4. Abre la app **AppCalificaciones** desde tu pantalla de inicio.
5. Regístrate con un usuario nuevo desde la pantalla de registro, o usa las credenciales de prueba de la sección de abajo.

### Opción 2 — Abrir el proyecto fuente en Kodular

1. Entra a [kodular.io/creator](https://www.kodular.io/creator/) e inicia sesión (puedes crear una cuenta gratuita).
2. Ve a **Projects > Import project (.aia) from my computer**.
3. Selecciona el archivo `AppCalificaciones.aia` de este repositorio.
4. El proyecto se abrirá con todas las pantallas y bloques ya armados.
5. Para probarlo en vivo, instala la app **Kodular Companion** en tu teléfono y escanea el código QR que aparece en el editor, o compílalo desde **Build > App (.apk)** para generar tu propio instalable.

## Funcionalidades

- **Login:** compara usuario y contraseña contra una copia local de los usuarios (TinyDB), sincronizada desde Supabase.
- **Registro:** crea un nuevo usuario directamente en la tabla `usuarios` de Supabase.
- **Recordatorio de contraseña por email:** busca el usuario por correo en Supabase y reenvía sus credenciales por correo usando EmailJS.
- **CRUD de usuarios y calificaciones:** crear, consultar, actualizar y eliminar registros contra la API REST de Supabase.
- **Reportes parametrizados:**
  - Usuarios: por nombre y por dominio de email.
  - Calificaciones: por estudiante y por asignatura.
- **Sensores:** agitar el teléfono limpia el formulario activo; el sensor de ubicación se activa en la pantalla de calificaciones.

## Credenciales de prueba

- Usuario: `admin_gabriela`
- Contraseña: `1234`

## Video de sustentación

https://youtu.be/E5BCOBWDX4Y

## Autor

Gabriela Orozco — [gorozcog@unicartagena.edu.co]

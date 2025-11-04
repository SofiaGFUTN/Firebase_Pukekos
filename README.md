# Firebase_Pukekos
Firebase Web: Registro de Signos Zodiacales
Estudiantes:
SOFÍA GUTIÉRREZ FLORES
JOSE PABLO LUNA VARGAS
DOUGLAS GUEVARA VARGAS
AHIAN QUESADA GUADAMUZ

Características principales:
Módulo de usuarios
- Registro de usuarios con *correo y contraseña*.
- Almacenamiento de:
  - idemp → UID del usuario autenticado.
  - usuario, `email`
  - createdAt → fecha de creación (timestamp del servidor).
  - ultAcceso → fecha del último inicio de sesión.
- Actualización automática de ultAcceso cada vez que el usuario inicia sesión.
- Cierre automático de sesión tras 3 minutos de inactividad.

Módulo de signos zodiacales
- Permite agregar un signo con:
  - Posición (1–12)
  - Nombre del signo
  - Rango de fechas
  - Elemento (Fuego, Tierra, Aire o Agua)
  - Astro celeste
  - Piedra preciosa
  - Imagen del signo (almacenada en Storage)
- Visualización de todos los signos en forma de tarjetas dinámicas.
- Cada tarjeta permite ingresar a una página para editar o actualizar el signo.
- Integración con reglas de seguridad que validan tipo de datos y restringen acceso a usuarios autenticados.

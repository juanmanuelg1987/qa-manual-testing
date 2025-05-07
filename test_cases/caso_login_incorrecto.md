## Caso de prueba: Login con credenciales inválidas

**ID del caso de prueba:** TC002
**Módulo:** Login
**Prioridad:** Alta
**Descripción:** Verificar que el sistema muestre un mensaje de error adecuado al intentar iniciar sesión con credenciales incorrectas.

**Pasos para reproducir:**
1. Navegar a la página de login.
2. Ingresar usuario inválido: `usuario_incorrecto@ejemplo.com`
3. Ingresar contraseña inválida: `contrasena_incorrecta`
4. Hacer clic en el botón "Iniciar sesión".

**Resultado esperado:**
El sistema debe mostrar el mensaje de error: "Nombre de usuario o contraseña incorrectos." y el usuario debe permanecer en la página de inicio de sesión.

**Resultado actual:**
El sistema mostró el mensaje: "Nombre de usuario o contraseña incorrectos." y el usuario permaneció en la página de inicio de sesión.

**Estado:** Aprobado
## Casos de Prueba: Flujo de Registro de Usuario

| ID | Caso de Prueba | Paso a Paso | Resultado Esperado | Estado |
|----|----------------|-------------|---------------------|--------|
| CP-01 | Registro exitoso con datos válidos | 1. Ingresar a gocuotas.com<br>2. Click en "Ingresar"<br>3. Click en "Registrate"<br>4. Completar formulario válido<br>5. Click en "Crear cuenta" | Usuario es redirigido al dashboard o recibe un mensaje de éxito | 🟡 Por testear |
| CP-02 | Registro con email inválido | Igual a CP-01 pero ingresando `email@invalido` | Se muestra mensaje de error: "Email inválido" | 🟡 Por testear |
| CP-03 | Registro con contraseña débil | Contraseña tipo "1234" | Mensaje: "La contraseña debe tener mínimo 8 caracteres..." | 🟡 Por testear |
| CP-04 | Registro con campos vacíos | Click en "Crear cuenta" sin llenar datos | Validaciones visibles en cada campo obligatorio | 🟡 Por testear |
| CP-05 | Registro con email ya registrado | Usar email existente | Mensaje de error "Email ya en uso" o similar | 🟡 Por testear |

🛠️ Herramientas sugeridas para estas pruebas

DevTools (F12) para inspeccionar errores de red, consola, formularios.
Lighthouse para auditar accesibilidad y performance.
Brave navegador
Postman (APIs de backend).QUEDA PENDIENTE POR EL MOMETO.
BugMagnet (extensión Chrome) para pruebas de valores edge en formularios.

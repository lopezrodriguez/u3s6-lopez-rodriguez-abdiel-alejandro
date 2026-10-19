<!-- # : título principal del README (lo primero que se ve en GitHub) -->
# Proyecto Django — Lopez Rodriguez Abdiel Alejandro

<!-- ## : subtítulo de la sección con el enlace a producción -->
## Demo en vivo (produccion)
<!-- la URL pública de tu Web Service u3s6-… en Render -->
https://u3s6-lopez-rodriguez-abdiel-alejandro.onrender.com

<!-- ## : subtítulo con lo que se hizo esta semana -->
## Semana 6 — Autenticacion, sesiones y seguridad
<!-- primera línea de la descripción de la práctica -->
Registro/login/logout propios; cada usuario ve y edita solo
<!-- segunda línea de la descripción de la práctica -->
sus propios servicios (probado con usuario_a y usuario_b).

<!-- ## : subtítulo de la sección con la prueba de aislamiento -->
## Prueba de aislamiento
<!-- reemplaza el texto entre corchetes por la descripción de tu prueba -->
Se crearon dos cuentas de prueba (`usuario_a` y `usuario_b`) y se registraron servicios distintos en cada una. Al iniciar sesión con `usuario_b`, la lista de servicios solo mostró sus propios registros. Posteriormente, desde la cuenta de `usuario_b` se intentó acceder manualmente a la URL de edición de un servicio perteneciente a `usuario_a` (`/servicios/1/editar/`), obteniendo como resultado una respuesta 404 que confirma el correcto aislamiento de los datos. 
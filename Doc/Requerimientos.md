# Requerimientos del sistema

## Requerimientos funcionales

RF1. La aplicación permitirá categorizar el estatus de solicitudes:
   - Pendientes con proceso 
   - Pendientes sin proceso
   - Denegadas 
   - Completadas 

RF2. Será necesario que el solicitante ingrese datos esenciales para el llenado del formulario, tales como (datos obligados):
   - Nombre
   - Apellido
   - Email
   - CURP
   - Sexo M ó F
   - Edad 
   - Domicilio
   - Número telefónico
   - Violacion de comportamiento civico
   - Descripcion del problema detallada 

RF3. Si el solicitante pasa la validaciond de datos y campos obligatorios, pasa al proceso de pago con tarjeta o PAyPal.

RF4. En el proceso de pago si es rechazado mas de 5 veces debe ser declarada como denegada, por otro lado se da la opcion de que sea en efectivo y lo mandara a otra pantalla para validar datos y fotografia de pago.

RF5. El administrador tendrá la opción de visualizar, crear, modificar y eliminar cuentas de usuario y detalles sospechosos, al igual que solicitudes denegadas por el despacho y un rembolsom, al igual que descripcion de porque fue denegada.

RF6. Datos de proceso de pago de forma externa (se le dara numero de referencia y una CLABE para hacer el pago):
   - Nombre
   - Apellido
   - Email para la copia de recibo
   - Número telefónico
   - Fotografia de pago

RF7. Como trabajadores, habrán diferentes roles:
   - Administrador
   - Empleado

RF8. El empleado(de despacho) deberá tener 1 rol:
   - En grupo(que es un conjunto de personas trabajando).
   - Individual (Solicitudes individuales, para el mas experimentado).

RF9. El administrador tendrá todas las funciones del sistema disponibles.

RF10. Para crear una cuenta, del solicitante debe ingresar datos;
   - Nombre
   - Apellido
   - Email
   - Sexo M ó F
   - Fecha de nacimiento
   - Número telefónico
   - se asigna un id automatico
   - Contraseña

RF11. Datos comunes se extraen y ponen en automatico en la solicitud, se validan con los de registro

RF12. Se da la opcion de que la doble verificacion, para todo usuario.

RF13. Los datos de registro seran autenticados con sus dispositivos que registro.

RF14. Cuando se concluya el formulario sera mandado en formato word al administrador y despues de la validacion al despacho para asigrnar el proceso.

RF15. Se vera una balanza de las personas del despacho que tengan solicitudes y cuando se vayan liberando se asiganra la solictud, es decir sera de manera horizontal.

RF16. Cuando la transaccion de pago sea recibida se validara y dara un dashbord al administrador.

RF17. Cuando se finalice cada solicitud se ira liberando carga y por ende seran notificadas al solicitante.

RF18. Se crea una notificacion para el solicitante, ya que se mandaran comentarios del proceso por parte del despacho.

## Requerimientos no funcionales

RNF1. La aplicación web deberá funcionar en los navegadores Edge y Chrome.

RNF2. La aplicación web debe ser capaz de operar adecuadamente con hasta 100 usuarios con sesiones concurrentes.

RNF3. Los datos modificados en la base de datos deben ser actualizados aproximadamente 5 segundos después de realizar alguna actualización.

RNF4. La aplicación web debe contar con manuales de usuario estructurados adecuadamente.

RNF5. El acceso a diferentes puntos de la aplicación podrá ser controlado por un administrador. (El administrador es quien podrá cambiar los roles de los trabajadores).

RNF6. La aplicación web debe poseer un diseño “Responsive” a fin de garantizar la adecuada visualización en múltiples computadores personales, dispositivos tableta y teléfonos inteligentes.

RNF7. La aplicación web tendrá un archivo de "respaldo". Dicho archivo contendrá todas las ventas realizadas en la plataforma.

RNF8. La aplicación web debe funcionar en cualquiera de los siguientes sistemas operativos:
   - Windows.
   - iOS.
   - Linux.  
   - Android. 

RNF9. La plataforma contará con una documentación que permita la fácil escalabilidad de la aplicación.

RNF10. Los datos personales de los consumidores (nombre completo, email, contraseña) serán encriptados con ayuda del gestor de base de datos MySQL. 

RNF11. La aplicación web tendrá un control de excepciones, es decir, una validación de la información.

RNF12. El servidor deberá estar encendido 24 horas al día, 7 días a la semana, los mantenimientos serán programados con anticipación mínima de una semana y únicamente podrán efectuarse en el horario de 00:00 - 9:00 hrs.
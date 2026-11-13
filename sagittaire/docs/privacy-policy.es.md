# Política de privacidad

*Versión 3 · Vigente desde el 13 de noviembre de 2026*

*Esta es una traducción que se ofrece solo para tu comodidad; únicamente las versiones en francés y en inglés hacen fe y, si hay cualquier diferencia, prevalecen sobre esta.*

Esta política explica qué información trata la aplicación sagitt·AI·re (la «App»), dónde se guarda, cuándo sale de tu dispositivo y qué puedes hacer al respecto. Forma parte de las condiciones de uso. «Desarrollador» significa el desarrollador de sagitt·AI·re.

## 1. En resumen

El Desarrollador no recopila nada. La App no tiene cuenta, ni publicidad, ni analítica, ni seguimiento, y no envía nada al Desarrollador. Tus registros se quedan en tu dispositivo. Una foto de la diana solo sale de tu dispositivo cuando eliges que un servicio de inteligencia artificial («IA») puntúe una tanda, y en ese caso solo se envía a ese servicio.

## 2. Qué conserva la App en tu dispositivo

Para funcionar, la App conserva lo siguiente en su almacenamiento privado en tu dispositivo:

- tus arcos (nombre, tipo, ajustes y la descripción de tus flechas) y los lugares donde tiras, tal como los nombras;
- tus sesiones: fecha, lugar, arco, distancia, diana, tandas, flechas, puntuaciones, y la foto de cada tanda con una pequeña vista previa;
- tus ajustes, incluidos tu método de puntuación, los servicios de IA que configuras, sus direcciones y modelos, tu apariencia y tu arquero en el modo juego, y la fecha en que aceptaste las condiciones de uso;
- tus claves de API, cifradas con una clave guardada en el hardware seguro del dispositivo (Android Keystore).

Otras aplicaciones no pueden leer esta información, y las fotos no aparecen en tu galería. La App desactiva la copia de seguridad automática en la nube de Android y la transferencia de dispositivo a dispositivo, por lo que nada de esto se copia automáticamente fuera de tu dispositivo.

## 3. Cuándo sale información de tu dispositivo

**Puntuación con tu propia clave de API.** Cuando se puntúa una tanda, la App envía, mediante una conexión cifrada (HTTPS) y solo al servicio de IA que elegiste, a la dirección guardada con su clave:

- la foto de la tanda, sin sus datos ocultos (ubicación, modelo del dispositivo, fecha) y, salvo que desactives esta opción, recortada a la diana;
- la configuración que el servicio necesita para puntuarla: la diana y las dianas colocadas en el parapeto, el número de flechas, la regla de puntuación, la descripción de tus flechas y el idioma de sus notas;
- tu clave de API, que identifica tu cuenta en ese servicio.

Tu nombre, tus lugares, tu historial, tus puntuaciones y los datos de tu dispositivo nunca se envían. Los datos técnicos sobre el dispositivo que las aplicaciones suelen enviar se sustituyen por «unknown» (desconocido). Como cualquier servicio de internet, el servicio de IA puede ver tu dirección de red (IP).

**Compartir con tu app de IA.** La App prepara la foto y un prompt, y tú eliges la app con la que compartirlos mediante el menú para compartir de Android. Lo que ocurra después queda entre tú y esa app.

**Puntuación manual.** Nada sale de tu dispositivo.

**Compartir una sesión.** Cuando tocas Compartir en una sesión, la App prepara un resumen (fecha, arco, lugar, tirada, puntuaciones y, si lo eliges, una imagen de la hoja de puntuación), y tú eliges la app con la que compartirlo. Las fotos de tus tandas nunca se incluyen.

**Informar de un problema de puntuación.** Cuando tocas Informar de un problema de puntuación en una tanda, la App redacta un correo sobre esa tanda (diana, distancia, regla, modelo de IA, y cada flecha tal como la puntuó la IA y como está ahora) y, si lo marcas, adjunta la copia de la foto que se envía al servicio de IA. Tu app de correo se abre sin destinatario: tú eliges a quién enviarlo, y no se envía nada hasta que lo envíes. Tus arcos, lugares y fechas no se incluyen.

**Exportaciones.** Cuando exportas tus registros, la App escribe un archivo en el lugar que elijas (por ejemplo, tu carpeta de descargas o una unidad en la nube). Las claves de API y las direcciones de los servicios nunca se incluyen en una exportación. Guarda el archivo en un lugar privado: cualquiera que tenga el archivo puede leer tus registros.

**Verificar una clave.** El botón «Comprobar clave» envía tu clave a su servicio para confirmar que funciona.

## 4. Servicios de IA

Cada servicio de IA que usas es una empresa independiente con sus propias condiciones y su propia política de privacidad, que determinan cómo usa, conserva y protege lo que recibe, incluido si puede usarlo para entrenar sus modelos, y en qué lugar del mundo lo trata, que puede estar fuera de Québec y de Canadá. Léelas antes de usar el servicio, y elige el servicio y la configuración de tu cuenta en él en consecuencia. El Desarrollador no tiene ningún control sobre estos servicios y no recibe nada de ellos.

## 5. Permisos

- **Cámara**, para fotografiar la diana. Android te lo pide la primera vez.
- **Internet**, para conectarse con el servicio de IA que elegiste. No se usa con la puntuación manual.

La App no pide permisos de ubicación, contactos, micrófono ni almacenamiento. Para importar una foto se usa el selector de fotos de Android, que solo da a la App la foto que eliges.

## 6. Cuánto tiempo se conserva la información

Tu información permanece en tu dispositivo hasta que la eliminas. Puedes eliminar una tanda o una sesión, eliminar fotos antiguas a tamaño completo (Ajustes → Almacenamiento y copia de seguridad → Liberar espacio), quitar una clave, o borrar todas las sesiones o todo (Ajustes → Almacenamiento y copia de seguridad → Borrar datos). Al desinstalar la App se elimina todo lo que conserva en tu dispositivo.

## 7. Tus opciones y derechos

Como el Desarrollador no tiene ninguna información sobre ti, todo lo que la App sabe de ti está en tu dispositivo y bajo tu control: puedes verlo en la App, obtener una copia con una exportación, corregirlo y eliminarlo, como se describe arriba. Para la información que haya recibido un servicio de IA, ejerce los derechos que te otorga su política de privacidad; según las leyes de Québec y de Canadá, y las leyes del lugar donde vives, puedes tener derechos de acceso, rectificación y supresión ante ese servicio.

## 8. Seguridad

La App protege tu información con el aislamiento de aplicaciones (sandbox) de Android, cifra tus claves de API, envía las solicitudes de puntuación solo mediante HTTPS, bloquea las conexiones sin cifrar y elimina los datos ocultos de las fotos antes de enviarlas. Ningún método es completamente seguro: protege tu dispositivo con un bloqueo de pantalla, crea una clave de API solo para la App con un límite de gasto, y elimínala en su servicio si pierdes tu dispositivo.

## 9. Menores

La App no está dirigida a menores de 14 años y no recopila información de nadie. Los servicios de IA fijan sus propias edades mínimas. Un padre, una madre o un tutor debería configurar cualquier servicio de IA que use un menor, o elegir la puntuación manual, que no envía nada.

## 10. Cambios en esta política

Si esta política cambia de forma sustancial, la nueva versión se mostrará en la App, con su fecha, y se te pedirá que vuelvas a aceptar las condiciones de uso antes de continuar. La versión vigente está siempre en la App (Ajustes → Información y aviso legal) y en el sitio web de sagitt·AI·re.

## 11. Preguntas

La App y su sitio web están hechos pro bono para Archery Canada y los gestiona el Desarrollador. Si tienes preguntas sobre esta política, abre una incidencia (issue) en github.com/ashencroft-hyperautomation/ashencroft-hyperautomation.github.io/issues. Las incidencias son públicas: no incluyas información personal, fotos ni claves de API.

## 12. Idioma

Esta política está redactada en francés y en inglés; ambas versiones hacen igualmente fe. *Cette politique est rédigée en français et en anglais; les deux versions font également foi.*

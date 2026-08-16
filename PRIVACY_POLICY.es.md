# Política de Privacidad de Wavely

**Fecha de entrada en vigor:** Agosto de 2026
**Desarrollador:** Kirutre
**Contacto:** contact.kirutre+sounds@gmail.com

## 1. Recopilación y uso de la Información
Wavely es desarrollada y mantenida por un desarrollador independiente (Kirutre). La extensión no recopila, almacena, transmite ni comparte ningún dato personal, historial de navegación o actividad del usuario. Todas las operaciones se realizan localmente en el dispositivo del usuario.

## 2. Almacenamiento Local y Retención de Datos
La extensión utiliza exclusivamente la `browser.storage.local / chrome.storage.local` API para guardar las configuraciones del usuario (tales como asignaciones de teclas personalizadas, preferencias de volumen y archivos de audio subidos codificados en Base64). Estos datos nunca salen del entorno local de su navegador y se eliminan automáticamente si desinstala la extensión.

## 3. Permisos Utilizados
* **Storage / Unlimited Storage:** utilizado únicamente para guardar sus configuraciones de sonido y triggers de teclas preferidos de forma local en su dispositivo sin restricciones de límite de almacenamiento.
* **Offscreen / Background Worker:** utilizado para gestionar la reproducción de audio y el procesamiento en segundo plano en cumplimiento con los estándares modernos para extensiones de navegador, sin afectar el rendimiento.
* **Content Scripts (`<all_urls>`):** utilizado estrictamente para detectar eventos de pulsación de teclas (keydown) en las pestañas activas para activar los sonidos. No se registra, supervisa ni transmite a ningún lugar ninguna tecla pulsada, entrada de texto ni contenido web.

## 4. Contenido Subido por el Usuario y Excención de Responsabilidad por Derechos de Autor
Wavely permite a los usuarios subir archivos de audio para uso personal.
* **Responsabilidad del Usuario:** los usuarios son los únicos responsables de garantizar que poseen el derecho legal o la licencia para utilizar cualquier archivo de audio subido a la extensión.
* **Infracción de Derechos de Autor:** como único desarrollador, yo (Kirutre) no respaldo, alojo ni asumo ninguna responsabilidad por el contenido de audio subido por el usuario que pueda violar los derechos de autor o las leyes de propiedad intelectual de terceros.

## 5. Limitación de Responsabilidad y Licencia
Wavely se distribuye bajo la **MIT License**. El software se proporciona "tal cual", sin garantía de ningún tipo, expresa o implícita. En ningún caso yo (el desarrollador) seré responsable de ninguna reclamación, daño u otra responsabildiad que surja del uso o mal uso de esta extensión.

## 6. Cambios a esta Política
Esta política de privacidad puede estar sujeta a actualizaciones según sea necesario. Cualquier cambio se publicará en este [repositorio/página]((https://github.com/Kirutre/wavely)) con la fecha de entrada en vigor actualizada.
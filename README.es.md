![Banner](/images/big_banner.png "Banner")

# 🎵 Wavely

[![Firefox Version](https://img.shields.io/amo/v/wavely?label=Firefox%20Add-ons&logo=firefoxbrowser&logoColor=white&color=FF7139)](https://addons.mozilla.org/es-ES/firefox/addon/wavely/)
[![Chrome Version](https://img.shields.io/chrome-web-store/v/hbbhbkidoemiahjkcgfbijpcjpfikaec?label=Chrome%20Web%20Store&logo=googlechrome&logoColor=white&color=4285F4)](https://chromewebstore.google.com/detail/wavely-kirutre/hbbhbkidoemiahjkcgfbijpcjpfikaec)
[![GitHub Release](https://img.shields.io/github/v/release/Kirutre/wavely?label=Última%20Versión&logo=github)](https://github.com/Kirutre/wavely/releases)
[![License: MIT](https://img.shields.io/badge/Licencia-MIT-yellow?logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Privacy Policy](https://img.shields.io/badge/Politica%20de-Privacidad-green?logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgLTIwIDM0MCAzNDAiPgogIDxnIGZpbGw9Im5vbmUiIHN0cm9rZT0id2hpdGUiIHN0cm9rZS13aWR0aD0iMTgiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCI+CiAgICA8bGluZSB4MT0iNDAiIHkxPSIxMzUiIHgyPSI0MC4wMSIgeTI9IjE2NSI+PC9saW5lPgogICAgPGxpbmUgeDE9Ijc1IiB5MT0iMTI1IiB4Mj0iNzUuMDEiIHkyPSIxNzUiPjwvbGluZT4KICAgIDxsaW5lIHgxPSIxMTAiIHkxPSIxMTAiIHgyPSIxMTAuMDEiIHkyPSIxOTAiPjwvbGluZT4KICAgIDxsaW5lIHgxPSIxNDUiIHkxPSIxMjUiIHgyPSIxNDUuMDEiIHkyPSIxNzUiPjwvbGluZT4KICAgIDxwYXRoIGQ9Ik0gMTQ1LDkwIEEgNjUsNjUgMCAwIDEgMTQ1LDIxMCI+PC9wYXRoPgogICAgPHBhdGggZD0iTSAxNzUsNzAgQSA5MCw5MCAwIDAgMSAxNzUsMjMwIj48L3BhdGg+CiAgICA8cGF0aCBkPSJNIDIwNSw1MCBBIDExNSwxMTUgMCAwIDEgMjA1LDI1MCI+PC9wYXRoPgogICAgPHBhdGggZD0iTSAyMzUsMzAgQSAxNDAsMTQwIDAgMCAxIDIzNSwyNzAiPjwvcGF0aD4KICA8L2c+Cjwvc3ZnPgo=)](PRIVACY_POLICY.es.md)

### Idiomas disponibles
[![Language: English](https://img.shields.io/badge/Language-English-blue?logo=googletranslate&logoColor=white)](README.md)
[![Idioma: Español](https://img.shields.io/badge/Idioma-Español-red?logo=googletranslate&logoColor=white)](README.es.md)

**Wavely** es una extensión diseñada para personalizar la experiencia al navegar por internet añadiendo efectos de sonido a diferentes acciones dentro de tu navegador.

---

## 🖼️ Imágenes
### Página de Configuraciones
![Página de opciones](/images/options_page.png "Página de configuraciones")

### Modal para personalizar los Eventos
![Modal](/images/modal.png "Modal de eventos")

---

## ✨ Características
- 🔊 **Sonidos Personalizables:** actualmente, puedes asignar sonidos a:
   * ➕ Abrir/Cerrar pestañas.
   * ⌨️ Pulsaciones de teclas.

- 🛠️ **Configuración Sencilla:** interfaz intuitiva para gestionar tus archivos de audio.

- 🚀 **Ligero:** optimizado para no afectar el rendimiento al navegar.

## ⏭️ ~~Próximas Características~~ ¡¡¡Características Finalizadas!!!
- 🎚️ **Controlador de Volumen:** para que seas tú quien decida qué tan rápido destrozar tus oídos.

- ⌨️ **Múltiples teclas, mismo sonido:** para que asignes tus sonidos favoritos a tu teclado.

## 💻 Tecnologías utilizadas
* JavaScript (WebExtensionAPI): para la lógica de fondo y eventos del navegador.

* HTML: para la página de opciones.

* CSS (Tailwind CSS): para el diseño de la interfaz.

## ⬇️ Instalación

### Para Usuarios
Ya disponible en [**Firefox Add-ons**](https://addons.mozilla.org/es-ES/firefox/addon/wavely/) y [**Chrome Web Store**](https://chromewebstore.google.com/detail/wavely-kirutre/hbbhbkidoemiahjkcgfbijpcjpfikaec) o, si prefieres, puedes instalarlo manualmente descargando el .zip de distribución correspondiente a tu navegador en el [Último Release](https://github.com/kirutre/wavely/releases/latest) o siguiendo los pasos de desarrollo.

### Guía para Desarrolladores (Instalación Manual)
Si deseas modificar la extensión o contribuir al código, sigue estos pasos para configurar tu entorno local.

1. **Clona este repositorio**
   ```bash
   git clone https://github.com/Kirutre/wavely.git

   cd wavely
   ```

2. **Gestión de Estilos (Tailwind CSS)**

   Esta extensión utiliza Tailwind CSS para la interfaz. El archivo `output.css` ya viene incluido en el repositorio para que la extensión funcione inmediatamente, pero si realizas cambios en el diseño, deberás recompilarlo.

   #### Recompilar `output.css`
   1. Descarga el ejecutable de la CLI según tu sistema operativo desde [Tailwind CSS Releases](https://github.com/tailwindlabs/tailwindcss/releases/tag/v4.1.18).

   2. Coloca el ejecutable en la raíz del proyecto y renómbralo a `tailwindcss-cli`.

   3. Ejecuta el siguiente comando para compilar y observar cambios en tiempo real.

   ```bash
   ./tailwindcss-cli -i ./options/input.css -o ./options/output.css --watch --minify
   ```

> [!TIP]
> Si tienes `Node.js` instalado, puedes evitar descargar el binario manualmente usando:

```bash
npx @tailwindcss/cli -i ./options/input.css -o ./options/output.css --watch --minify
```

3. **Cargar para pruebas**
   + En Firefox
      1. Renombra el archivo `manifest-firefox.json` a `manifest.json`.

      2. Abre Firefox y escribe `about:debugging` en la barra de direcciones.

      3. Haz clic en "Este Firefox".

      4. Haz click en "Cargar complemento temporal...".

      5. Selecciona el archivo `manifest.json` que se encuentra en la raíz del proyecto.
   
   + En Chromium
      1. Renombra el archivo `manifest-chromium.json` a `manifest.json`.

      2. Abre tu navegador basado en Chromium y escribe `chrome://extensions/` en la barra de direcciones.

      3. Activa el "Modo de Desarrollador".

      4. Haz clic en "Cargar descomprimido" o "Cargar desempaquetado".

      5. Selecciona la carpeta raíz del proyecto (donde está el manifest.json).

## 🤝 Contribuir
¡Las contribuciones son lo que hacen mejorar al software, y estoy encantado de ver qué puedes ofrecer!

Por favor lee las [**Pautas de contribución**](CONTRIBUTING.es.md) para empezar. Ya sea para corregir un bug o sugerir una nueva _feature_, ¡toda ayuda es bienvenida!.

## 📝 Licencia y Politica de Privacidad
Distribuido bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más información.

En ningún caso yo (el desarrollador) seré responsable de ninguna reclamación, daño u otra responsabildiad que surja del uso o mal uso de esta extensión.. Consulta el archivo [PRIVACY_POLICY](PRIVACY_POLICY.es.md) para más información.

## 📬 Contacto
Kirutre - [GitHub](https://github.com/kirutre)

Kirutre - contact.kirutre+wavely@gmail.com

Link del proyecto: https://github.com/Kirutre/wavely
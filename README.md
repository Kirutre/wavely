![Banner](/images/big_banner.png "Banner")

# 🎵 Wavely

[![Firefox Version](https://img.shields.io/amo/v/wavely?label=Firefox%20Add-ons&logo=firefoxbrowser&logoColor=white&color=FF7139)](https://addons.mozilla.org/en-US/firefox/addon/wavely/)
[![Chrome Version](https://img.shields.io/chrome-web-store/v/hbbhbkidoemiahjkcgfbijpcjpfikaec?label=Chrome%20Web%20Store&logo=googlechrome&logoColor=white&color=4285F4)](https://chromewebstore.google.com/detail/wavely-kirutre/hbbhbkidoemiahjkcgfbijpcjpfikaec)
[![GitHub Release](https://img.shields.io/github/v/release/Kirutre/wavely?label=Latest%20Version&logo=github)](https://github.com/Kirutre/wavely/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Privacy Policy](https://img.shields.io/badge/Privacy-Policy-green?logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgLTIwIDM0MCAzNDAiPgogIDxnIGZpbGw9Im5vbmUiIHN0cm9rZT0id2hpdGUiIHN0cm9rZS13aWR0aD0iMTgiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCI+CiAgICA8bGluZSB4MT0iNDAiIHkxPSIxMzUiIHgyPSI0MC4wMSIgeTI9IjE2NSI+PC9saW5lPgogICAgPGxpbmUgeDE9Ijc1IiB5MT0iMTI1IiB4Mj0iNzUuMDEiIHkyPSIxNzUiPjwvbGluZT4KICAgIDxsaW5lIHgxPSIxMTAiIHkxPSIxMTAiIHgyPSIxMTAuMDEiIHkyPSIxOTAiPjwvbGluZT4KICAgIDxsaW5lIHgxPSIxNDUiIHkxPSIxMjUiIHgyPSIxNDUuMDEiIHkyPSIxNzUiPjwvbGluZT4KICAgIDxwYXRoIGQ9Ik0gMTQ1LDkwIEEgNjUsNjUgMCAwIDEgMTQ1LDIxMCI+PC9wYXRoPgogICAgPHBhdGggZD0iTSAxNzUsNzAgQSA5MCw5MCAwIDAgMSAxNzUsMjMwIj48L3BhdGg+CiAgICA8cGF0aCBkPSJNIDIwNSw1MCBBIDExNSwxMTUgMCAwIDEgMjA1LDI1MCI+PC9wYXRoPgogICAgPHBhdGggZD0iTSAyMzUsMzAgQSAxNDAsMTQwIDAgMCAxIDIzNSwyNzAiPjwvcGF0aD4KICA8L2c+Cjwvc3ZnPgo=)](PRIVACY_POLICY.md)

### Available Languages
[![Language: English](https://img.shields.io/badge/Language-English-blue?logo=googletranslate&logoColor=white)](README.md)
[![Idioma: Español](https://img.shields.io/badge/Idioma-Español-red?logo=googletranslate&logoColor=white)](README.es.md)

**Wavely** is an extension designed to personalize your web browsing experience by adding sound effects to different actions within your browser.

---

## 🖼️ Images
### Settings Page
![Settings Page](/images/options_page.png "Settings page")

### Event Customization Modal
![Modal](/images/modal.png "Event modal")

---

## ✨ Features
- 🔊 **Custom Sounds:** currently, you can assign sounds to:
    * ➕ Open/Close tabs.
    * ⌨️ Keystrokes.

- 🛠️ **Simple Configuration:** intuitive interface to manage your audio files.

- 🚀 **Lightweight:** optimized to ensure no impact on browser performance.

## ⏭️ ~~Upcoming Features~~ Completed Features!!!
- 🎚️ **Volume Control:** because only you should decide how fast you want to destroy your ears.

- ⌨️ **Multiple keys, same sound:** so you can assign your favorite sounds to your keyboard.

## 💻 Technologies Used
* JavaScript (WebExtensionAPI): for background logic and browser events.

* HTML: for the options page.

* CSS (Tailwind CSS): for the interface design.

## ⬇️ Installation

### For Users
Now available on [**Firefox Add-ons**](https://addons.mozilla.org/en-US/firefox/addon/wavely/) and [**Chrome Web Store**](https://chromewebstore.google.com/detail/wavely-kirutre/hbbhbkidoemiahjkcgfbijpcjpfikaec) or, if you prefer, you can install it manually by downloading the distribution .zip for your browser from the [Latest Release](https://github.com/kirutre/wavely/releases/latest) or by following the development steps.

### Developer Guide (Manual Installation)
If you want to modify the extension or contribute to the code, follow these steps to set up your local environment.

1. **Clone this repository**
    ```bash
    git clone https://github.com/Kirutre/wavely.git

    cd wavely
    ```

2. **Styles Management (Tailwind CSS)**

    This extension uses Tailwind CSS for the interface. The `output.css` file is already included in the repository so the extension works immediately, but if you make design changes, you will need to recompile it.

    #### Recompile `output.css`
    1. Download the CLI executable for your operating system from [Tailwind CSS Releases](https://github.com/tailwindlabs/tailwindcss/releases/tag/v4.1.18).

    2. Place the executable in the project root and rename it to `tailwindcss-cli`.

    3. Run the following command to compile and watch changes in real-time.

    ```bash
    ./tailwindcss-cli -i ./options/input.css -o ./options/output.css --watch --minify
    ```

> [!TIP]
> If you have Node.js installed, you can avoid downloading the binary manually by using:

```bash
npx @tailwindcss/cli -i ./options/input.css -o ./options/output.css --watch --minify
```

3. **Load for testing**
    + In Firefox
        1. Rename `manifest-firefox.json` to `manifest.json`.

        2. Open Firefox and type `about:debugging` in the address bar.

        3. Click on "This Firefox".

        4. Click on "Load Temporary Add-on...".

        5. Select the `manifest.json` file inside the project folder.
    
    + In Chromium
        1. Rename `manifest-chromium.json` to `manifest.json`.

        2. Open your Chromium-based browser and type `chrome://extensions/` in the address bar.

        3. Enable "Developer Mode".

        4. Click on "Load unpacked".

        5. Select the project root folder (where `manifest.json` is located).

## 🤝 Contributing
Contributions are what make software better, and I’m excited to see what you have to offer!

Please read the [**Contributing Guidelines**](CONTRIBUTING.md) to get started. Whether it's fixing a bug or suggesting a crazy new sound trigger, all help is welcome!

## 📝 License
Distributed under the MIT License. See the [LICENSE](LICENSE) file for more information.

In no event shall I (the developer) be liable for any claim, damages, or other liability arising from the use or misuse of this extension. See the [PRIVACY POLICY](PRIVACY_POLICY.md) file for more information.

## 📬 Contact
Kirutre - [GitHub](https://github.com/kirutre)

Kirutre - contact.kirutre+wavely@gmail.com

Project Link: https://github.com/Kirutre/wavely
# Privacy Policy for Wavely

**Effective Date:** August 2026
**Developer** Kirutre
**Contact:** contact.kirutre+sounds@gmail.com

## 1. Information Collection and Use
Wavely is being developed and maintained by an independent developer (Kirutre). The extension does not collect, store, transmit, or share any personal data, browsing history, or user activity. All operations take place locally in the user's device.

## 2. Local Storage and Data Retention
The extension uses the `browser.storage.local / chrome.storage.local` API exclusively to save user configuration settings (such as custom keybindings, volume preferences and uploaded audio files encoded in Base64). This data never leaves your local browser environment and it is automatically removed if you uninstall the extension.

## 3. Permissions Used
* **Storage / Unlimited Storage:** used solely to save your sound configurations and preferred key triggers locally on your device without storage limit restrictions.
* **Offscreen / Background Worker:** used to handle audio playback and background processing in compliance with modern browser extensions standards without impacting performance.
* **Content Scripts (`<all_urls>`):** used strictly to detect keypress events (`keydown`) on active tabs to trigger the sounds. No keycaps, text entries or web contents are recorded, monitored or transmitted anywhere.

## 4. User-Uploaded Content & Copyright Disclaimer
Wavely allows users to upload custom audio files for personal use.
* **User Responsibility:** users are solely responsible for ensuring they have the legal right or license to use any audio file uploaded to the extension.
* **Copyright Infringement:** as the sole developer, I (Kirutre) do not endorse, host or assume any liability for user-uploaded audio content that may violate third-party copyrights or intellectual property laws.

## 5. Limitation of Liability & License
Wavely is distributed under the **MIT License**. The software is provided "as is", without warranty of any kind, express or implied. In no event shall I (the developer) be liable for any claim, damages, or other liability arising from the use or misuse of this extension.

## 6. Changes to This Policy
This Privacy Policy may be updated as needed. Any changes will be posted on this [repository/page](https://github.com/Kirutre/wavely) with an effective date update.
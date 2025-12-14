# Bazloco's Zero-Touch Mod Vault

## 🚀 Overview
Welcome to the **Zero-Touch Mod Vault**, a custom repository for the Xbox 360 Homebrew Store script (by Derf).

This vault is designed for simplicity, offering zero-touch installation for various content, including games, utilities, dashboards, and boot animations.

### ✨ Key Features
* **Zero-Touch Animation Install:** Installing a new boot animation automatically **backs up** your existing `boot.wmv` to `boot.wmv.bak` before installing the new file.
* **Organized Categories:** Separate sections for Games, Emulators, Title Updates, and Utility Apps.
* **Direct Installation:** Content is automatically extracted to the correct path (`/Content/`, `/Apps/`, `/Emulators/`, etc.).

---

## 💻 How to Add the Repository

To access the Mod Vault, you need the **Xbox 360 Homebrew Store** script installed in your Aurora dashboard.

1.  **Open Aurora:** Launch the Aurora Dashboard on your RGH/JTAG console.
2.  **Access Scripts:** Press the **BACK** button > **Scripts** > **Xbox 360 Homebrew Store**.
3.  **Add New Repo:** Select the option to **Add New Repository**.
4.  **Enter URL:** Input the following URL exactly as shown (case-sensitive):

    ```
    [https://bazloco.github.io/xbox360-mod-vault/the_mod_vault.ini](https://bazloco.github.io/xbox360-mod-vault/the_mod_vault.ini)
    ```
5.  **Confirm:** Press START/A to save the repository.
6.  **Launch:** Select the new **Bazloco's Mod Vault** from your list and begin browsing!

---

## 💡 Important Notes and Warnings

### 1. Title ID Matching is Critical (For TUs and DLC)
* For any Title Update (TU) or DLC to function, it **must** match the region (Title ID) of the base game installed on your console.
* Check the full Title ID (e.g., `415608CB`) listed in the item description before downloading.

### 2. FakeAnim (Boot Animation) Setup
* **First Download:** Before installing a boot video, you must install the **FakeAnim Tool Installer** first (found in the **FakeAnim Boot Videos** menu).
* **DashLaunch:** After installing the FakeAnim Tool, you must open **DashLaunch** and ensure `fakeanim.xex` is set as a plugin for the tool to work.
* **Restore:** If you want to restore your previous boot video, navigate to the `Hdd1:\Apps\FakeAnim\jukebox\` folder using Aurora's File Manager and rename `boot.wmv.bak` back to `boot.wmv`.

### 3. Content Hosting
* This GitHub repository hosts only the small `.ini` files (the store listings).
* Due to GitHub's file size limits, the large `.7z` content files (games, videos) are hosted externally for reliable, high-speed downloads.

---

## 🛠️ Repository Technical Structure

The project uses the following file structure:


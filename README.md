# Project Overview

This repository contains supplementary files and documentation. The full Unity project builds and source archives are **not** stored in this repo due to size constraints. Instead, you can download everything from our Google Drive folder, which includes:

* **Android Platform Build and Project**: APK and full Unity project folder.
* **iOS Platform Build and Project**: Xcode project and full Unity project folder.

---

## Links

* **Google Drive Download:**

  * See the `links.rtf` file in this repository for the Google Drive URL where the complete builds and source projects are hosted.
  * Or download directly: [Google Drive Project Folder](https://drive.google.com/file/d/1bp4jmVgaME3kNxqoTCpuyX4CUbHiThD-/view?usp=drive_link)

---

## Repository Files

In addition to the `links.rtf`, this repository includes:

* **Project Book** (`book.pdf`) – comprehensive documentation of the project.
* **PowerPoint Presentation** (`presentation.pptx`) – slide deck summarizing features and architecture.
* **SUS Results** (`sus_results.docx`) – results from the System Usability Scale evaluation.

---

## Running the Android APK on an Android Device

1. **Download the APK**

   * Open the Google Drive link from the `links.rtf` file or click [here](https://drive.google.com/file/d/1bp4jmVgaME3kNxqoTCpuyX4CUbHiThD-/view?usp=drive_link).
   * Download the `unityfinalapk.apk` file to your device.

2. **Enable Unknown Sources**

   * On Android, go to **Settings > Security** (or **Applications**).
   * Enable **Install from Unknown Sources** to allow installation of apps from outside the Play Store.

3. **Install the APK**

   * Using a file manager app, navigate to the **Downloads** folder (or wherever you saved `unityfinalapk.apk`).
   * Tap the APK file and follow the prompts to install the application.

4. **Launch the App**

   * Tap **Open** from the installer, or find the app icon in your app drawer and launch it.

5. **Permissions & Usage**

   * Grant any runtime permissions requested (storage, camera, etc.) so the app functions correctly.

---

## Running the iOS App in Xcode

1. **Download the Xcode Project**

   * From the same Google Drive link in `links.rtf` or click [here](https://drive.google.com/file/d/1bp4jmVgaME3kNxqoTCpuyX4CUbHiThD-/view?usp=drive_link), download the `iOS_Unity_Project.zip` file.

2. **Unzip and Open in Xcode**

   * Unzip the archive to a folder on your Mac.
   * Double-click the `.xcodeproj` file (or open Xcode and choose **File → Open**).

3. **Configure Signing**

   * In Xcode, select your team under **Signing & Capabilities** for both the project and target.
   * Ensure a valid provisioning profile is selected.

4. **Build & Run on Device**

   * Connect your iOS device via USB.
   * Select your device in the target device dropdown and click **Build and Run** (▶️).

---

## Full Unity Projects

* **Android Project Folder:** Contains the Unity project configured for Android builds.
* **iOS Project Folder:** Contains the Unity project configured for iOS builds.

You can open either folder directly in Unity Editor to inspect or modify the source, then build to your chosen platform.

---

*For any questions or issues, please open an issue in this repository or contact the project maintainer.*

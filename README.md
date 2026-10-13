# VirtualShoppingWorld — phone-only free build

This is a starter 3D shopping-world prototype with:
- 3D mall environment and four shopfronts
- Stylized walking avatar
- Touch joystick and drag-to-look camera
- Sample products and local cart
- Android WebView packaging configuration

## Important
This ZIP is the **project source**, not a precompiled APK. The GitHub Actions workflow is configured to build a debug APK in the cloud. The project uses Three.js from jsDelivr CDN, so an internet connection is required when launching the prototype.

## Build the APK using only your Android phone
1. Sign in or create a free account at https://github.com.
2. Create a **public** repository named `VirtualShoppingWorld`.
3. In the repository, use **Add file → Upload files** and upload the contents of this ZIP (including the `.github` folder). If the GitHub mobile page hides upload controls, open GitHub in Chrome and enable **Desktop site**.
4. Commit the files to the `main` branch.
5. Open the repository's **Actions** tab. If prompted, enable workflows.
6. Select **Build VirtualShoppingWorld APK** → **Run workflow**.
7. Wait for the run to finish successfully. Open the completed run and download the `VirtualShoppingWorld-debug-apk` artifact.
8. Extract the downloaded artifact ZIP on your phone, tap `app-debug.apk`, and allow your browser/files app to install unknown apps if Android asks.

## Notes
- This is a prototype, not a commercial-ready game. It uses simple procedural 3D models and sample products.
- For performance, test on your phone and lower quality if needed.
- The APK is a debug build suitable for personal testing, not a signed Google Play release.
- No paid tool is required by this workflow, but GitHub Actions usage/availability can be subject to GitHub account limits and service policies.

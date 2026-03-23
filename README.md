# Degenerate gen 6.9.420

Android wrapper app for local ComfyUI. The app loads `http://127.0.0.1:8188` inside a WebView.

## Run locally on phone
1. Start ComfyUI on the phone:
   - Example: `python main.py --listen 0.0.0.0 --port 8188 --cpu`
2. Launch the app. If it cannot connect, tap **Retry** once ComfyUI is running.

## Build APK on GitHub Actions
1. Upload this project to your GitHub repo (main branch).
2. Go to **Actions -> Build APK -> Run workflow**.
3. Download the `degenerate-gen-apk` artifact.
4. Install `app-debug.apk` on your phone.

## Notes
- The app uses cleartext HTTP for `127.0.0.1`. This is only for local device use.

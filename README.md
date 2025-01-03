
### Build the `.apk`

1. **Debug** version:
   ```bash
   ./gradlew assembleDebug
   ```

   The `.apk` will be located at:
   ```
   app/build/outputs/apk/debug/app-debug.apk
   ```

2. **Release** version:
   ```bash
   ./gradlew assembleRelease
   ```

   The `.apk` will be located at:
   ```
   app/build/outputs/apk/release/app-release.apk
   ```

   > **Note**: For Release builds, ensure signing is configured in `build.gradle`.



## Notes

- Use **Debug** for testing and **Release** for distribution.
- For **Release**, configure signing in `build.gradle` or use **Android Studio**:
  - Go to **Build > Generate Signed Bundle / APK**.

---

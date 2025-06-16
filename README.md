You're an expert Android engineer and product designer. I'm building an Android app that shows full device information, both hardware and software. It should help users view their phone's detailed technical data, similar to apps like CPU-Z, DevCheck, or Device Info HW.
Help me design and implement an MVP for this app.


---
## 🎯 App Name: CoreDroid
### ✅ Goal:
Build a modern Android app using **Jetpack Compose** and **MVVM** (optional: MVI) that displays detailed **device information**, both software and hardware, in a user-friendly, clean layout.

---

## 📱 Core MVP Features:

### 🔋 Battery Info
- Battery health (cycle count, if accessible)
- Battery level, status, temperature
- Charging source (USB, AC, wireless)
### 💾 Storage Info
- Total internal/external storage
- Free vs used space
- App cache and media file sizes
### 📶 Network Info
- Wi-Fi and mobile network status
- IP address, MAC address
- Signal strength (dBm), network type (4G/5G)
### 📟 Display Info
- Screen resolution & density (DPI)
- Refresh rate, screen size (inches)
- Orientation, HDR support
### 🧠 CPU & RAM Info
- CPU model, architecture, number of cores
- CPU frequency per core
- Total and available RAM
### 📷 Camera Info
- Back and front camera megapixels
- Camera API level
- Hardware-level support info
### 🔐 System Info
- Android version & API level
- Kernel version, build number
- Manufacturer, model, bootloader, security patch
### 📲 Sensors
- List all available sensors
- Real-time values (accelerometer, gyroscope, light, etc.)
---
## 🛠️ Tech Stack Suggestions
- **Language**: Kotlin
- **UI**: Jetpack Compose + Material 3
- **Architecture**: MVVM (optional: Clean Architecture with MVI)
- **Permissions**: Handle runtime permission checks gracefully
- **Data**: Use system APIs like `Build`, `BatteryManager`, `SensorManager`, `StatFs`, `CameraManager`, `WifiManager`, `TelephonyManager`
- **Storage formatting**: Show size in GB/MB, battery in %, CPU frequency in GHz
---
## 💡 Bonus Suggestions (Optional but Nice)
- Export info to PDF or text file
- Share device report
- Dark mode support
- UI themes (light, AMOLED, pastel)
- Animations for transitions and loading
- Compare with previous stats (e.g. 7-day battery history)
---
### 🎨 UI Design Suggestion
Ask for a **clean, modular layout** using cards or expandable sections. Group content like:
- Overview (top cards: Android version, battery level, storage used)
- Hardware section (CPU, RAM, Display, Camera)
- Software section (OS, kernel, patch level)
- Network section (Wi-Fi, mobile, IPs)
- Sensors section (list with live data)
---
Please help me design the:
1. App architecture with Kotlin + Compose
2. Modular screen layout with best practices
3. ViewModel and repository structure
4. Code snippets to retrieve device data
5. UI suggestions to keep it clean and modern

Firstly create app design as mobile web page I want to see design. It should look modern show me all screens design

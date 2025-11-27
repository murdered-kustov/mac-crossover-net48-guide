# .NET Framework 4.8 Installation Guide for CrossOver on Mac
**Author:** murdered kustov

This repository provides a step-by-step guide to install .NET Framework 4.8 on macOS using CrossOver, including tips for Apple Silicon (M1/M2) and Intel Macs. 

##  Compatibility
- CrossOver officially supports .NET 4.8 ("Runs Great") on macOS.
- Recommended to use a **new 64-bit bottle** (Windows 10 x64).

##  Installation Steps

1. Install CrossOver from the official site.
2. Create a new **Windows 10 x64 bottle**.
3. Open **Install Windows Software** → search for `.NET Framework 4.8`.
4. If not found, download the offline installer: `dotNetFx48_Full_x86_x64.exe` from Microsoft.
5. Run the installer in the selected bottle.
6. Restart the bottle if needed.
7. Install your Windows applications in the same bottle.

## ️ Notes
- 64-bit bottles are recommended; 32-bit may cause issues.
- Install dependencies like Visual C++ runtimes, fonts, and DirectX as needed.

## Files
- `installers/` - offline installer `.exe`
- `screenshots/` - step-by-step images

# AdvStatusBarTools Extension 🚀

**Author:** AppGineerSahil - Sahil Shelke
**Category:** Extension | Free & Open Source  

---

## 📖 Introduction
Advanced Status & Navigation Bar customization, including visibility control, color/gradient styling, icon theme switching, transparency, immersive mode, and measurement support.  
Compatible with **hex colors** and **built-in color blocks**.

---

## 🧩 Blocks & Features

- Show / Hide / Toggle **StatusBar & NavigationBar**
- SetColor (**Hex / Color Block**) for both bars
- Set Icons to **Dark / Light** (status & navigation)
- **Transparent, Gradient, Pulse Effects**
- Enable **Immersive Sticky Mode**
- **GetBar Heights** (status, nav, combined)
- Event: **SystemThemeChanged (Dark/Light mode)**

---

## 📘 Block Documentation

| Block | Description |
|-------|-------------|
| `MakeStatusBarTransparent` | Makes the status bar fully transparent over screen content. |
| `SetStatusBarGradientHex(startHex, endHex, angle)` | Applies gradient (color to color) to status bar, angle 0–7. |
| `PulseStatusBar(color, durationMs)` | Briefly flashes the status bar with a color, then reverts. |
| `EnableImmersiveStickyMode` | Enters full‑screen immersive mode with swipe for system bars. |
| `GetCombinedBarHeight` | Returns combined status + navigation bar heights in pixels. |
| `SystemThemeChanged(isDarkMode)` *(Event)* | Fires when system theme (dark/light) changes. |
| `IsStatusBarVisible` *(Property)* | Boolean: whether the status bar is currently visible. |

---

## 🖼️ Screenshots / Block Previews
*(Insert screenshots or block images here)*

---

## 📥 Downloads

- 🔗 Check uploaded files. 

---

## 🙌 Credits & Support

Thanks to all contributors and testers!  
Special thanks to the **App Inventor / Kodular Community** ❤️

---

## ⚙️ Android API & Permissions

- Compatible with **Android API 21+ (Lollipop and higher)**  
- Icon color control:  
  - Status bar → **Android M+ (API 23)**  
  - Navigation bar → **Android O+ (API 26)**  
- Permissions: `android.permission.WRITE_SECURE_SETTINGS` *(optional; required for certain OEM customizations)*

---

## 💡 Usage Tips

- Use `GetStatusBarHeight` to add top padding when using transparent bars.  
- Reapply style blocks inside **Screen.Initialize** for consistent behavior.  
- OEMs may override icon color changes → always **test on real devices**.  

---

## 📌 License

This project is released as **Free & Open Source**.  
Feel free to use, modify, and contribute!  

---

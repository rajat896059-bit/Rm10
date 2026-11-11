# RaadWave Racing — Android 3D Starter Project

**App name:** RaadWave Racing  
**App icon:** `assets/raadwave_icon.svg` (red racing theme)

यह Godot 4 का शुरुआती 3D arcade racing prototype है। इसमें procedural road, पीछा करता camera, basic car body, acceleration, steering, brake, drift, nitro meter, stunt ramps और touch buttons शामिल हैं।

## चलाने के लिए
1. PC पर Godot Engine 4.3 या नया संस्करण इंस्टॉल करें।
2. Godot में `project.godot` खोलें।
3. Play (F6/F5) दबाएँ।

## कंट्रोल
- PC: Arrow keys / W-A-S-D से steering और acceleration; Space = Drift; Shift = Nitro.
- Android: स्क्रीन पर GO, BRAKE, ◀, ▶, DRIFT और NITRO बटन।

## Android APK बनाने के चरण
1. Godot के लिए Android export templates इंस्टॉल करें: Editor > Manage Export Templates.
2. Android SDK और OpenJDK सेट करें: Editor > Editor Settings > Export > Android.
3. Project > Export में Android preset जोड़ें।
4. Package name को अपने unique नाम से बदलें, उदाहरण: `com.yourstudio.raadwaveracing`.
5. Debug APK export करके अपने फोन पर टेस्ट करें। Play Store के लिए release keystore से signed AAB बनाएं।

## अभी prototype में क्या बाकी है
यह पूरा Asphalt 8 स्तर का तैयार गेम नहीं है। अभी यह playable foundation है। असली high-end गेम के लिए licensed 3D car/track assets, बेहतर physics, collision/AI opponents, race progression, sound, menus, optimization और device testing जोड़ना होगा। किसी दूसरे गेम के copyrighted models, tracks, logos या code का उपयोग न करें।

## App icon और package name
- Project Settings में Application > Config > Name = `RaadWave Racing` रखें।
- Application > Config > Icon में `res://assets/raadwave_icon.svg` सेट है।
- Android Export preset में Package/Unique Name को `com.yourstudio.raadwaveracing` जैसे अपने unique package name से बदलें।
- SVG icon source project में शामिल है; अलग-अलग store icon आकार/feature graphic की जरूरत Play Store publishing में पड़ सकती है।

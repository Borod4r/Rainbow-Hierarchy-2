# Rainbow Hierarchy 2

Have you ever thought about highlighting often used objects in your scene? This simple but colorful asset allows you to do that!

With Rainbow Hierarchy, you can set a custom icon and background for any object in the Hierarchy window.

Just hold the Alt key and click on any object in your scene. A configuration dialog will appear, and you'll be able to assign a custom icon and background to the corresponding object. Your own one or chose from dozens of presets!

Features:

* Assign a custom icon and background for any object in your Hierarchy window.
* Change icon or background for multiple objects at once
* Apply custom icon and background for all subfolders automatically
* Optional row shading and hierarchy tree outlines
* More than 200 icons are available out of the box

### Installation

Install via Unity Package Manager as a git package:

1. Open `Window → Package Manager`.
2. Click `+` → `Install package from git URL...`
3. Paste:

```
https://github.com/Borod4r/Rainbow-Hierarchy-2.git?path=Assets/Plugins/Borodar/RainbowHierarchy
```

Or add it to `Packages/manifest.json` manually:

```json
"com.borodar.rainbow-hierarchy": "https://github.com/Borod4r/Rainbow-Hierarchy-2.git?path=Assets/Plugins/Borodar/RainbowHierarchy"
```

Alternatively, clone this repository and copy `Assets/Plugins/Borodar` into your project's `Assets` folder.

# Technical Notes & Stability

* This asset relies heavily on Unity's internal Editor APIs. While stable for official releases, major Unity updates may occasionally break functionality until a patch is issued.
* Alpha and Beta versions of the Unity Editor are not officially supported. Use at your own risk in those environments.

# License

All the code in this repo is covered under the Apache 2.0 license:

https://www.apache.org/licenses/LICENSE-2.0

All the icons, images and other artwork is covered under Creative Commons Attribution-NonCommercial 4.0 International license:

https://creativecommons.org/licenses/by-nc/4.0/
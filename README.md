# 🔷 Advanced Rectangle Generator (Godot Plugin)

A versatile Godot editor plugin for automatically generating **rectangular 3D object arrays**.
Perfect for level designers who want to quickly arrange objects in rows and columns — featuring **live preview**, **random variations**, and a **preset system**.

---

## 🚀 Core Features

### 🔹 Rectangle Array Generator

* Creates objects in a 3D rectangular grid
* Fully customizable **rows**, **columns**, **spacing (X/Z)**, and **offsets**
* Supports **rotation**, **scaling**, and **height variation (Y)**
* Optional **centering** of the entire array

### 🔹 Live Preview

* Real-time preview directly in the Godot editor
* Multiple display modes: Transparent, Wireframe, Solid, Outline
* Adjustable preview color, transparency, and grid size
* Instant visual feedback while adjusting parameters

---

## 🎨 Advanced Features

* ✅ **Random rotation** (e.g. ±30°) for natural variation
* ✅ **Random scaling** (e.g. ±20%) for organic layouts
* ✅ **Progressive scaling** across rows
* ✅ **Positional jitter** for more dynamic structures
* ✅ **Preset System**:

  * Save, load, and delete presets
  * Manage them easily through the integrated GUI
  * Saved in `res://rectangle_generator_presets.cfg`

---

## ⚙️ How to Use

1. Enable the plugin in **Project > Project Settings > Plugins**
2. Select a 3D object (e.g. a `MeshInstance3D`) in your scene
3. Open **“Rectangle Multiplier”** from the top editor menu
4. Adjust parameters like rows, columns, spacing, scaling, etc.
5. Use the **Live Preview** or click **Generate** to create the array

---

## 🧠 Technical Details

* Duplicates the selected `Node3D` object in a rectangular pattern
* Integrated **Undo/Redo support** through the Godot editor
* Saves plugin settings persistently within the project
* Fully written in **GDScript**, compatible with **Godot 4.x**

---

## 💡 Use Cases

* **Level layouts** and **terrain decoration**
* **Architectural modeling** or **building structures**
* **Scene setup** and **rapid prototyping**
* Combine with the *Circle Multiplier* for complex designs

---

## 📁 Installation

1. Copy the plugin folder into:
   `res://addons/advanced_rectangle_generator/`
2. Enable it in:
   `Project > Project Settings > Plugins`

---

## 🧰 Compatibility

* ✅ Godot 4.2+
* 🧱 Works with all `Node3D`-based objects
* 💾 Cross-platform: Windows, Linux, macOS

---

## 📸 Preview (optional)

<img width="2557" height="1389" alt="image" src="https://github.com/user-attachments/assets/c178dd92-e660-4098-b160-e5447e510fa7" />

---

## ⚙️ License

Released under the **MIT License** — free to use, modify, and distribute.

---

## ✨ Author

**Developed by:**iMrArevio
💬 Feedback, ideas, or bug reports?
→ Open an [Issue](../../issues)

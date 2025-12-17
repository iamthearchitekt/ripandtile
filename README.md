# Rip & Tile 🩸

> **A Browser-based Doom Texture Converter**

**Rip & Tile** is a web tool designed for Doom modders. It instantly converts any image into a Doom-compatible texture, sprite, or graphic, ready for import into SLADE.



## ⚡ Features

*   **Doom Palette Conversion**: Automatically maps colors to the standard 256-color Doom `PLAYPAL`.
*   **Smart Dithering**: Choose between **Floyd-Steinberg**, **Bayer (Ordered)**, **Atkinson**, or **None** (Posterize).
*   **Asset Modes**:
    *   **Texture**: Forces opaque output, standard power-of-two sizes (64x128, 128x128, etc).
    *   **Sprite**: Preserves transparency for monsters/props.
    *   **Weapon**: Optimized for HUD graphics (Screen width fit).
*   **Zero Dependencies**: Runs completely in the browser. No server uploads, no installs.

## 🚀 Usage

1.  **[Launch the App](https://iamthearchitekt.github.io/ripandtile/)**
2.  Select your **Asset Type** (Texture, Sprite, Weapon).
3.  **Drag & Drop** your PNG/JPG image.
4.  Adjust **Dithering** to taste.
5.  **Download** the resulting PNG.

## 🛠️ Tech Stack

*   **Vanilla JS**: No frameworks, no build steps.
*   **HTML5 Canvas**: High-performance pixel manipulation.
*   **CSS3**: Modern glassmorphism UI.

## 📜 Credits

*   Built for the Doom Modding Community.
*   Fonts: *Outfit* (Google Fonts) & *M42* (Custom).

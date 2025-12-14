# Pixelation
# 🧱 Pixel Art Image Converter

Turn any image into crisp, retro-style pixel art right in your browser. Upload an image, tweak the palette + pixel scale, crop it how you want, and download the final pixelated result.

---

## ✨ Features

- 🎨 **Palette Picker** — Choose from a list of color palettes (see below)
- 🔲 **Pixel Scale Control** — Adjust how "chunky" the pixels are  
- 🖼️ **Output Resolution** — Select the final export resolution  
- ✂️ **Crop the Image** — Crop before converting  
- ⚡ **Real-time Preview** — See changes instantly as you edit  
- ↩️ **Undo Changes** — Step back through edits  
- 🧼 **Revert to Original** — Jump back to the original image  
- 🔄 **Reset App** — Clear everything and start over  
- ⬇️ **Download Pixelated Image** — Export your pixel art result  
- 📐 **Crop Tool Upgrade** — Supports **freeform** crops as well as **square** crops

---

## 🎨 Available Color Palettes

The tool includes the following retro and classic color palettes:

- **Image Default** — Keep original image colors (no palette conversion)
- **Greyscale** — 16-shade greyscale palette
- **NES** — Classic Nintendo Entertainment System colors
- **GameBoy** — Original Game Boy 4-color green palette
- **AmigaOCS** — Commodore Amiga OCS color set
- **C64** — Commodore 64 classic palette
- **PICO-8** — Fantasy console 16-color palette (default)
- **SNES** — Super Nintendo Entertainment System colors
- **NeoGeo** — SNK Neo Geo arcade palette
- **Genesis** — Sega Genesis/Mega Drive colors
- **Web Safe** — 216-color web-safe palette

---

## � How to Use the Tool

### Step 1: Upload Your Image
1. Click the **"Upload Image"** button at the top of the controls panel
2. Select an image file from your device (JPG, PNG, GIF, etc.)
3. Your image will appear in the preview area on the right

### Step 2: Choose a Color Palette
1. Click the **Color Palette** dropdown to see all available palettes
2. Browse through the options - each shows a preview of its colors
3. Select a palette to instantly apply it to your image
   - **Tip:** Start with "Image Default" to keep original colors, or try "PICO-8" for a classic retro look

### Step 3: Adjust Pixel Scale (Optional)
1. Use the **Pixel Scale** slider to control how "blocky" your image looks
2. Drag left (1px) for subtle pixelation, right (20px) for chunky retro pixels
3. Changes apply in real-time as you adjust the slider

### Step 4: Set Output Resolution (Optional)
1. Use the **Output Resolution** dropdown to resize your final image
2. Options include: Auto (keeps original size), 128×128, 64×64, 32×32, or 16×16
3. Smaller resolutions create more dramatic pixel art effects

### Step 5: Crop Your Image (Optional)
1. Click **"Enable Crop Tool"** to activate the crop overlay
2. **Drag** the crop box to reposition it over your desired area
3. **Drag the corner handle** to resize the crop area
4. Use the **Aspect Ratio** dropdown to switch between Square (1:1) or Free cropping
5. Fine-tune with the **Width, Height, X, and Y** input fields if needed
6. Click **"Apply"** to crop, or **"Cancel"** to discard changes

### Step 6: Undo or Revert Changes
- Click **"Undo"** to step back through your edits one at a time
- Click **"Restore"** to jump back to the original uploaded image instantly
- Both buttons are only available after you've made changes

### Step 7: Download Your Pixel Art
1. Once you're happy with the result, click **"Get Image"**
2. Your pixelated image will download as a PNG file
3. The file is ready to use in games, art projects, or social media!

### Pro Tips 💡
- **Experiment with palettes first** before adjusting pixel scale - different palettes dramatically change the feel
- **Crop before applying effects** if you only want to pixelate part of your image
- **Use smaller output resolutions** (32×32 or 16×16) for avatar/icon creation
- **Mobile friendly** - the tool works okay on iPhone and Android devices in portrait mode

---

## 🚀 Getting Started (Installation)

### ✅ Option 1: Run locally (simple)
1. Clone or download this repo
2. Open `pixelate-standalone.html` in your browser  
   - (Tip: use VS Code + Live Server for a smoother dev loop)

### ✅ Option 2: Serve it locally (recommended)
If you want a local server for better caching + module support:

```bash
# Python
python -m http.server 8080


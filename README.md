# MultiMC & Prism Launcher Themes & Icon Themes

> *«Even in cold geometry, order breeds grace. Form and function aligned beneath a calm, lunar gaze.»*  
> — *The Architect*

A curated collection of minimalist, aesthetic, and high-contrast dark themes and matching vector icon themes meticulously calibrated for **Prism Launcher**, **MultiMC**, and compatible Qt-based Minecraft launchers.

---

## 🧭 Navigation

- [🎨 Gallery & Showcase](#-gallery--showcase)
  - [Nord](#nord)
  - [Rosé Pine](#rosé-pine)
  - [Kanagawa Wave](#kanagawa-wave)
  - [GitHub Dark High Contrast](#github-dark-high-contrast)
  - [Catppuccin Mocha](#catppuccin-mocha)
- [✨ Icon Themes](#-icon-themes)
- [📦 Quick & Simple Installation](#-quick--simple-installation)
  - [Step 1: Open your Prism Launcher root folder](#step-1-open-your-prism-launcher-root-folder)
  - [Step 2: Install `themes` and `iconthemes`](#step-2-install-themes-and-iconthemes)
    - [Option A: One-command install with Git (Terminal)](#option-a-one-command-install-with-git-terminal)
    - [Option B: Manual download without Git (ZIP)](#option-b-manual-download-without-git-zip)
  - [Step 3: Activate your theme & icons in the launcher](#step-3-activate-your-theme--icons-in-the-launcher)
- [⚙️ Technical Notes & Structure](#️-technical-notes--structure)
- [📜 License & Credits](#-license--credits)

---

## 🎨 Gallery & Showcase

### Nord
> *An arctic, north-bluish clean palette engineered for calm endurance and eye comfort.*

| Preview | Specifications |
| :--- | :--- |
| ![Nord Preview](https://raw.githubusercontent.com/Sto3IV/MultiMC-themes/assets/screenshots/nord.png) | **Theme:** `Nord`<br>**Icon Pack:** `Flat (Nord)`<br>**Base:** `#2E3440`<br>**Alternate Base:** `#353B49`<br>**Button / Surface:** `#434C5E`<br>**Accent / Frost:** `#88C0D0`<br>**Text / Snow:** `#D8DEE9` / `#ECEFF4` |

---

### Rosé Pine
> *Ethereal dark velvet drenched in muted rose, iris, and pine serenity.*

| Preview | Specifications |
| :--- | :--- |
| ![Rosé Pine Preview](https://raw.githubusercontent.com/Sto3IV/MultiMC-themes/assets/screenshots/rose.png) | **Theme:** `Rosé Pine`<br>**Icon Pack:** `Flat (Rosé Pine)`<br>**Base:** `#191724`<br>**Alternate Base:** `#21202E`<br>**Button / Surface:** `#26233A`<br>**Highlight / Pine:** `#403D52`<br>**Link / Iris:** `#C4A7E7`<br>**Text:** `#E0DEF4` |

---

### Kanagawa Wave
> *Inspired by the sumi ink, wave blue, and autumn tones of traditional Japanese woodblock prints.*

| Preview | Specifications |
| :--- | :--- |
| ![Kanagawa Wave Preview](https://raw.githubusercontent.com/Sto3IV/MultiMC-themes/assets/screenshots/kanagawa.png) | **Theme:** `Kanagawa Wave`<br>**Icon Pack:** `Flat (Kanagawa Wave)`<br>**Base / Sumi Ink:** `#1F1F28`<br>**Alternate Base:** `#252530`<br>**Button / Surface:** `#363646`<br>**Highlight / Wave Blue:** `#2D4F67`<br>**Text / Fuji White:** `#DCD7BA` |

---

### GitHub Dark High Contrast
> *Ultra-crisp, surgical contrast built on Primer Design primitives. Zero visual blur, maximum readability.*

| Preview | Specifications |
| :--- | :--- |
| ![GitHub Dark High Contrast Preview](https://raw.githubusercontent.com/Sto3IV/MultiMC-themes/assets/screenshots/github.png) | **Theme:** `GitHub Dark High Contrast`<br>**Base:** `#010409`<br>**Alternate Base:** `#151b23`<br>**Button / Surface:** `#262c36`<br>**Highlight:** `#504f4f`<br>**Text / Bright:** `#ffffff` / `#ff9492` |

---

### Catppuccin Mocha
> *A smooth, soothing dark pastel palette with warm lavender accents and deep charcoal base.*

| Preview | Specifications |
| :--- | :--- |
| ![Catppuccin Mocha Preview](https://raw.githubusercontent.com/Sto3IV/MultiMC-themes/assets/screenshots/catpuccin.png) | **Theme:** `Catppuccin Mocha`<br>**Base / Crust:** `#181825`<br>**Alternate Base / Mantle:** `#1e1e2e`<br>**Button / Surface:** `#313244`<br>**Highlight / Pink:** `#f5c2e7`<br>**Link / Lavender:** `#b4befe`<br>**Text:** `#cdd6f4` |

---

## ✨ Icon Themes

This collection includes custom recolored scalable SVG icon packs specifically matching the color themes:

- **`Flat (Nord)`** — Recolored to Nord Snow Storm (`#D8DEE9`).
- **`Flat (Rosé Pine)`** — Recolored to Rosé Pine text (`#E0DEF4`).
- **`Flat (Kanagawa Wave)`** — Recolored to Kanagawa Fuji White (`#DCD7BA`).

These icon packs live in the `iconthemes/` directory and replace the default launcher sidebar and button icons with clean, unified vector graphics.

---

## 📦 Installation

### Step 1: Open your Prism Launcher root folder

Open your launcher's root directory (the folder containing `instances`, `prismlauncher.cfg`, etc.):

- **From inside the Launcher:**
  1. Open **Prism Launcher** (or **MultiMC**).
  2. Click **Settings** ➔ **User Interface**.
  3. Under the theme section, click the **Folder icon** or click **Folders** in the sidebar to reveal the launcher root directory.
- **Or via File Explorer:**
  - **Windows (Standard AppData):**  
    Press `Win + R`, paste `%APPDATA%\PrismLauncher` and press `Enter` *(or open your portable launcher folder)*.
  - **Linux (Flatpak / Steam Deck):**  
    `~/.var/app/org.prismlauncher.PrismLauncher/data/PrismLauncher/`
  - **Linux (Standard):**  
    `~/.local/share/PrismLauncher/`
  - **macOS:**  
    `~/Library/Application Support/PrismLauncher/`

---

### Step 2: Install `themes` and `iconthemes`

Choose the method that works best for you:

#### Option A: One-command install with Git (Terminal)

If you have **Git** installed on your system:

1. Inside your Prism Launcher root folder, right-click any blank space and click **Open in Terminal** *(native in Windows 11 and Linux)*.
2. Run this single command:

**On Windows (PowerShell):**
```powershell
git clone --depth 1 https://github.com/Sto3IV/MultiMC-themes.git temp; Copy-Item -Recurse -Force temp\themes, temp\iconthemes .; Remove-Item -Recurse -Force temp
```

**On Linux / macOS:**
```bash
git clone --depth 1 https://github.com/Sto3IV/MultiMC-themes.git temp && cp -r temp/themes temp/iconthemes . && rm -rf temp
```

> **How it works:** This command downloads only the `themes` and `iconthemes` folders directly into your launcher root and automatically removes the temporary folder, leaving behind no unnecessary readmes or git folders.

---

#### Option B: Manual download without Git (ZIP)

If you do **not** have Git installed:

1. Download the repository archive: **[Download ZIP](https://github.com/Sto3IV/MultiMC-themes/archive/refs/heads/main.zip)** (or click the green **Code** button at the top of GitHub and select **Download ZIP**).
2. Open the downloaded `.zip` file.
3. You will see two folders: **`themes`** and **`iconthemes`**.
4. Drag and drop both **`themes`** and **`iconthemes`** directly into your Prism Launcher root folder.
5. That's it!

---

### Step 3: Activate your theme & icons in the launcher

1. Open **Prism Launcher** or **MultiMC**.
2. Navigate to **Settings** ➔ **User Interface**.
3. Pick theme and icons set.

---

## ⚙️ Technical Notes & Structure

```
MultiMC-themes/
├── themes/
│   ├── catpuccin/
│   │   ├── theme.json
│   │   ├── theme.json.license
│   │   └── themeStyle.css
│   ├── github/
│   │   ├── theme.json
│   │   ├── themeStyle.css
│   │   └── resources/
│   ├── kanagawa-wave/
│   │   ├── theme.json
│   │   ├── themeStyle.css
│   │   └── resources/
│   ├── nord/
│   │   ├── theme.json
│   │   ├── themeStyle.css
│   │   └── resources/
│   └── rose-pine/
│       ├── theme.json
│       ├── themeStyle.css
│       └── resources/
├── iconthemes/
│   ├── kanagawa-wave/
│   │   ├── index.theme
│   │   └── scalable/ (*.svg)
│   ├── nord/
│   │   ├── index.theme
│   │   └── scalable/ (*.svg)
│   └── rose-pine/
│       ├── index.theme
│       └── scalable/ (*.svg)
├── LICENSE
└── README.md
```

> [!IMPORTANT]
> **Preserving Folder Names (Relative URL Resolution):**  
> Qt stylesheets (`themeStyle.css`) resolve UI assets using the relative path `themes/<folder_name>/resources/...`.  
> Do not rename individual theme or icon folders, otherwise the custom UI graphics and icons will fail to load.

---

## 📜 License & Credits

This repository is distributed under the [Apache License 2.0](LICENSE).  
Individual color palettes, icon foundations, and aesthetic motifs belong to their respective creators and open-source communities:
- **Nord:** [Arctic Ice Studio](https://www.nordtheme.com/)
- **Rosé Pine:** [Rosé Pine Team](https://rosepinetheme.com/)
- **Kanagawa:** [rebelot / Kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim)
- **GitHub Dark High Contrast:** [GitHub Primer Primitives](https://primer.style/)
- **Catppuccin:** [Catppuccin Community](https://github.com/catppuccin/catppuccin)
- **Icons base:** [Prism Launcher upstream flat_white vector set](https://github.com/PrismLauncher/PrismLauncher)

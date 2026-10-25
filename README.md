# MultiMC & Prism Launcher Themes

> *«Even in cold geometry, order breeds grace. Form and function aligned beneath a calm, lunar gaze.»*  
> — *Ranni, The Architect*

A curated collection of minimalist, aesthetic, and high-contrast dark themes meticulously calibrated for **Prism Launcher**, **MultiMC**, and compatible Qt-based Minecraft launchers.

[![Launchers](https://img.shields.io/badge/Launchers-MultiMC%20%7C%20Prism%20%7C%20PolyMC-blue?style=for-the-badge&logo=minecraft)](https://prismlauncher.org/)
[![Engine](https://img.shields.io/badge/Engine-Qt5%20%2F%20Qt6%20Fusion-informational?style=for-the-badge&logo=qt)](https://www.qt.io/)
[![Themes](https://img.shields.io/badge/Themes-5%20Curated-purple?style=for-the-badge)](#-gallery--showcase)
[![License](https://img.shields.io/badge/License-Apache--2.0-green?style=for-the-badge)](LICENSE)

---

## 🧭 Navigation

- [🎨 Gallery & Showcase](#-gallery--showcase)
  - [Nord](#nord)
  - [Rosé Pine](#rosé-pine)
  - [Kanagawa Wave](#kanagawa-wave)
  - [GitHub Dark High Contrast](#github-dark-high-contrast)
  - [Catppuccin Mocha](#catppuccin-mocha)
- [📦 Installation Guide](#-installation-guide)
  - [Method 1: Clone via Git](#method-1-clone-via-git)
  - [Method 2: Manual Download (.zip)](#method-2-manual-download-zip)
  - [Activating the Theme in Launcher](#activating-the-theme-in-launcher)
  - [Platform Paths (Where is my `themes` folder?)](#platform-paths)
- [🇷🇺 Инструкция по установке (Русский)](#-инструкция-по-установке-русский)
- [⚙️ Technical Notes & Structure](#️-technical-notes--structure)
- [📜 License](#-license)

---

## 🎨 Gallery & Showcase

### Nord
> *An arctic, north-bluish clean palette engineered for calm endurance and eye comfort.*

| Preview | Palette Specifications |
| :--- | :--- |
| ![Nord Preview](screenshots/nord.png) | **Name:** `Nord`<br>**Widget Style:** `Fusion`<br>**Base:** `#2E3440`<br>**Alternate Base:** `#353B49`<br>**Button / Surface:** `#434C5E`<br>**Accent / Frost:** `#88C0D0`<br>**Text / Snow:** `#D8DEE9` / `#ECEFF4`<br>**Vector Assets:** Included (`resources/`) |

---

### Rosé Pine
> *Ethereal dark velvet drenched in muted rose, iris, and pine serenity.*

| Preview | Palette Specifications |
| :--- | :--- |
| ![Rosé Pine Preview](screenshots/rose.png) | **Name:** `Rosé Pine`<br>**Widget Style:** `Fusion`<br>**Base:** `#191724`<br>**Alternate Base:** `#21202E`<br>**Button / Surface:** `#26233A`<br>**Highlight / Pine:** `#403D52`<br>**Link / Iris:** `#C4A7E7`<br>**Text:** `#E0DEF4`<br>**Vector Assets:** Included (`resources/`) |

---

### Kanagawa Wave
> *Inspired by the sumi ink, wave blue, and autumn tones of traditional Japanese woodblock prints.*

| Preview | Palette Specifications |
| :--- | :--- |
| ![Kanagawa Wave Preview](screenshots/kanagawa.png) | **Name:** `Kanagawa Wave`<br>**Widget Style:** `Fusion`<br>**Base / Sumi Ink:** `#1F1F28`<br>**Alternate Base:** `#252530`<br>**Button / Surface:** `#363646`<br>**Highlight / Wave Blue:** `#2D4F67`<br>**Text / Fuji White:** `#DCD7BA`<br>**Vector Assets:** Included (`resources/`) |

---

### GitHub Dark High Contrast
> *Ultra-crisp, surgical contrast built on Primer Design primitives. Zero visual blur, maximum readability.*

| Preview | Palette Specifications |
| :--- | :--- |
| ![GitHub Dark High Contrast Preview](screenshots/github.png) | **Name:** `GitHub Dark High Contrast`<br>**Widget Style:** `Fusion`<br>**Base:** `#010409`<br>**Alternate Base:** `#151b23`<br>**Button / Surface:** `#262c36`<br>**Highlight:** `#504f4f`<br>**Text / Bright:** `#ffffff` / `#ff9492`<br>**Vector Assets:** Custom checkmarks & radio icons (`resources/`) |

---

### Catppuccin Mocha
> *A smooth, soothing dark pastel palette with warm lavender accents and deep charcoal base.*

| Preview | Palette Specifications |
| :--- | :--- |
| ![Catppuccin Mocha Preview](screenshots/catpuccin.png) | **Name:** `Catppuccin Mocha`<br>**Widget Style:** `Fusion`<br>**Base / Crust:** `#181825`<br>**Alternate Base / Mantle:** `#1e1e2e`<br>**Button / Surface:** `#313244`<br>**Highlight / Pink:** `#f5c2e7`<br>**Link / Lavender:** `#b4befe`<br>**Text:** `#cdd6f4` |

---

## 📦 Installation Guide

You do **not** need any external installation scripts or separate documents. Everything is configured right here.

### Method 1: Clone via Git

If you use Git, open your terminal inside your launcher's data directory or clone directly:

```bash
# Clone the repository
git clone https://github.com/Sto3IV/MultiMC-themes.git

# Copy the themes directory contents into your launcher's themes folder
# (Adjust the destination path according to your OS below)
```

### Method 2: Manual Download (.zip)

1. Click the green **Code** button at the top of this repository, then select **Download ZIP** (or [Click Here](https://github.com/Sto3IV/MultiMC-themes/archive/refs/heads/main.zip)).
2. Extract the downloaded archive.
3. Inside the extracted folder, you will find a `themes/` directory containing:
   - `catpuccin/`
   - `github/`
   - `kanagawa-wave/`
   - `nord/`
   - `rose-pine/`
4. Copy either the entire `themes/` folder (to merge it) or individual theme folders directly into your launcher's `themes/` directory.

---

### Activating the Theme in Launcher

1. Launch **Prism Launcher** / **MultiMC**.
2. Navigate to **Settings** (Настройки) ➔ **User Interface** (Интерфейс пользователя).
3. Under the **Colors** / **Theme** (Цвета / Тема) dropdown:
   - Select your desired theme (e.g., `Nord`, `Rosé Pine`, `Kanagawa Wave`, `GitHub Dark High Contrast`, or `Catppuccin Mocha`).
4. Ensure the **Widget style** is set to **Fusion** for optimal appearance.
5. Click **Close** — the stylesheet applies immediately (a launcher restart is recommended for complete icon caching).

---

### Platform Paths

Locate your launcher's `themes` directory based on your environment:

#### 🪟 Windows
- **Prism Launcher (Standard AppData):**  
  `%APPDATA%\PrismLauncher\themes\`  
  *(Press `Win + R`, paste the path, and hit `Enter`)*
- **Portable / MultiMC / Root Installation:**  
  `<Your_Launcher_Directory>\themes\`

#### 🐧 Linux
- **Flatpak (Standard on Steam Deck & Flathub):**  
  `~/.var/app/org.prismlauncher.PrismLauncher/data/PrismLauncher/themes/`
- **Native / Package Manager (AUR, DEB, RPM, AppImage):**  
  `~/.local/share/PrismLauncher/themes/`  
  *(For MultiMC: `~/.local/share/multimc/themes/`)*

#### 🍎 macOS
- **Prism Launcher:**  
  `~/Library/Application Support/PrismLauncher/themes/`
- **MultiMC:**  
  `~/Library/Application Support/MultiMC/themes/`

> [!TIP]
> **Universal Shortcut inside the Launcher:**  
> In Prism Launcher, you can go to **Settings** ➔ **User Interface** and click **Folder** (or open the launcher instance/data directory directly) to reveal the root where the `themes` directory lives.

---

## 🇷🇺 Инструкция по установке (Русский)

<details>
<summary><b>Нажмите, чтобы развернуть подробное руководство на русском</b></summary>

### Шаг 1. Получение файлов
- Скачайте архив репозитория: [Скачать ZIP](https://github.com/Sto3IV/MultiMC-themes/archive/refs/heads/main.zip).
- Распакуйте архив на свой компьютер. Внутри находится папка `themes`.

### Шаг 2. Размещение в лаунчере
Скопируйте папки нужных тем из `themes/` в системную директорию тем вашего лаунчера:

* **Windows:**  
  Нажмите `Win + R`, введите `%APPDATA%\PrismLauncher\themes` и нажмите `Enter`.  
  *(Если у вас портативная версия MultiMC или Prism — перейдите в папку с программой и откройте папку `themes`)*
* **Linux (Flatpak / Steam Deck):**  
  `~/.var/app/org.prismlauncher.PrismLauncher/data/PrismLauncher/themes/`
* **Linux (Обычная установка):**  
  `~/.local/share/PrismLauncher/themes/`
* **macOS:**  
  `~/Library/Application Support/PrismLauncher/themes/`

### Шаг 3. Активация
1. Откройте **Prism Launcher** (или **MultiMC**).
2. Зайдите в **Настройки** ➔ вкладка **Интерфейс пользователя** (User Interface).
3. В выпадающем меню **Цвета** (Colors) или **Тема** выберите добавленную тему:
   - `Nord`
   - `Rosé Pine`
   - `Kanagawa Wave`
   - `GitHub Dark High Contrast`
   - `Catppuccin Mocha`
4. Убедитесь, что в поле **Стиль виджетов** (Widgets) выбран `Fusion`.
5. Нажмите **Закрыть**. Тема применится сразу.

</details>

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
│   │       ├── check-partial.svg
│   │       ├── check.svg
│   │       └── radio-dot.svg
│   ├── kanagawa-wave/
│   │   ├── theme.json
│   │   ├── themeStyle.css
│   │   └── resources/ (*.svg)
│   ├── nord/
│   │   ├── theme.json
│   │   ├── themeStyle.css
│   │   └── resources/ (*.svg)
│   └── rose-pine/
│       ├── theme.json
│       ├── themeStyle.css
│       └── resources/ (*.svg)
├── screenshots/
│   ├── catpuccin.png
│   ├── github.png
│   ├── kanagawa.png
│   ├── nord.png
│   └── rose.png
├── LICENSE
└── README.md
```

> [!IMPORTANT]
> **Сохранение структуры путей (Relative URL Resolution):**  
> Стили Qt (`themeStyle.css`) разрешают векторные ресурсы (чекбоксы, стрелки, радиокнопки) по относительному пути `themes/<имя_папки>/resources/...`.  
> Не переименовывайте папки тем внутри вашей директории `themes/` (`kanagawa-wave`, `nord`, `rose-pine`, `github`, `catpuccin`), иначе векторные иконки в интерфейсе не загрузятся.

---

## 📜 License

Данный репозиторий распространяется под лицензией [Apache License 2.0](LICENSE).  
Отдельные цветовые палитры и исходные мотивы принадлежат их уважаемым сообществам и создателям:
- **Nord:** [Arctic Ice Studio](https://www.nordtheme.com/)
- **Rosé Pine:** [Rosé Pine Team](https://rosepinetheme.com/)
- **Kanagawa:** [rebelot / Kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim)
- **GitHub Dark High Contrast:** [GitHub Primer Primitives](https://primer.style/)
- **Catppuccin:** [Catppuccin Community](https://github.com/catppuccin/catppuccin)

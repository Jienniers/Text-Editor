# ✨ GS Text Editor

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Platform: Windows](https://img.shields.io/badge/Platform-Windows-blue)
![Status: No Longer Maintained](https://img.shields.io/badge/Status-No%20Longer%20Maintained-lightgrey)

A lightweight and customizable text editor built in **C#**, packed with features beyond a standard notepad! 📝

---

> ⚠️ **Project Status: Not Actively Maintained**
> This project is no longer being updated but remains public for reference and learning purposes. Some parts of the code may be outdated or include minor bugs.
<br>
🔴 Many major bugs have been reported in this project.

---

## 📚 Table of Contents

* [📌 Description](#-description)
* [🚀 Features](#-features)
* [🛠️ Prerequisites](#️-prerequisites)
* [🧰 Installation](#-installation)
* [🗂️ Project Structure](#️-project-structure)
* [🖼️ Screenshots](#-screenshots)
* [🤝 Contributing](#-contributing)
* [📝 License](#-license)
* [📬 Contact](#-contact)

---

## 📌 Description

**GS Text Editor** is a personal project created to go beyond the simplicity of Notepad. I wanted something that included utility tools like a calculator, text-to-speech, theme switching, and even music playback — all in one desktop application. 🎯

It served as a great way to deepen my understanding of **C#** and Windows Forms development while building something practical.

---

## 🚀 Features

✅ Create a new document window
<br>
✅ Open and edit existing text files
<br>
✅ Save and Save As functionality with multiple formats
<br>
✅ Print support with print preview 🖨️
<br>
✅ 🧮 Built-in Calculator
<br>
✅ 🗣️ Text-to-Speech engine
<br>
✅ 🖼️ Add and view images (image support included in print preview)
<br>
✅ 🌓 Theme toggle (Light/Dark mode)
<br>
✅ 🎵 Integrated Music Player
<br>
✅ 🧭 Customizable Menu and Toolbar
<br>
✅ ⏲️ Built-in Time Display
<br>
✅ ⚙️ Dedicated Settings Window for preferences

---

## 🛠️ Prerequisites

* 🪟 Microsoft Windows 10
* 🧰 Visual Studio 2022 or newer

---

## 🧰 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Jienniers/Text-Editor.git
   ```

2. **Open the solution**

   * Launch Visual Studio.
   * Navigate to `File > Open > Project/Solution` and open `GS_Text_Editor2.sln` in the root folder.

3. **Build the project**

   * Select `Build > Build Solution` or press `Ctrl+Shift+B`

4. **Prepare assets**

   * If the `Debug` folder doesn’t exist, run the build once to generate it.
   * Place the `Assets` folder inside the `Debug` folder.

5. **Run the application**

   * Press `F5` to launch in debug mode or `Ctrl+F5` for release mode.

---

## 🗂️ Project Structure

```
Text-Editor/
├── GS_Text_Editor2.sln         # Solution file
├── Form1.cs                    # Main UI logic
├── Calculator.cs               # Calculator tool
├── Find.cs                     # Find word window
├── GoTo.cs                     # Jump-to-line window
├── Replace.cs                  # Replace text tool
├── WordCout.cs                 # Word count dialog
├── Settings.cs                 # General settings management
├── SettingsAppearance.cs       # Theme & appearance configuration
```

---

## 🖼️ Screenshots

![App Screenshot](https://github.com/Jienniers/Text-Editor/blob/main/screenshots/SS1.png)
![App Screenshot](https://github.com/Jienniers/Text-Editor/blob/main/screenshots/SS2.png)
![App Screenshot](https://github.com/Jienniers/Text-Editor/blob/main/screenshots/SS3.png)

---

## 🤝 Contributing

This repo is archived, but you're welcome to explore, fork, or enhance for learning:

1. Fork this repository 🍴
2. Create your feature branch: `git checkout -b feature/AmazingFeature`
3. Commit your changes: `git commit -m 'Add some AmazingFeature'`
4. Push to the branch: `git push origin feature/AmazingFeature`
5. Open a Pull Request 🚀

---

## 📝 License

Released under the **MIT License**. See [LICENSE](LICENSE) for full details.

---

## 📬 Contact

Created & maintained by **[@Jienniers](https://github.com/Jienniers)**.
Feel free to open an issue for questions, suggestions, or bug reports.

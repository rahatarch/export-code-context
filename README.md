# Export Code Context

![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/rahathasan.export-code-context?color=blue&label=VS%20Marketplace) ![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/rahathasan.export-code-context?color=green) ![GitHub License](https://img.shields.io/github/license/rahatarch/export-code-context)

**Export code from any file or folder into a single, clean text file or your clipboard — ready to paste into an LLM (GPT, Gemini, Claude), use in documentation, or share for review.**

Instead of manually copying and pasting dozens of files, "Export Code Context" does it in a single right-click.

---

### Demonstration

![Demonstration GIF](https://raw.githubusercontent.com/rahatarch/export-code-context/main/export-code-context.gif)

---

## 🚀 Features

-   **One-Click Action**: Right-click any file or folder in the VS Code Explorer and select **"Code Context Action"**.
-   **Folder Export**:
    -   **Recursive Scanning**: Scans all subfolders to find every relevant file.
    -   **Auto-Ignore**: Skips common heavy directories like `node_modules`, `.git`, `dist`, and `build`.
    -   **Interactive Folder Selection**: A checklist lets you **deselect any subfolders** you want to exclude.
    -   **File Type Filtering**: A second prompt lets you choose which file extensions (e.g., `.ts`, `.py`, `.css`) to include.
    -   **Consolidated Output**: Combines the path and contents of every selected file into one organized `.txt` file, saved in the folder you clicked.
-   **Single File Copy**:
    -   **Clipboard Access**: Copies the file path and its full contents to your clipboard, formatted and ready to paste.
-   **Works Offline**: No internet connection required.

---

## 📖 How to Use

1.  In the VS Code Explorer, **right-click on any file or folder**.
2.  Select **Code Context Action** from the menu.
3.  Follow the interactive prompts for folder exports. Single-file actions are instant.

---

## 👨‍💻 Built By

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/rahatarch">
        <img src="https://raw.githubusercontent.com/rahatarch/export-code-context/main/assets/profile.png" width="120px;" alt="Rahat Hasan"/>
        <br />
        <sub><b>Rahat Hasan</b></sub>
      </a>
    </td>
    <td valign="top">
      <p>
        Founder of <a href="https://github.com/Akkhar-Labs">Akkhar-Labs</a> and builder of
        <a href="https://github.com/rahatarch/brud">Brud Code</a>. I built "Export Code Context" to solve a
        problem I hit every day: getting a project's code into an AI chat quickly and cleanly.
      </p>
      <div>
        <a href="https://github.com/rahatarch"><img src="https://img.shields.io/badge/GitHub-rahatarch-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
        <a href="https://www.linkedin.com/in/dev-rahathasan/"><img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
        <a href="mailto:rahathasan5773@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
      </div>
    </td>
  </tr>
</table>

---

## Release Notes

### 1.0.2
- Added "Meet the Creator" profile section.
- Updated documentation and links.

### 1.0.1
- Updated documentation and fixed the broken demonstration GIF link in the Marketplace listing.

### 1.0.0
- Initial release of **Export Code Context**.
- Universal command for handling both files and folders.
- Automatic ignore-list for common large directories.
- Interactive prompts for selecting subfolders and file extensions.

---

## 🤝 Contributing & Feedback

This is an open-source project. If you find a bug, have a feature request, or want to contribute, please [open an issue](https://github.com/rahatarch/export-code-context/issues) or submit a pull request.

## 📄 License

MIT — see the [LICENSE](https://github.com/rahatarch/export-code-context/blob/main/LICENSE) file for details.

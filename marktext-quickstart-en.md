# Mark Text Quick Start Guide — From Download to Your First Note

  

**Document Version**: v1.0  

**Software Version**: Mark Text v0.17.1  

**Target Audience**: First-time users of Mark Text  

**Date**: August 2026

  

---

  

## 1. Introduction

  

Mark Text is a free, open-source Markdown editor available on Windows, macOS, and Linux. Its key feature is WYSIWYG (What You See Is What You Get) — the way your text looks while editing is exactly how it will appear when exported. Unlike traditional Markdown editors, you don't need to switch between editing and preview modes.

  

This guide will walk you through downloading, installing, and writing your first note in Mark Text.

  

---

  

## 2. Download and Installation

  

### 2.1 Download Links

  

You can get Mark Text from:

  

- GitHub Releases: https://github.com/marktext/marktext/releases

- Official Website: https://marktext.app

  

The GitHub Releases page is recommended, as it lists all versions and release notes.

  

### 2.2 Choose the Right File

  

| Operating System | File to Download |

|---|---|

| Windows | `marktext-setup-x.x.x.exe` |

| macOS | `marktext-x.x.x.dmg` |

| Linux (Debian/Ubuntu) | `marktext_x.x.x_amd64.deb` |

| Linux (Universal) | `marktext-x.x.x.AppImage` |

  

If you are unsure about your system type, choose the x64 version.

  

## 2.3 Installation Steps

  

Taking Windows as an example:

  

1. Double-click the downloaded `.exe` installation file.

2. In the pop-up installation wizard, click **Next**.

3. Select the installation path; it is recommended to keep the default settings.

4. Click **Install** and wait for the progress bar to finish.

5. After installation, check **Run Mark Text** and click **Finish**.

  

After successful installation, Mark Text will launch automatically.

  

> Download page reference:

> [https://github.com/marktext/marktext/releases/latest](https://github.com/marktext/marktext/releases/latest)

  

## 3. First Launch and Interface Overview
  

When you open Mark Text, you will see a clean editing interface. The main areas are:

  

| Area | Location | Purpose |

|---|---|---|

| Editor | Center | Write and edit Markdown content |

| Toolbar | Top | Menu options: File, Edit, Insert, View |

| File Tree Panel | Left (optional) | Browse and manage local folders |

| Status Bar | Bottom | Shows line number, word count, etc. |

  

To show the file tree panel, go to **View → Show File Tree** in the menu.

  

---

  

## 4. Quick Start: Write Your First Note

  

### 4.1 Create a New File

  

- Menu: **File → New**

- Shortcut: `Ctrl + N` (Windows/Linux) or `Cmd + N` (macOS)

  

### 4.2 Add Headings

  

Use `#` followed by a space at the beginning of a line. The number of `#` symbols indicates the heading level:


# Heading 1
## Heading 2
### Heading 3
#### Heading 4

  

### 4.3 Add Lists

  

**Unordered list**: Use `-` or `*` followed by a space

- Requirements Document
- Operation Manual
- Meeting Minutes



**Ordered list**: Use `1.` followed by a space

1. Step 1: Open a file 
2. Step 2: Create a new file 
3. Step 3: Start writing 


### 4.4 Bold and Italic

  

- **Bold**: Wrap text with two asterisks: `**bold text**`

- *Italic*: Wrap text with one asterisk: `*italic text*`

  

### 4.5 Insert Links

  

Use square brackets followed by parentheses:

- Baidu: [Baidu](https://www.baidu.com)

- GitHub: [GitHub](https://github.com)


  
### 4.6 Insert Images

  

- Drag and drop an image file into the editor.

- Or use the shortcut `Ctrl + Shift + I` (Windows/Linux) / `Cmd + Shift + I` (macOS).

  

### 4.7 Save Your File

  

- Menu: **File → Save**

- Shortcut: `Ctrl + S` (Windows/Linux) or `Cmd + S` (macOS)

- The file extension is `.md`. It is recommended to save it in a dedicated folder.

  

---

  

## 5. Useful Features

  

### 5.1 Focus Mode

  

When enabled, only the current line stays highlighted; other lines dim. This helps you concentrate.

  

- Menu: **View → Focus Mode**

- Shortcut: `Ctrl + Shift + L` (Windows/Linux) or `Cmd + Shift + L` (macOS)

  

### 5.2 Typewriter Mode

  

When enabled, the cursor always stays in the center of the screen. Ideal for long writing sessions.

  

- Menu: **View → Typewriter Mode**

  

### 5.3 Export to PDF or HTML

  

- Menu: **File → Export → PDF**

- Menu: **File → Export → HTML**

  

Exported PDF files retain all styles shown in the editor.

  

### 5.4 Switch Theme

  

Mark Text comes with Light and Dark themes.

  

- Menu: **View → Theme → Light**

- Menu: **View → Theme → Dark**

  

The Dark theme reduces eye strain when working at night.

  

### 5.5 Math Formula Support

  

Mark Text supports LaTeX math syntax:

  

- Inline formula: wrap with single dollar signs, e.g., `$E=mc^2$`

- Display formula: wrap with double dollar signs, e.g., `$$\int_a^b f(x)dx$$`

  

---

  

## 6. Frequently Asked Questions

  

### Q1: I closed a file without saving. Can I recover it?

  

Mark Text does not have auto-save by default. If you close a file without saving, the content will be lost. We recommend getting into the habit of pressing `Ctrl + S` (or `Cmd + S`) frequently. If a prompt appears when closing, choose **Save**.

  

### Q2: How do I open an existing .md file?

  

There are three ways:

  

1. Menu: **File → Open**, then select the file.

2. Shortcut: `Ctrl + O` (Windows/Linux) or `Cmd + O` (macOS).

3. Drag and drop the `.md` file into the Mark Text window.

  

### Q3: Can I change the editor font?

  

Currently, Mark Text does not support changing fonts directly from the interface. Advanced users can modify the configuration file manually. For most users, the default font works well.

  

### Q4: Does Mark Text support Chinese?

  

Yes. Mark Text fully supports Chinese input and display. You can write in Chinese without any issues.

  

---

  

## 7. Additional Resources

  

- Mark Text GitHub Repository: https://github.com/marktext/marktext

- Markdown Guide: https://www.markdownguide.org/basic-syntax/

- Mark Text Documentation: https://docs.marktext.app/

  

---

  

> This document is based on Mark Text v0.17.1. Software updates may cause slight differences in interface or functionality.
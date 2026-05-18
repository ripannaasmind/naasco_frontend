# Responsive Admin Dashboard - Naascco

## Project Overview

This is a modern, responsive admin dashboard UI built with HTML, CSS (Vanilla + Tailwind), and JavaScript. It features a professional layout with a focus on clean aesthetics and responsive design.

## Folder Structure

The project follows a clean, standalone structure without the need for `node_modules` or `npm`.

```
naasco/
├── index.html                 # Main dashboard page
├── tailwindcss.exe           # Standalone Tailwind CLI (v3.4.17)
├── tailwind.config.js        # Tailwind configuration file
├── .gitignore                # Git configuration
├── README.md                 # Project documentation
├── pages/                    # Additional dashboard pages
└── assets/                   # Static assets folder
    ├── css/
    │   ├── style.css         # Source CSS with @tailwind directives
    │   └── tailwind.css      # Compiled and ready-to-use CSS
    ├── js/
    │   └── main.js           # Main JavaScript file
    └── images/               # Image assets
```

## Tailwind CSS Development

## Standalone CLI: Use Tailwind CSS without Node.js

This project is built using the **Tailwind CSS Standalone CLI**. This means you can develop, watch, and build your CSS **without installing Node.js, npm, or any other dependencies.**

### How it works:
1.  **Direct Execution**: We use a pre-compiled `tailwindcss.exe` binary.
2.  **No `node_modules`**: Your project directory stays clean and lightweight.
3.  **Portable**: You can move this project to any computer and start developing immediately just by having the executable.

### How to Install tailwindcss.exe
If you have cloned this repository and `tailwindcss.exe` is missing (as it is excluded from Git), follow these steps:
1.  **Download**: Go to the [Tailwind CSS Releases](https://github.com/tailwindlabs/tailwindcss/releases) page.
2.  **Select Binary**: Download the `tailwindcss-windows-x64.exe` (for Windows).
3.  **Setup**: Place the downloaded file in the project root folder and rename it to `tailwindcss.exe`.

---


### How to use the CLI
Now you can use it just like the npm-distributed CLI tool. Run these commands in your project root:

```powershell
# Create a tailwind.config.js file (Optional)
.\tailwindcss.exe init

# Start a watcher to recompile on every save
.\tailwindcss.exe -i ./assets/css/style.css -o ./assets/css/tailwind.css --watch

# Compile and minify your CSS for production
.\tailwindcss.exe -i ./assets/css/style.css -o ./assets/css/tailwind.css --minify
```

---

## Features

- **Fully Responsive**: Optimized for Desktop, Tablet, and Mobile devices.
- **Standalone Build**: Zero dependencies on Node.js/NPM.
- **Modern UI**: Clean navigation, stats cards, and interactive components.
- **Clean Structure**: Separated source styles and compiled assets.

## How to Run
1. Open `index.html` directly in any modern browser.
2. (Optional) Use a local server like VS Code "Live Server" for the best experience.

---
*Last updated: May 2026*

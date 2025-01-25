# Content Protector JS  

A lightweight and efficient JavaScript plugin to safeguard your website's content from being copied or stolen. Simply include a single JS file, and the plugin will disable all common methods of copying content.  

## ✨ Key Features  

- **Text Selection Blocking**  
  Prevent users from selecting or highlighting text on your website.  

- **Developer Tools Disabling**  
  Restrict access to browser developer tools to prevent code inspection.  

- **Hotkeys Blocking**  
  Disable popular keyboard shortcuts used for copying, saving, or viewing source code.  

- **Context Menu Blocking**  
  Prevent users from right-clicking to open the context menu.  

### 🛠️ Detailed Blocking Options  
- **Text Selection and Highlighting**: Disabled via mouse.  
- **Developer Tools**: Prevent access to tools like `Inspect Element`.  
- **Keyboard Shortcuts**:  
  - `Select All`: Disabled (`Ctrl+A`/`Command+A`)  
  - `Copy, Cut, Paste`: Disabled (`Ctrl+C`, `Ctrl+X`, `Ctrl+V`/`Command+C`, `Command+X`, `Command+V`)  
  - `Save or Save As`: Disabled (`Ctrl+S`/`Command+S`)  
  - `View Source`: Disabled (`Ctrl+U`/`Command+U`)  
  - `Print Page`: Disabled (`Ctrl+P`/`Command+P`)  
- **Image Dragging**: Disabled via mouse.  
- **Right-Click Context Menu**: Disabled on all elements.  

## 🚀 Easy Setup  

1. Add the following file to your website:  
   ```html
   <script src="/dist/content-protector.js"></script>

# 🐍 Installation & Setup (pyRevit)

## 📂 Installation
1.  **Locate your pyRevit Extensions folder.**
    *   *Default:* `%appdata%\pyRevit\Extensions\`
    *   *Or:* Create a custom folder (e.g., `C:\MyRevitScripts`) and add it in **pyRevit Settings > Custom Extension Folders**.
2.  **Create the required structure:**
    *   `MyTools.extension` → `MyTab.tab` → `Electrical.panel`
3.  **Deploy the scripts:**
    *   Copy the script folders from this repo (e.g., `AutoTag`) into the `Electrical.panel` folder.
    *   **Rename** the folders to add the `.pushbutton` suffix (e.g., `AutoTag.pushbutton`).
4.  **Reload:** Click **pyRevit > Reload** in Revit.

## ⚠️ Configuration
**Every project is different.** You MUST configure the scripts before use.
1.  Open the `script.py` file (or Alt+Click the button).
2.  Edit the **USER CONFIGURATION** section at the top.

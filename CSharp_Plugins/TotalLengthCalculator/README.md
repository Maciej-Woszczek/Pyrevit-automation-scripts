# Total Length Calculator (Revit 2026)

A compiled C# plugin that calculates the total length of selected Conduits and Cable Trays.

## 📁 Repository contents
- `TotalLengthCalculator.sln` – open this in Visual Studio.
- `TotalLengthCalculator.csproj` – project configuration (target framework, references).
- `Command.cs` – source code implementing `IExternalCommand`.
- `CalculateTotalLength.addin` – manifest template (edit `<Assembly>` path before installing).

## 📥 Installation

1.  **Open the Solution:**
    *   Open `TotalLengthCalculator.sln` in Visual Studio 2022.
2.  **Build:**
    *   Press `Ctrl + Shift + B` to build the solution.
    *   *Note: Ensure you have Revit 2026 installed, or update references to your version.*
3.  **Configure Manifest:**
    *   Open `CalculateTotalLength.addin` (found in Revit2026Plugin folder).
    *   Edit the `<Assembly>` path to point to your compiled DLL (usually in `bin/Debug/net8.0-windows/`).
4.  **Install:**
    *   Copy the `.addin` file to `%appdata%\Autodesk\Revit\Addins\2026\`.

## 🛠️ Requirements
*   Revit 2026
*   .NET 8.0 SDK

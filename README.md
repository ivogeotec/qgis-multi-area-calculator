# QGIS Multi-Area Calculator (PyQGIS)

A PyQGIS processing script that automates the calculation of areas in multiple units. It adds three new fields to your polygon layer attributes: square meters (sqm), square kilometers (sqkm), and hectares (ha).

## Features
- Integrates directly into the QGIS Processing Toolbox.
- Automatically creates and populates three area columns.
- Preserves all original attributes from the source layer.

## Compatibility
- Tested and verified on **QGIS 3.22.8-Białowieża**.
- Compatible with most QGIS 3.x versions.

## How to Use

Follow these steps to run the script inside your QGIS:

1. **Open the Python Console:**
   - Go to the top menu: `Plugins` > `Python Console` (or press `Ctrl+Alt+P`).
2. **Open the Script Editor:**
   - Click on the **Show Editor** icon (the notepad and pencil symbol) in the Python Console toolbar.
3. **Load the Code:**
   - Copy the entire code from the `multiple_area_calculator.py` file in this repository.
   - Paste it into the blank Editor window in QGIS.
4. **Execute the Script:**
   - Click the green **Run Script** button (the "play" icon) at the top of the editor.
5. **Configure and Run:**
   - A window titled **"Multi-Area Calculator (sqm, sqkm, ha)"** will appear.
   - **Input Layer:** Select the polygon layer you want to analyze.
   - **Output Layer:** Choose to save to a file or create a temporary layer.
   - Click **Run**.

## Requirements
- **Important:** Ensure your input layer is using a **Projected Coordinate Reference System (CRS)**, such as UTM, to ensure the area calculations are accurate in meters.

---
Developed by [ivogeotec]

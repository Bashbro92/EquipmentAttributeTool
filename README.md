# EquipmentAttributeTool - For Tarisland

This repository contains a Google Apps Script designed to enhance the management of equipment attributes within Google Sheets. The script enables interactive and dynamic handling of attributes through checkboxes, automating the calculation and display of attribute totals and their respective percentages. It ensures that selections are mutually exclusive where required, maintaining logical consistency across equipment types.

## Features

- **Dynamic Checkbox Insertion:** Adds interactive checkboxes across various equipment categories to enable attribute selection directly within the spreadsheet.
- **Automatic Calculations:** Calculates and updates attribute totals and converts these totals to percentages for attributes like Crit Chance, Cooldown, and Omni.
- **Mutual Exclusivity:** Implements logic to ensure that attributes such as +140 and +210 of the same type cannot be selected simultaneously on the same piece of equipment.
- **Node Level Management:** Adds dropdowns for managing Node Levels and calculates their impact on attributes.
- **Bonus Calculation:** Provides checkboxes to apply a 50% bonus to selected attributes and updates the flat stat and converted percentage values accordingly.

## How to Use

To integrate this script into your Google Sheets for managing game-related equipment attributes, follow these steps:

1. **Open Google Sheets:** Navigate to the Google Sheets where you want to manage equipment attributes.
2. **Access Apps Script:** Go to `Extensions` > `Apps Script`.
3. **Replace Script:** Clear any existing code in the Apps Script editor, paste the code from this repository, and save.
4. **Reload Sheet:** Refresh your Google Sheets to activate the script.

## Setup Example

Here's a simple example to set up your sheet correctly:

- **Column A:** List attributes (+140 Intelligence, +210 Intelligence, etc.).
- **Columns B-O:** Correspond to different equipment pieces (Helmet, Armor, etc.), with checkboxes inserted as per the script configuration.
- **Node Levels:** Configure Node Levels for attributes like Crit. Chance, Omni, and Cooldown in rows 19-30 with dropdowns in Column B.
- **50% Bonus:** Use checkboxes in Column C to apply a 50% bonus to selected attributes.
- **Flat Stat and Converted %:** Columns D and E will display the calculated flat stat and converted percentage values based on the Node Level and 50% bonus selections.

### Example Configuration:

- **Attributes (Rows 19-30):** 
  - Crit. Chance, Omni, Cooldown attributes listed.
  - Node Level dropdowns in Column B.
  - 50% Bonus checkboxes in Column C.
  - Flat stat values calculated and displayed in Column D.
  - Converted percentage values displayed in Column E.

## Contributing

Contributions to enhance or extend the functionality of this script are welcome. Please feel free to fork this repository, make your changes, and submit a pull request.

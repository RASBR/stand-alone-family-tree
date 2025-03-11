# Stand Alone Family Tree

A stand-alone web page to display family tree using EXCEL, JSON, and an HTML page.

## Instructions

1. Open the Excel workbook family_tree.xlsx and go to the `Original_data` sheet.
1. In the table in sheet `Original_data` Enter your data as per the sample data in the table.
1. On `Data` menu press `Refresh All`.
1. On Sheet `FinalJSON` copy the cell with the JSON data.
1. Open the file d:\family-tree\stand-alone-family-tree\family_tree.json and paste the JSON inside. Save and Close. ➔ JSON File
1. Open the file d:\family-tree\stand-alone-family-tree\family_tree.html in your browser. ➔ HTML File
1. Press the `Load Family JSON` button, browse to the folder, and select the JSON file.
1. If the data has no errors, the family tree will display.

### JSON Formatter:

Use [![img](https://jsonformatter.org/img/logo.webp =32x)](https://jsonformatter.org/){target=\_blank} to view JSON in a user friendly format AND CHECK FOR ERRORS.

### Project Folder Content:

1. **family_tree.xlsx:** Enter your data in an Excel table, and it will be converted into JSON data.
1. **family_tree.json:** The JSON data that will be loaded to the web page that will display the family tree.
1. **family_tree.html:** The web page that we will load the JSON data into and it will display the family tree.

# Attribution

The family tree is being represented using the [Family-Chart](https://raw.githubusercontent.com/donatso/family-chart/HEAD/examples/logo.svg) npm package created by ![img](https://www.npmjs.com/npm-avatar/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJhdmF0YXJVUkwiOiJodHRwczovL3MuZ3JhdmF0YXIuY29tL2F2YXRhci9lMzE2N2EwZDU3NWY0MzMzYmIxNzlmYmRhNWEwZjIyZj9zaXplPTEwMCZkZWZhdWx0PXJldHJvIn0.Kn8I9ctK855enR9gwp1wq5mwCUEyTHo8_UC114X64tw =32x) Donatso

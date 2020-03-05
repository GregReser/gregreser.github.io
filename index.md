## Embedded Metadata Export-Import Plugin for Adobe Bridge
This is a Javascript plugin for [Adobe Bridge](https://www.adobe.com/products/bridge.html) CS5 and higher that allows the user to export and import embedded XMP metadata from media files.

Supported file types: ai, avi, bmp, dng, flv, gif, indd, indt, jpg, mp2, mp3, mp4, mov, pdf, png, psd, swf, tiff, wav, wma, wmv

This plugin is written in [Adobe ScriptUI](https://estk.aenhancers.com/index.html) and utilizes the Adobe Bridge JavaScript object model

## Main features
 - Export-import from select file(s) or from an entire folder (with option to include all subfolders)
 - Export-import metadata in tab-delimited text files
 - Define which fields to export-import
   - Create reusable custom lists of fields
   - Use established schemas (IPTC, Dublin Core, VRA) - either the entire schema or select fields
   - Use custom schemas and namespaces
   - Combine fields from different schemas
   - Specify field name/column header (allows synchronization with local field names)
   - Specify the order of the fields/column headers

## Before you begin
Backup your files first
	
IT IS HIGHLY RECOMMENDED THAT YOU BACKUP YOUR IMAGE FILES BEFORE USING THIS OR ANY BRIDGE PLUGIN.	
THERE ARE NO WARRANTIES FOR LOSS OR UNINTENDED MODIFICATION OF DATA.*

<a href="https://github.com/GregReser/Customizable_Export-Import/archive/release/user_customizable_export_import.zip">[[Images/download_button_003.png|ALT TEXT]]</a>
version 2020-01-28

## Installation
 1. Start Adobe Bridge
 2. Go to Bridge Preferences
 
    Windows
      - Go to Edit --> Preferences --> Startup Scripts
    
    Mac:
      - Go to Adobe Bridge --> Preferences --> Startup Scripts
 3. Click "Reveal My Startup Scripts".  This will open the correct folder
 4. In this folder, copy the the downloaded file "user_customizable_export_import.jsx"
 5. Close the folder
 6. Quit Bridge
 7. Start Bridge
 8. When prompted, confirm the installation of "user_customizable_export_import"

## Open the plugin in Adobe Bridge
  1. Locate the menu "Custom Metadata at the top of the Bridge window (to the right of "Help")
  2. Click "Metadata Export-Import" on the dropdown menu
  3. The first time you open the plugin, you have to set up the fields you want to export/import. You will see the text "Fields: UNDEFINED,  click Edit →"

     After clicking the "Edit" button, you will see the Customize Fields window.

     See [Customize Fields](https://github.com/GregReser/Customizable_Export-Import/wiki/Customize-fields) for instructions


# OWrite Document Manager

The library implements a working document manager to demonstrate the features of the Brainy Data external components OWrite, PDFDevice and OSpell2. The document manager is used by Brainy Data to manage external component documentation. The library demonstrates many features such as desktop and javascript document management and editing, desktop label printing, data merging, mailing, PDF and HTML production, library-wide spell checking, and much more.

## Additional Requirements

To build the library you will require the following external components by Brainy Data; OWrite (v4.1), jsOWrite (v4.1), PDFDevice (v3.3) and OSpell2 (v3.2.4). If you do not have them, demo versions are available at https://www.brainydata.com/demos. Furthermore, additional files and libraries are required which can also be downloaded from the same location.

The specific downloads are:

https://www.brainydata.com/demos/software/owrite_document_manager.zip
https://www.brainydata.com/demos/software/jsowrite_demo_software_mac.zip
https://www.brainydata.com/demos/software/jsowrite_demo_software_win.zip

These downloads provide all files required for both desktop and javascript implementations. Please follow the accompanying installation notes.

Please also refer to the online documentation for further information.
https://www.brainydata.com/supportpublic/documentation.htm

The latest OSpell2Interface.lbs library can be downloaded from a separate Github repository within this organization.

## Contents

### OWriteDocumentManager

This folder contains the JSON source files for the Omnis library in Github.

To restore these files in Omnis Studio, click 'Libraries' in the Studio Browser, then click 'New Lib from JSON'. In the import dialog, navigate to this source folder (containing library.json), then specify a different location for the new Library. Click on Import and open the library in the Studio Browser.

Before importing, ensure you have loaded the OSpell2 library and installed the required external components.

To test your builds, simply replace the library with the identical name in the downloaded folders, with the ones you have just build.

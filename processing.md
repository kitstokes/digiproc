# Processing Scans

This section contains instructions on how to process files once a project is fully scanned.

Contents of this section:

1. [Images]
2. [Documents]
3. [How to Apply OCR]
4. [How to Reduce File Size]
5. [Create Photoshop Batch Actions]

---

## Images

There are two steps to successfully process scanned images and documents:

1. Convert files from **TIFF** to **JPEG**.
2. Crop and convert files to low resolution **JPEG**. 

        Before you begin:
        
        Go to the folder for this scanning project. Check for two folders labeled **access jpeg** and **lowres jpeg**. Create the folders if they do not exist. 

### Convert files from TIFF to JPEG

1. Open Photoshop. Go to File > Automate > Batch.

*

2. Select the action **tiff>jpeg**. If you do not have this action on your machine, ask CDIL staff for assistance.

3. Change the settings in the **Batch** window to the following:

- **Action**: select the **tiff>jpeg** action.
- **Source**: select the **tiff** folder for your scanning project.
- **Destination**: select the **access jpeg** folder for your scanning project.

*

4. Click **OK**. Wait for Photoshop to complete the action.

5. Check that the files saved to the correct folder. 

### Crop and convert files to low resolution JPEGs:

#### Crop:

1. Go to the **access jpeg** folder. 
2. Open the first image in Photoshop.
3. Crop out the color bar. Crop the image as close to the edges of the item as possible while getting rid of the entire background. 
4. If needed, balance images using the Levels tool in Photoshop.
5. Save and close the image when finished.
6. Complete steps 1-5 until all files have been cropped. Then, continue with steps below. 

#### Convert:

7. In Photoshop, open the **Batch** window and change the settings to the following:

- **Action**: select the **lowres jpeg** action.
- **Source**: select the **access jpeg** folder for your scannign project.
- **Destination**: select the **lowres jpeg** folder for your scanning project.

*

9. Click **OK**. Wait for Photoshop to complete the action.
10. Check that the files saved to the correct folder. 


## Documents

This section of the Processing Guide explains:

- How to convert JPEG scans into PDFs using Adobe Acrobat.
- How to combine multiple PDFs into one document.

#### Convert JPEG scans to PDFs using Adobe Acrobat:

1. Open the **lowres jpeg** folder for your scanning project.
2. Select the item(s) you would like to convert.
3. Right-click the selected item(s). From the context menu choose one of the following:
        - **Convert to Adobe PDF** if converting only one file.
        - **Combine supported files in Acrobat if converting files that need to be combined into one (like a multi-page letter or document).
        
        *
        
4. After you choose an option, a new window will open. Click **Combine** in this window.
5. Wait for Acrobat to open your files.
6. Find **Tools** in the top-right corner of the screen. Select **Recognize Text** and then **In this file**. 

*

7. Wait for Acrobat to complete the command. If working with a multi-page document, you will know it's finished when it ends back at the first page. 
8. Save the document as a PDF following the naming rules established in the [File Naming] section.

## Other Processes


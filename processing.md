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
        - **Combine supported files in Acrobat** if converting files that need to be combined into one (like a multi-page letter or document).
        
        *
        
4. After you choose an option, a new window will open. Click **Combine** in this window.
5. Wait for Acrobat to open your files.
6. Find **Tools** in the top-right corner of the screen. Select **Recognize Text** and then **In this file**. 

*

7. Wait for Acrobat to complete the command. If working with a multi-page document, you will know it's finished when it ends back at the first page. 
8. Save the document as a PDF following the naming rules established in the [File Naming] section.

## Other Processes

This section explains how to:

- Extract text in documents through OCR
- Batch reduce file size
- Create actions in Photoshop

### Text Recognition with Adobe Acrobat Pro DC OCR

Optical Character Recognition (OCR) is a technology that recognizes text in documents and images to make them machine readable. Using Adobe Acrobat Pro DC, you can extract text through OCR on a single or multiple documents with just a few clicks.

#### OCR on a Single Document

Follow this process to extract text through OCR on one document.

1. Open a PDF in Adobe Acrobat Pro DC.
2. Select **Scan & OCR** from the tool menu on the right side of the application window.

*

3. Select **Recognize Text** from the toolbar at the top of the screen. Choose **In This File** from the dropwdown menu:

*

4. In the **Recognize Text** window, check that the settings are correct:

- **Document Language**: language in whcih the document is written. Most documents you work with in the CDIL will be in English (US).
- **Output**: Searchable Image
- **Downsample To**: 300 dpi

*

5. Click **OK** and begin the process.
6. Save and close the file when the process finishes.

#### Batch OCR on Multiple Documents

Follow this process to extract text through OCR on multiple documents at one time.

1. Open Adobe Acrobat Pro DC. Click the **Tools** menu in the top-left corner.

*

2. Click **Scan & OCR** in the **Create & Edit** tool group.
3. Click **Or recognize text in multiple files** under the blue Start button. 

*

4. Click **Add Files...** to manually add files or drag and drop files into the window.

*

5. Output options:
- **Target folder**: choose to save the items to the same folder as the originals or to save them to a new folder.
- **File naming**: choose to keep the same file name or input a tet or number string before or after the original name.
6. Click **OK**. Check the **General Settings** dialog that opens. Set PDFs to **300 dpi** to reduce file size issues later.
7. Click **OK** to start the OCR process.


### Batch Reduce File Size

Follow this process to reduce the file size of many PDFs at once using Adobe Acrobat Pro DC. 

1. In Acrobat, open the **File** menu and select **File** > **Save As Other** > **Reduce Size PDF**.
2. In the **Arrange documents** dialog box, add files by selecting **Add Files...** or drag and drop files into the window. Click **OK**.

*

3. In the next window, choose **Retain existing** for the compatibility options and click **OK**.
4. Output options:
- **Target folder**: choose to save the items to the same folder as the originals or to save them to a new folder.
- **File naming**: choose to keep the same file name or input a text or number string before or after the original name.

*

5. Click **OK** to start the process.

### Creating Batch Actions in Photoshop

Follow these steps to learn how to make the two Photoshop actions required for the CDIL digitization process.

#### Action: tiff > access jpep

**Before you begin**:

Open Photoshop. Is the **Action Window** visible? 
Make sure by selecting the **Window** menu at the top of the screen and clicking **Actions**. 

1. Open one of the tiff files from your scanning project in Photoshop. 
2. In the **Action Window**, click on the **Create New Action** button. It is a small square with a plus sign. 

**

3. In the **New Action** window, set the name of the new action to tiff > jpeg.

*

4. Click **Record**. 
5. In the **File** menu select **Save As...**. Navigate to the **access jpeg** folder for your scanning project.
6. Choose **JPEG** from the **Save as** type drop down menu. Click **Save**. 

*

7. In the **JPEG Options** window change the **Quality** value to 10 and click **OK**.

*

8. Select **Close** from the **File** menu or use Ctrl + W.

*

9. Click the square **Stop** icon in the Action Window.

*

#### Action: access jpeg > lowres jpeg

**Before you begin**:

Open Photoshop. Is the **Action Window** visible? 
Make sure by selecting the **Window** menu at the top of the screen and clicking **Actions**. 

1. Open one of the **access jpeg** files from your scanning project. 
2. In the **Action Window**, click on the **Create New Action** button. It is a small square with a plus sign. 

*

3. In the **New Action** window, set the name of the new action to **lowres jpeg**. 

*

4. Press **Record**.
5. In the **File** menu select **Save As...**. Navigate to the **lowres jpeg** folder for your scanning project.
6. Choose **JPEG** from the **Save as** type drop down menu. Click **Save**.

*

7. In the **JPEG Options** window change the **Quality** value to 8 and click **OK**.

*

8. Select **Close** from the **File** menu or use Ctrl + W.

*

9. Click the square **Stop** icon in the Action Window to stop the recording. 

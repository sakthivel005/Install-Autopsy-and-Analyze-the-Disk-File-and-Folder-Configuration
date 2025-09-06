# Install Autopsy and Analyze the Disk File and Folder Configuration

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM

<img width="577" height="785" alt="Screenshot 2025-08-22 151258" src="https://github.com/user-attachments/assets/e506f435-8734-46f0-8ad7-68be3fe56226" />


## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:

#### Name - Sakthivel R
#### Reg. No. - 212222100044

### CREATING A DISK PARTITION:

#### Step 1: Open File Manager
```
Right-click This PC → Click Show More Options.

Select Manage.
```

#### Step 2: Access Disk Management
```
In the new window, select Disk Management.
```

<img width="285" height="526" alt="437154922-f5f69c3b-f2d9-4171-b5cc-fa4a589597d5" src="https://github.com/user-attachments/assets/9cc6f801-862d-4895-aa0d-f113daabf114" />


#### Step 3: Shrink the C Drive to Allocate Space
```
Locate C: drive → Right-click → Select Shrink Volume.

Enter the amount of memory to allocate for the new disk.

Click Shrink.
```

<img width="1919" height="1079" alt="Screenshot 2025-09-06 142216" src="https://github.com/user-attachments/assets/a70beea6-9e8b-434f-91eb-31a37f8e1cea" />



#### Step 4: Create a New Volume
```
Right-click on the newly unallocated space → Select New Simple Volume.

Follow the wizard and assign a disk name.

Click Finish to complete the process.

The new Disk Partition is created
```


<img width="1919" height="1079" alt="Screenshot 2025-09-06 141839" src="https://github.com/user-attachments/assets/c9b86285-f3ef-48bb-b1b7-d99852360075" />



### ANALYSING FILES USING AUTOPSY:

#### Step 1: Create a Case
```
Enter a case name and select a location to store the case data.

Provide a case number and investigator details if required.
```

<img width="1919" height="1079" alt="Screenshot 2025-09-06 142818" src="https://github.com/user-attachments/assets/8966c252-42d5-4174-8e2f-16187315bc33" />



#### Step 2: Add a Data Source
```
Click "Add Data Source" and choose the type:

Select the data source and let Autopsy process it.
```

#### Step 3: File Analysis

##### Application
<img width="1919" height="1018" alt="Screenshot 2025-09-04 133502" src="https://github.com/user-attachments/assets/3153d6e7-b49f-4124-817d-5554948ba04c" />


<img width="1919" height="1079" alt="Screenshot 2025-09-04 133534" src="https://github.com/user-attachments/assets/80e8201b-e0da-45bb-b750-9935d8e3aed5" />

##### File Metadata

<img width="1915" height="1024" alt="Screenshot 2025-09-04 133523" src="https://github.com/user-attachments/assets/6b9e8325-0f4e-421a-b74c-684edc3d673d" />



##### Click OS Account.


<img width="1910" height="1079" alt="Screenshot 2025-09-04 133546" src="https://github.com/user-attachments/assets/f205dc35-1ba1-4dd0-b927-a460054776b6" />


### GENERATE REPORT:

<img width="1919" height="1079" alt="Screenshot 2025-09-04 133727" src="https://github.com/user-attachments/assets/44f0ac4f-023e-4b0f-9c79-4cd7c4c75acf" />


## RESULT:

Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.

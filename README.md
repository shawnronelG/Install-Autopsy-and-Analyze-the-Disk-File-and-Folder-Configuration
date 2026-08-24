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
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
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
File and Folder Configuration Analysis Results
<img width="1917" height="1077" alt="image" src="https://github.com/user-attachments/assets/585241f2-10be-4967-972e-d00b7afdef08" />
<img width="1600" height="901" alt="WhatsApp Image 2026-08-24 at 23 00 04" src="https://github.com/user-attachments/assets/eb6047a2-3e4d-45ab-a042-e368245856df" />
<img width="1600" height="893" alt="WhatsApp Image 2026-08-24 at 23 10 25" src="https://github.com/user-attachments/assets/8ea2086b-77be-4d89-86d3-38d8050f4c98" />
<img width="1600" height="898" alt="WhatsApp Image 2026-08-24 at 23 18 24" src="https://github.com/user-attachments/assets/7af21c2d-8827-48b2-aad2-216324a5b298" />
<img width="1600" height="898" alt="WhatsApp Image 2026-08-24 at 23 18 39" src="https://github.com/user-attachments/assets/ba8e28ae-b0da-401d-bc8f-adf5af80fdc8" />
<img width="1600" height="898" alt="WhatsApp Image 2026-08-24 at 23 20 38" src="https://github.com/user-attachments/assets/35907896-0fa5-47b7-8fb3-b197be611441" />
<img width="1600" height="898" alt="WhatsApp Image 2026-08-24 at 23 20 38" src="https://github.com/user-attachments/assets/4b10046f-6ff0-434b-9e52-6d531e12ab5e" />
<img width="1600" height="898" alt="WhatsApp Image 2026-08-24 at 23 24 50" src="https://github.com/user-attachments/assets/80187e79-9d7b-47f1-8920-7c401324ce98" />


## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.

# Invoice Processing Bot - UiPath Project

This project is an automated invoice processing bot built using UiPath. The bot downloads invoice attachments from emails, saves it into a specified folder, extracts data from the invoice file e.g invoice date,number total etc, and uploads it to a OneNote application. 

## Getting Started

Follow these steps to download, configure, and run the project on your local machine.

---

### **1. Prerequisites**

- **UiPath Studio:** Ensure you have UiPath Studio installed on your system. You can download it [here](https://www.uipath.com/start-trial).
- **OneNote Application:** Install and configure the OneNote application on your machine.

---

### **2. Downloading the Project**

1. Download Main File:
 You can directly download the Main.xml file from this repository.

### Configuring the Project
1. Open UiPath Studio and go to the "Open a Local Project" option.
2. Navigate to the folder where the Main.xml file is located and select it.
3. Editing File Paths:

- The project uses specific file paths for saving attachments and logs. Update these paths to suit your system.
- Open the Main.xml file in UiPath Studio, and edit the following variables in the workflow:
- Email Attachment Path: Path where email attachments are stored.
- OneNote Application Path: Update this if the OneNote installation directory differs.
- Ensure the paths are accessible and have the required permissions.
- Run the project.

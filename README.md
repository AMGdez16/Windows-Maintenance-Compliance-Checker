# Windows-Maintenance-Compliance-Checker
Scripts and resources for automating Windows system maintenance and compliance checks. Includes PowerShell scripts for updates, logging, and reporting to ensure system compliance and efficiency.


---
## **Introduction**

This repository contains PowerShell scripts designed to automate Windows system maintenance, disk space monitoring, and password policy compliance checks. This solution helps streamline routine updates, monitor disk space, and ensure that password policies meet organizational standards.

## **Features**

- **Routine System Updates:** Automate the installation of Windows updates and manage system reboots.
- **Disk Space Monitoring:** Check and report the available disk space on all file system drives.
- **Password Policy Compliance Checks:** Verify and report on password policies to ensure compliance.

## **Requirements**

- **Operating System:** Windows OS
- **PowerShell Version:** 5.1 or higher (adjust this based on the specific version required)

## **Step 1: Develop PowerShell Scripts**

1. **Write Scripts**  
   Automate maintenance and compliance with the following script:
   ```powershell
   # Install all Windows updates and automatically reboot
   Install-WindowsUpdate -AcceptAll -AutoReboot
   ```
   **Result**: Automated system maintenance is achieved.

2. **Integrate Logging and Reporting**  
   Implement logging and compliance reports with this script:
   ```powershell
   # Example script to generate a compliance report
   $ReportPath = "C:\Reports\ComplianceReport.txt"
   Get-WindowsUpdateLog | Out-File -FilePath $ReportPath
   ```
   **Result**: Detailed logs and reports are generated.

## **Step 2: Execute and Monitor**

1. **Clone the Repository**
   ```bash
   git clone https://github.com/AMGdez16/WindowsMaintenanceChecker.git
   ```

2. **Navigate to the Script Directory**
   ```powershell
   cd path\to\your\script\directory
   ```

3. **Run the Desired Script**
   ```powershell
   .\InstallUpdates.ps1
   .\CheckDiskSpace.ps1
   .\CheckPasswordPolicy.ps1
   ```

## **Customization**

- **Script Paths:** Update paths within the scripts to match your system’s directory structure.
- **Function Modifications:** Customize functions to fit specific compliance requirements or system configurations.

## **Final Result**

A reliable, automated system maintenance and compliance solution is in place, providing regular updates, monitoring, and reporting.

## **Additional Resources**

- **Access the Full Documentation:** [Google Drive Link](https://drive.google.com/drive/folders/1298T8wYjaMDutNvH3PiITdf-kqoQNjgy)
- [PowerShell Documentation](https://docs.microsoft.com/en-us/powershell/)
- [PSWindowsUpdate Module](https://www.powershellgallery.com/packages/PSWindowsUpdate/)
- [GitHub Markdown Guide](https://guides.github.com/features/mastering-markdown/)

## **License**

This project is licensed under the [MIT License](LICENSE).

## **Screenshots and Visuals**

![Example Screenshot](https://github.com/AMGdez16/WindowsMaintenanceChecker/raw/main/images/screenshot.png)

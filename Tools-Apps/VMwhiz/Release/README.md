<img src="Images/VMwhiz-Icon-Transparent.png" alt="VMwhiz" width="42" height="42"> <img src="Images/VMwhiz_Transparent.png" alt="VMwhiz" width="190" height="42">

##
## **Release notes**

**Update 0.9.2 - April 10, 2025**
- Fixed a bug installing Hyper-V feature on Windows server #11
- Fixed a bug where an error occurs when the application starts refreshing the dropdown list of existing VMs #12

##

  
**Update 0.9.1 - April 09, 2025**
- Fixed issue where the last selected VM was not retained after a refresh; now ensures reselection of the last chosen VM, defaulting to the first item if unavailable.
- Fixed path errors, removed GUI freezes, and improved VM startup reliability.
- Fixed syntax issues to ensure timers run without crashing.
- Implemented maintenance tasks to efficiently manage the cleanup of virtual machines and associated resources that are locked by Hyper-V after deletion operations.
- Implemented real-time updates for dropdowns, labels, and progress bars.
- Implemented version checking and update functionality with registry tracking.
- Improved form layouts, added tooltips, and updated labels for better user experience.
- Improved GUI Responsiveness: Eliminated blocking delays by relying on asynchronous state checks.
- Improved input validation for VM names, paths, and configurations.
- Improved code logic to save and retrieve configurations, including disk type, checkpoints, and VM paths.
- Improved logging and error messages for better debugging.
- Improved VM calculator logic for accurate resource estimation.
- Reworked functions for better readability and reusability.


© 2025 Rabih HADDAD. All rights reserved.


# AR Mood Room Application 

This repository hosts the documentation and requirements for the **AR Mood Room** application, a project for Application Development.

## Group Members

* **Jhon Lei B. Arao**
* **James Ruzzel Antonio**

## Product Overview

The AR Mood Room is an **Augmented Reality (AR) application** that allows users to place and customize virtual furniture, decor, lighting, and ambience into their physical room to create a desired atmosphere or "Mood".

Users can:
* Place and customize **virtual furniture, decor, lighting, and ambience** into their real-world environment.
* Select from a gallery of virtual objects and themes (e.g., furniture, lamps, plants).
* Adjust lighting effects and save customized mood room layouts.

## Key Requirements Summary

### Functional Capabilities
The app must provide controls for placing, moving, rotating, and resizing virtual objects in the AR space. The user interface must also display all relevant controls and options for customization.

### Non-Functional Requirements
| Category | Requirement |
| :--- | :--- |
| **Operational** | Must run on **Windows 10 or later** **AND** be compatible with **Android devices**. The app also requires a compatible camera that can utilize AR. |
| **Performance** | AR tracking should be **smooth and stable**. The application must run at **at least 60 fps**. |
| **Security** | The system **shall require user authentication** and must protect user data. |

##  Requirement Inspection Note

During the requirement inspection, several key defects were identified, including:
1.  **Missing Key AR Lifecycle Elements:** Critical use cases like "Calibrate AR Environment" or "Initialize AR View” were absent.
2.  **Clarity Issues:** The actor named "USER" was too generic and recommended to be renamed to "End User" or "Home Decorator".
3.  **Missing Actor Links:** Association lines were missing for functions like "Save Scene" and "Adjust Virtual Scale".

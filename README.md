<!--- @file
  Readme.md for UEFI / EDK II Training Tianocore Contents

  Copyright (c) 2018, Intel Corporation. All rights reserved.<BR>

  Redistribution and use in source (original document form) and 'compiled'
  forms (converted to PDF, epub, HTML and other formats) with or without
  modification, are permitted provided that the following conditions are met:

  1) Redistributions of source code (original document form) must retain the
     above copyright notice, this list of conditions and the following
     disclaimer as the first lines of this file unmodified.

  2) Redistributions in compiled form (transformed to other DTDs, converted to
     PDF, epub, HTML and other formats) must reproduce the above copyright
     notice, this list of conditions and the following disclaimer in the
     documentation and/or other materials provided with the distribution.

  THIS DOCUMENTATION IS PROVIDED BY TIANOCORE PROJECT "AS IS" AND ANY EXPRESS OR
  IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
  MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO
  EVENT SHALL TIANOCORE PROJECT  BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
  SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
  PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS;
  OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
  WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
  OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS DOCUMENTATION, EVEN IF
  ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

-->

# Tianocore_Training_Contents
Table of Contents and suggested course Schedule using [GitPitch]( https://gitpitch.com/docs/) on-line slideshow viewer.
  
To see the Slides with links to the presentations goto https://gitpitch.com/tianocore-training/Tianocore_Training_Contents/master#/

---
### GitPitch Key press controls

GitPitch slideshow presentations offer numerous keyboard controls and shortcuts to help presentation authors and their audiences to navigate and interact with slideshow content.

-  Press **F** for full screen
-  Press **O** for Overview
-  Press **B** for Blackout 
-  Press **M** for menu
-  Press **?** for help
-  Press **S** for Speaker notes
- To get a PDF of the presentation, use the lower left white bars ( "&equiv;" ) and select "Print Version(.pdf)"
- Navigation,  Space - Arrow keys - Page Down ( Arrows at bottom right show Next slide or sub-slides) ( " < &or; > ")

---

## Schedule / outline
The following is a link to the corresponding repository for each presentation.  Each repository has a link to the GitPitch slideshow.

|Unit 1 | Unit 2 | Unit 3 | Unit 4 |
| ----------------- | ------------------ | -------------- | -------------- |
| [Overview UEFI/ FSP Boot Flow ](https://github.com/tianocore-training/UEFI_Boot_Flow_Pres)  | [UEFI Aware OS -UEFI Secure boot](https://github.com/tianocore-training/UEFI_Aware_OS_Pres)| [Porting a  EDK II Project using Open Source example ](https://github.com/tianocore-training/EDK_II_Porting_Projects_Pres)| [UEFI / EDK II Network ](https://github.com/tianocore-training/UEFI_EDK_II_Network_Pres) |
| [EDK II Build Environment & Process](https://github.com/tianocore-training/EDK_II_Build_Process_Pres) | [EDK II Libraries and Modules and Drivers ](https://github.com/tianocore-training/EDK_II_Modules_Libs_Drivers_Pres) | [Porting EDK II Board - Apollo Lake](https://github.com/tianocore-training/EDK_II_Porting_Board_Pres) | [UEFI / EDK II Security ](https://github.com/tianocore-training/UEFI_Platform_Security_Pres)|
| [EDK II Build Spec Files](https://github.com/tianocore-training/EDK_II_Build_Spec_Files_Pres) | [EDK II Platforms configuration Database (PCD)](https://github.com/tianocore-training/Platform_Config_DB_PCD_Pres)| [Porting Beyond the Shell w/ EDK II](https://github.com/tianocore-training/EDK_II_Porting_Beyond_Shell_Pres)| [UEFI / EDK II Capsule Update ](https://github.com/tianocore-training/Capsule_Update_Pres)|
| [Open Source UEFI Platforms](https://github.com/tianocore-training/OpenSource_Platforms_Pres) | Writing UEFI Applications Lab [Linux](https://github.com/tianocore-training/Writing_UEFI_App_Lab) or [Windows ](https://github.com/tianocore-training/Writing_UEFI_App_Win_Lab) | EDK II Debugging Lab [Linux](https://github.com/tianocore-training/EDK_II_Debugging_Pres_Lab) or [Windows ](https://github.com/tianocore-training/EDK_II_Debugging_Pres_Win_Lab) | [UEFI / EDK II - HII Lab ](https://github.com/tianocore-training/UEFI_HII_Overview_Pres_Lab)|
| EDK II Platform Build Lab [Linux](https://github.com/tianocore-training/Platform_Build_Lab) or [Windows](https://github.com/tianocore-training/Platform_Build_Win_Lab) | [UEFI Driver Model  ](https://github.com/tianocore-training/UEFI_Driver_Pres) | [Source Level Debugging w/ UDK Debugger](https://github.com/tianocore-training/EDK_II_UDK_Debugger_Pres)| &nbsp; |
| Platform Build Lab Apollo Lake UP2 [Linux](https://github.com/tianocore-training/Platform_Build_Lab_UP2_Linux) or [Windows](https://github.com/tianocore-training/Platform_Build_Lab_UP2_WIN) | UEFI Driver Wizard Lab [Linux](https://github.com/tianocore-training/UEFI_Driver_Wizard_Lab) or [Windows](https://github.com/tianocore-training/UEFI_Driver_Wizard_Win_Lab) | &nbsp; |&nbsp; |
| [UEFI Shell Application](https://github.com/tianocore-training/UEFI_Shell_App_Pres) | UEFI Driver Porting Lab  [Linux](https://github.com/tianocore-training/UEFI_Driver_Porting_Lab) or [Windows](https://github.com/tianocore-training/UEFI_Driver_Porting_Win_Lab) | &nbsp; |&nbsp; |
| UEFI Shell Lab [Linux](https://github.com/tianocore-training/UEFI_Shell_Lab) or [Windows](https://github.com/tianocore-training/UEFI_Shell_Win_Lab) | &nbsp;  | &nbsp; |&nbsp; |
| &nbsp; | &nbsp;  | &nbsp; |&nbsp; |




## Lab Training Material
The following github repositories contain the Lab Material :  

- [Lab_Material_FW]( https://github.com/tianocore-training/Lab_Material_FW)
  - FW
     - Documentation
     - DriverWizard
     - edk2 (- Same as https://github.com/tianocore/edk2 )
     - LabSampleCode
- [PlatformBuildLab_FW](https://github.com/tianocore-training/PlatformBuildLab_FW)
  - FW
    - PlatformBuildLab
      - Max (- source code for the Minnowboard Max / Turbot V 1.00)

- [PlatformBuildLab_UP2 FW](https://github.com/tianocore-training/PlatformBuildLab_UP2_FW)
  - FW
    - PlatformBuildLab
      - MV3 (- source code for the Apollo Lake build support for UP Squared Board)
	  
	  
	  
## On-line Self Paced web-based training:
See full description at : https://github.com/tianocore/tianocore.github.io/wiki/UEFI-EDKII-Learning-Dev 

|Download |	Description|
| ----------------- | ------------------ |
|[Zip file** ](https://github.com/tianocore-training/Lesson-0/archive/master.zip) | Lesson 0: Defining Specifications' Role in Firmware |
|[Zip File** ](https://github.com/tianocore-training/Lesson-1/archive/master.zip) | Lesson 1: Course Introduction and Pre-EFI (PEI) and Security (SEC) Phases |
|[Zip File**](https://github.com/tianocore-training/Lesson-2/archive/master.zip) | Lesson 2: Driver Execution Environment (DXE) |
|[Zip File**](https://github.com/tianocore-training/Lesson-3/archive/master.zip) | Lesson 3: UEFI Drivers |
|[Zip File**](https://github.com/tianocore-training/Lesson-4/archive/master.zip) |Lesson 4: Firmware and Data Storage|
|[Zip File**](https://github.com/tianocore-training/Lesson-5/archive/master.zip) |Lesson 5: Boot Device Selection (BDS) and Human Interface Infrastructure (HII)|


## For questions 
[email laurie0131](mailto:laurie.jarlstrom@intel.com)

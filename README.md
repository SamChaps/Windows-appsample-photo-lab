---
page_type: sample
languages:
- csharp
products:
- windows
- windows-uwp
- windows-app-sdk
statusNotificationTargets:
- codefirst@microsoft.com
---

<!---
  category: ControlsLayoutAndText FilesFoldersAndLibraries
-->

# UWP+WinAppSDK PhotoLab sample

A sample app that illustrates how to maintain both UWP and WinAppSDK platform within a single solution using the [PhotoLab sample](https://github.com/microsoft/Windows-appsample-photo-lab).

## Solution structure

![image](https://user-images.githubusercontent.com/16784153/202829686-ad9d4178-f5d0-495e-8b51-092b78278f53.png)

* **Platforms** folder containing both UWP and WinAppSDK application projects.
  * **PhotoLabUWP.csproj** containing UWP app specific code.
  * **PhotoWASDK.csproj** containing WinAppSDK app specific code.
* **Solution Items** folder containing license, contribution and readme files.
* **PhotoLab.shproj** containing shared code between UWP and WinAppSDK projects.

## Running the sample

The default project is PhotoLabUWP, you can also change to PhotoLabWinAppSDK, and you can Start Debugging (F5) or Start Without Debugging (Ctrl+F5) to try it out. 
The app will run in the emulator or on physical devices. 


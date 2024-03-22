# Getting Started

StudFinder is currently supported in Rhino 7, Grasshopper v1.0, and Revit 2022-2024.

To ensure you have a seamless experience, please follow the installation instructions below for integrating StudFinder into Rhino, Grasshopper, and Revit.

## Rhino / Grasshopper Installation:
1. Open Rhino
    - With Rhino installed launch the software and make sure it is up to date.
2. Open Package Manager: 
    - Input the command **PackageManger** into the command line opening the package manager window.
3. Search For **StudFinder**:
    - Ensure that **Include pre-releases** is checked in the lower left corner of the window.
    - Upon finding the StudFinder package select the version you want to install and click install.

    ![installpackagemanager](/assets/gettingstarted/rhinograsshopper/installpackagemanager.jpg)

4. Verify Installation:
    - Restart Rhino.
    - Be sure that the StudFinder side panel is open, if it is not open it by right clicking on your panels gear and selecting **StudFinder** from the list.
    - Login to the panel using your STUD-IO credentials to enable StudFinder Rhino commands and components in Grasshopper.

    ![openpanel](/assets/gettingstarted/rhinograsshopper/openpanel.jpg)
    
    ![loginpanel](/assets/gettingstarted/rhinograsshopper/loginpanel.jpg)

**Rhino 8 Only**:

If you are installing StudFinder on Rhino 8 you will also need to follow the steps below to run using *NETFramework*. Further information about Rhino and NETFramework/NETCore can be found on the Rhino website ![here](https://www.rhino3d.com/en/docs/guides/netcore/).

1. Upon lauching Rhino, type the command **SetDotNetRuntime**
2. Select the **Runtime** option (by default this should be set to *Default* which is NETCore)
3. Set the **NETFramework** option
4. Restart Rhino. Rhino will continue to run in NETFramework until you switch this option again.

In coming releases, StudFinder will take advantage of NETCore and run there, but until that release and announcement please continue to ue Rhino using NETFramework.


 
## Revit Installation:

1. Download Revit Plugin:
    - Visit the StudFinder [downloads](www.studfinder.io/downloads) page.
    - Find the Revit plugin download link and download the installer.
2. Run Revit Installer:
    - Double-click on the downloaded installer file.
    - Follow the installation prompts to complete the process.
3. Verify Integration:
    - Ensure the StudFinder ribbon appears at the top of your Revit session.

For further help with intallation of any StudFinder integrations please reach out via our [community forum](https://studio.discourse.group/).

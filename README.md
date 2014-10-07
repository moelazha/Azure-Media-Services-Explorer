Azure-Media-Services-Explorer
=============================

A Winforms/C# application for Windows that does upload, download, encode, package, and stream assets with Azure Media Services.
The latest binary (with an installer) is available in the release section. https://github.com/xpouyat/Azure-Media-Services-Explorer/releases

This solution has been developped with Visual Studio 2013. It contains two projects: "AMSExplorer" and "SetupAMSExplorer".
"AMSExplorer" is the main application.
"SetupAMSExplorer" is an InstallShield project that creates a Setup executable (EXE/MSI).

In order to compile this setup project, you must install InstallShield Limited Edition for VisualStudio. To do this:
- Launch Visual Studio 2013
- Select New project
- Select Installed / Other Project Types / InstallShield Limited Edition Project
- This should trigger the process to install and activate InstallShield.

Contact: amse@microsoft.com
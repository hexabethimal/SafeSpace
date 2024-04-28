# SafeSpace
Safe Space Web Browser

This GitHub repository includes:
- Releases (For non-tech people > Look to the right -->)
- A project overview with main highlights

**A shortcut to a thorough wikipedia-style reference will appear on your Desktop after installing Safe Space**

*What appears below is intended to offer basic information, but not complete instructions*

## Table of Contents
- **What is Safe Space?**
  - **Safety First**
  - **Capabilities**
  - **Dependencies**
- **Requirements & Setup**
- **Why no source code?**
- **Bug Reporting**

## What is Safe Space?
Safe Space was initially designed to meet unique needs and provide better web safety for a specialized work environment. During its development, I realized that it had potential to also be a great tool for anyone interested in its unique features and many security options.

Safe Space offers a highly customizable experience through its many options inside Settings. New users are encouraged to refer to the full wiki (Desktop shortcut) and to experiment with customization options inside Settings to suit individual preferences.

![Image of Safe Space UI](/safespaceui.png)

## Safety First
Safe Space has zero connections to cloud-based resources (other than those built into the underlying dependency, WebView2 by Microsoft). Neither the application of Safe Space or any of its features will transmit or store any data remotely. As a program designed to run entirely on the local system, Safe Space does not know (and will not alert you) when a new update is available; and you are free to stay on whatever version you prefer. It is up to you to check **Releases** to see if an update is available, if you desire to update. As a program designed to run entirely on the local system, Safe Space provides no "syncing" capability or "browser profiles" (which would require your data to be stored remotely).

## Capabilities
Includes all modern web browser standard features plus many innovative approaches and security tools:
- Private/Incognito tabs side-by-side with normal tabs
- Multiple simultaneous incognito sesssions
- Drag-and-drop all tab types with no restrictions
- Rename browser tabs
- Utilize left/right clicks for more options with fewer buttons
- Import extensions from Edge or Chrome
- Options to prevent downloads by specified file type
- Optional PDF scan on download for detecting harmful automatic code execution
- Options to reject web navigation for certificate or https issues
- and more

## Dependencies
Safe Space has a couple of underlying dependencies worth mentioning. First, Safe Space relies on the WebView2 runtime which uses Microsoft Edge as the rendering engine to display web content. However, unlike the standard Microsoft Edge application, WebView2 provides the ability to significantly customize the experience of using Edge (beyond what would be possible within Edge), such as turning some features off entirely or adding new features.

Second, Safe Space utilizes an embedded Python environment and Python script to aid in detecting malicious PDF files.

## Requirements & Setup

Windows-only. Windows 11 recommended. Limited testing on Windows 10. 16GB RAM memory recommended, but will work with less.

Please follow the suggested installation location. Safe Space has internal program references to the expected location of its core files.

Safe Space stores its essential, static program files in the standard Program Files directory. Safe Space stores its essential, user alterable files inside the user appdata roaming folder. (The appdata folder is hidden by default within Windows and hidden folders must be toggled on within Windows settings to view this folder and its contents.) Tampering with Safe Space's essential files or their contents could lead to Safe Space not working. Remember that Safe Space lets you control all of its settings through the Settings window.

## Why no source code?
Safe Space is closed-source for only one reason; an internal program dependency on Syncfusion. Syncfusion is a UI component kit that software developers use to offer capable user inputs without designing everything from scratch. Because Syncfusion is a paid product, their terms of use prohibit open-sourced projects, since this could reveal private developer keys that authenticate access to their product. For anyone who is concerned about how Safe Space operates, I can offer you the complete source code with UI elements removed upon request. It is not my intention to be secretive about anything about how Safe Space works.

## Bug Reporting
Your feedback about bugs encountered is valuable to me. However, please be aware that bug fixes are not guaranteed and may be significantly delayed. Report any bugs, including a thorough description of **how it happened** and **what happened exactly** by selecting **Issues** (on the top in the website you are reading right now) and then clicking to *create a new issue*. Alternatively, you can email me at the email address mentioned in the included wiki, following installation.

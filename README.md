# PMD Solver VS Code Extension
## Overview
The PMD Solver VS Code Extension resolves below 2 common PMD Issues

    1.**Rule**:EmptyCatchBlock -> Avoid empty catch blocks 
    2.**Rule**:DebugsShouldUseLoggingLevel -> Calls to System.debug should specify a logging level.
## Features
- **Apex Debug Log Level Updater**: Adds LoggingLevel.FINE for all the System.debug statements in all triggers and classes of salesforce project.
- **Empty Catch Block Logger**: replaces empty catch block with below system.debug Error Logging Statement
    System.debug('Cause : '+e.getCause() +' Message: '+e.getMessage()+' Stack: '+e.getStackTraceString() + ' Line: ' + e.getLineNumber());

## Prerequisites
Before using this extension, ensure you have the following installed:
- **Python**: This extension requires Python. You can download it from [python.org](https://www.python.org/downloads/).
- Install below Python Extension in VS Code
      ![Screenshot (1130)](https://github.com/user-attachments/assets/bd7bc540-a58b-4252-bf1d-221fd11cf4da)

## Installation
1. Download the `.vsix` file for the PMD Solver extension provided above.
2. Open Visual Studio Code.
3. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side or by pressing `Ctrl+Shift+X`.
4. Click on the three-dot menu in the top right corner.
5. Select **Install from VSIX...** and choose the downloaded `.vsix` file.
   ![Screenshot (1131)](https://github.com/user-attachments/assets/105cb1aa-30a8-48fd-9d30-fb8898d10eba)

## Usage
Once the extension is installed, you can use the following commands:
1. **Apex Debug Log Level Updater**
  - Right-click in the editor and select **Apex Debug Log Level Updater** to update all the classes and trigger system.debug() with logging level.
   ![Image1](https://github.com/user-attachments/assets/ef94cfa0-b44a-403e-8078-4b15718e9834)

  ![Image2](https://github.com/user-attachments/assets/5ec444f5-c62d-4e5c-a668-e0cabca7db2f)

2. **Empty Catch Block Logge**
  - Right-click in the editor and select **Empty Catch Block Logger** to update all the classes Empty Catch blocks with System.debug().
   ![Image3](https://github.com/user-attachments/assets/d03bee05-4b04-492f-a1bc-5c9bda9d46fc)
   ![Image4](https://github.com/user-attachments/assets/74c684bf-f743-45de-942b-5e5283196a0a)
   ![Image5](https://github.com/user-attachments/assets/b04e3353-b683-40d2-8385-1ba3430bfdf4)



3. **Success Message**
    -On button of the vscode window you get below success message.
    ![Image6](https://github.com/user-attachments/assets/5e2d86aa-f484-4792-bd0f-58c468ab46ab)


## Author
**M Pravalika**

**Mail: mpravalikashetty@gmail.com**

**Happy Learning!**

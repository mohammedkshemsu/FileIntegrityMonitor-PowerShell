# File Integrity Monitoring with PowerShell

## Objective

Create a PowerShell script for monitoring file integrity. The script will calculate and store file hashes in a baseline file. It will then continuously monitor the specified folder for changes, deletions, or additions and notify the user accordingly.

### Flowchart

![Image](https://i.imgur.com/tbi9sLJ.png)

## Requirements

1. **Prerequisites:**
   - Basic knowledge of PowerShell scripting.
   - Access to a Windows environment.

2. **Features:**
   - Calculate and store file hashes in a baseline file.
   - Continuous monitoring for changes using an infinite loop.
   - Notifications for new file creations, changes, or deletions.

## Getting Started

### Step 1: Download and Install PowerShell (if not installed)

Ensure that PowerShell is installed on your Windows machine.

### Step 2: Create a New PowerShell Script

Open your preferred text editor (e.g., Visual Studio Code, Notepad++) and create a new PowerShell script file with a `.ps1` extension.

### Step 3: Copy and Paste the Script

Copy the provided PowerShell script into your newly created script file.

### Step 4: Run the Script

Save the script file and open a PowerShell terminal. Navigate to the directory containing your script and execute it by running:

( ```powershell
.\YourScriptName.ps1 )

### Step 5: Choose Action (a or b)

Enter 'a' to calculate new hashes and create a new baseline.
Enter 'b' to begin monitoring the files.

### Step 6: Observe Monitoring
If you chose option 'b', the script will enter an infinite loop, checking for changes every second. Observe the notifications for new file creations, changes, or deletions.

| User Input Console | File Creation Notification | File Modification Alert |
| --- | --- | --- |
| ![Image](https://i.imgur.com/qUyoGbd.png) | ![Image](https://i.imgur.com/pAO7ZdT.png) | ![Image](https://i.imgur.com/LKZRseY.png) |


### Conclusion

The File Integrity Monitoring with PowerShell script provides a valuable tool for safeguarding file integrity and preventing unauthorized modifications. By continuously monitoring file changes and generating notifications, this script helps maintain data integrity and ensures system security.

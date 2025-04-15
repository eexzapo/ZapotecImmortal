# Zapotec Immortal

PUBG help program

![image](https://github.com/user-attachments/assets/9a30ebd1-95d7-4130-b5d9-ef9878345ac4)


# Indtroduction

# Guid

This tool provides functionality for managing process affinity, priority, and performing maintenance operations specifically tailored for games like PUBG. The UI is divided into several categories to help manage your system performance effectively.

# 🔧 Processor Affinity
Used to assign specific CPU cores to selected processes.

▶️ Set Button
Assigns selected processes to "Cores for Gaming".

All other processes are assigned to "Cores for Others".

📝 Text Fields
Process to Core text area
List of process names (comma-separated) that should use gaming cores.
Example: TslGame,MyGameApp

Cores for Gaming text area
CPU cores reserved for gaming (1-based index, comma-separated).
Example: 1,2,3,4

Cores for Others text area
CPU cores for all other processes (1-based index, comma-separated).
Example: 5,6,7,8

Logs text area
Displays actions, time stamps, success messages, and any errors.

Description text area
Optional notes or a quick explanation of the current setup.

# ⚙️ Processor Priority
Used to set the priority level of processes.

🔘 Buttons
High
Sets the priority of processes listed in "Priority High" to High.

Extream
Sets "Priority High" processes to High, all others to Low except those in "Not Included".

📝 Text Fields
Priority High text area
List of process names (comma-separated) to set as High priority.
Example: TslGame,GameApp

Not Included text area
List of processes to ignore during "Extream" operation.
Example: explorer,Taskmgr

Logs text area
Displays logs including actions, time, results, and any exceptions.

# 💣 KILL PUBG
Tools for controlling PUBG-related processes.

🔘 Buttons
Kill Process
Forcefully terminates all processes listed in the "Process text area".

Kill Low Memory ThisGame
Finds multiple "TslGame" instances and kills the one using the least memory.

Delete Movies
Finds the PUBG installation directory and deletes all files in TslGame\Content\Movies.

Crash Helper (10 second cleanup)
Deletes Saved folder to reset PUBG settings. Optionally backs up GameUserSettings.ini. After 10 seconds, the game can be terminated (if needed).

📝 Text Fields
Process text area
List of process names (comma-separated) to be terminated.
Example: TslGame,MyGameApp

Logs text area
Logs of kill attempts, success/failure results, and memory usage (if applicable).

# ℹ️ Info
🔘 Info Button (top-right corner)
Displays a dialog or RichTextBox with useful crash help instructions, tips, and common fixes (e.g. resetting PUBG settings).

# ❌ Exit
🔘 Exit Button (bottom-left corner)
Closes the application.

# Licence

 Zapotec Immortal - Pubg help tool

 Description:
 Zapotec Immortal is a utility application designed to help users manage and monitor system processes, specifically focusing on performance adjustments, memory management, and game-related settings. This program offers functionality to adjust process priorities, assign CPU cores to specific applications, clean up unnecessary files, and manage settings related to games like PUBG.

 Key features include:
 - Adjusting process priorities based on user input.
 - Assigning CPU cores to specific processes for improved performance.
 - Cleaning up unnecessary files and configurations to help improve game performance or troubleshoot crashes.
 - Restoring settings files from backups to ensure correct configuration.

 This tool is intended for use by gamers and developers who wish to fine-tune their system's performance for specific applications and games. It provides flexibility for various system optimizations, but users should exercise caution and ensure they understand the changes being made to avoid system instability.

 Usage:
 By using Zapotec Immortal, you acknowledge and agree that the actions you take using this program are at your own risk. The program provides functionalities that can alter system settings, processes, and files. While these operations are intended to optimize performance and fix specific issues, improper use or understanding of the program’s features can lead to unintended consequences.

 License and Ownership:
 This program, ""Zapotec Immortal,"" is developed and distributed by ZapotaZ. All rights to the software and its contents are retained by ZapotaZ. Users are granted permission to use the software solely for personal and non-commercial purposes. Redistribution, modification, or commercial use of the software is prohibited without explicit permission from the copyright holder.

 ZapotaZ is not liable for any damages, data loss, or other issues that may arise from the use of this software. By using this program, you agree to accept full responsibility for any outcomes or consequences resulting from its use.

 Important:
 - The use of this software is at your own risk.
 - The software is provided ""as is"" with no warranties or guarantees.
 - Users must ensure that they back up any important data and settings before using the software, particularly before making changes to system configurations or deleting files.

 Copyright and Trademark:
 All trademarks and brand names related to the Zapotec Immortal software are the property of ZapotaZ, unless otherwise noted. All rights are reserved. 
 Icons made by Dia de Muertos, Processor glyph silhouettes, Angara, Freepick, bsd from www.flaticon.com.
            

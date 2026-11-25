# milestone-xprotect-autologin-multimonitor-script

Base script to automate the login process in Milestone XProtect 2025 R3 and automatically configure and display views across multiple monitors.

# Automatic Script Execution

To make the script run automatically when Windows starts, simply create a shortcut in the Windows Startup folder using the following command:

"C:\Program Files\Milestone\XProtect Smart Client\Client.exe" -Script="C:\path_to\file.scs"

Default installation path for Milestone XProtect Smart Client:

"C:\Program Files\Milestone\XProtect Smart Client\Client.exe"


# Correct Application Monitor

Windows sometimes remembers the last monitor where an application was opened or closed. This can cause the application to open on the wrong screen.

To fix this, open the application, move its main window to the primary monitor, and close it. Then open it again and check that everything is displayed on the correct monitor.


## Windows 11 - Disable Window Position Memory

Windows 11 has an option that remembers window positions depending on how your monitors are connected.

To disable it:

1. Open Settings.
2. Go to System -> Display -> Multiple displays.
3. Uncheck "Remember window locations based on monitor connection".

This prevents Windows from automatically restoring applications to their previous monitor positions when monitor connections change.


## Windows 10

Windows 10 doesn't have a built-in option to disable this behavior.

Applications may continue opening on the last monitor where they were used, so you'll need to move them manually whenever necessary.

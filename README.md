# Hydra Virus
<img src="https://github.com/giabao4498/Hydra-Virus/blob/master/Hydra%20icon.ico">

## *"Cut off one head, two more shall take its place!"*

Hydra is a Windows virus that displays a message box. When you close a message box, 2 more will show up.

This virus was implemented using ***Visual Basic*** and ***.NET 4.7.1***.

To shut it down complete, you can use Task Manager. If the Task Manager is disable, do the following steps to enable it:
- Open **Registry Editor**
- Locate `Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\System`
- Open **DisableTaskMgr**, enter `0` to **Value data**
- Click **OK**

To stop the virus from running at Windows startup, do the following steps:
- Open **Registry Editor**
- Locate `Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run`
- Delete the `Hydra` registry value

Demo 1: https://youtu.be/2Nk8loSs02c

Demo 2: https://youtu.be/a2TUs6uHr70

Note that this virus is harmless 🙂 If you know how to make it more annoying (for example: Task Manager can't shut it down), feel free to contact me

(so that means Task Manager is Captain America 🤔)

# *HAIL HYDRA!*

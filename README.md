# Set-up
-------------------
Repository dedicated for setting up the basic tools needed at Elevate.

You'll find below the instructions to set-up your computer such as VScode, Terminal, zsh, Docker and other utilities.

Please feel free to contribute ✨

Let's start !

## Github

If you haven't register to github, [do it right away !](https://github.com/)

Github is our hub where every consultant share their code, a useful collaborative coding tool.

👉 Use the mail address Elevate gave you to register, in order to ensure security in our organization we tend to avoid using our respective personal Github.
👉 Upload a picture with your best smile and ask permission to join elevate-agency organization, you'll find there every on-going data & tech project and more.

![image](https://user-images.githubusercontent.com/114242324/202664978-fb5c3bc3-7f72-4d12-9913-1fc7469b2c45.png)

## Virtualization

We need to ensure that the Virtualization options are enabled in the BIOS of your computer.

For many computers, this is already the case. Let's check:
- Press `Windows` + `R`
- Type  `taskmgr`
- Press `Enter`
- Click on the `Performance` tab
- Click on `CPU`

![Windows task manager](https://github.com/lewagon/setup/blob/master/images/windows_task_manager.png)

:heavy_check_mark: If you see "Virtualization: Enabled", you're good to go :+1:

:x: If the line is missing or if the virtualization is disabled, please **contact a teacher before trying to activate the Virtualization**

<details>
  <summary>Activate Virtualization</summary>

  We need to access the BIOS / UEFI of the computer to activate it.
  - Press `Windows + R`
  - Type  `shutdown.exe /r /o /t 1`
  - Press `Enter`
  - Wait for the computer to shutdown
  - Click on `Troubleshoot`
  - Click on `Advanced Options`
  - Click on `UEFI Firmware Settings`
  - Click on `Restart`

  You need to activate the virtualization option for your processor here:
  - Most of the time, in the advanced settings, the CPU settings, or the Northbridge settings
  - The option can be called differently according to your computer:
      - Intel: `Intel VT-x`, `Intel Virtualization Technology`, `Virtualization Extensions`, `Vanderpool`...
      - AMD: `SVM Mode` or `AMD-V`
  - Save the changes after activation and reboot the computer through the appropriate option
</details>





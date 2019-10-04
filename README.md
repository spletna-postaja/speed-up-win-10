# Speed up your Windows 10

## Preface

There are quite a few developers in our company and we mostly use machines with Microsoft Windows 10 operating system. The nature of our work requires us to have a lot of programs installed that we work with.

When a new worstation is setup and configured, everything works normally at first, but eventually the system starts to work more and more slowly. 
Working speed (or the lack of it) is a real problem for us, so we tried to diagnose the slowness of our PCs and speed up the machines on a software level, since the hardware was clearly not a problem.

We prepared a step-by-step guide for each of our developers and since it turned out to be a great solution, we decided to share it with everybody.

## Guide on how to speed up Windows 10

### Step 1: Update your system

1. Click the Windows logo Start button, write "Check for updates" and click the Best match
2. Click the button "Check for updates" and wait for a few moments
3. Updates will be downloaded and installed - your might have to restart your PC during the update process
4. When you restart the PC, open the "Windows Update" again and check for updates again, until you're up to date

### Step 2: Run disk cleanup

1. Right-click the Windows logo Start button and select "File Explorer"
2. Check the "Devices and drivers", right-click your System disk (usually marked with a letter C) and select "Properties"
3. Under the "General" tab, click the button "Disk Cleanup"
4. Once the Disk Cleanup window opens up, click the button "Clean up system files"
5. It's safe to select the options:
	- Windows Update Cleanup (older versions of the system)
	- Windows Defender Antivirus (non critical files used by Windows Defender)
	- Windows upgrade log files (some Windows upgrade log files)
	- Downloaded Program Files (ActiveX controls and Java applets)
	- Temporary Internet Files (your browser cache for Internet Explorer and Microsoft Edge)
	- System error memory dump files (memory dump files)
	- System archived Windows Error Reporting (some error reports)
	- System queued Windows Error Reporting (some error reports)
	- Delivery Optimization File (some no longer needed data)
	- Device driver packages: (old versions of device drivers)
	- Previous Windows installation(s) (old Windows system files)
	- Recycle Bin (empty your Recycle Bin)
	- Temporary Files (temporary files programs aren't using)
	- Temporary Windows installation files (some temporary files)
	- Thumbnails (cached thumbnails)
	- Temporary Setup Files (no longer used files)
6. After you select the desired files to delete, click the OK button and wait for the process to complete

### Step 3: Use IObit Uninstaller

1. Navigate to [IObit Uninstaller](https://www.iobit.com/en/advanceduninstaller.php) homepage and download their free software
2. Run the downloaded setup file and click "Custom Install"
3. Tick desired checkboxes and click "Install" button
4. On the next step, you can skip the Advanced SystemCare installation by clicking the "Skip This" button
5. Wait for the installation process to finish
6. Run the program and select "Windows Apps" on the left menu
7. Open "Windows Apps" section, select everything you do not use or need and click the "Uninstall" button
8. Tick the "Automatically remove residual files" checkboxes and click "Unintall"
9. Wait for the process to complete and close the report window
10. In the main window, select "Programs" / "All programs" on the left menu
11. Select all the software you do not use or need and repeat the procedure

### Step 4: Use CCleaner

1. Navigate to [CCleaner](https://www.ccleaner.com/) homepage and download their free software
2. Run the downloaded setup file, un-tick the "Yes, install CCleaner Browser" and click the "Customize" link
3. Select desired checkboxes and click the "More" link
4. On the next step, leave the "Install for anyone using this computer" option enabled and click the "Install" button
5. Wait for the installation process to finish
6. Run the program and select "Registry" on the left menu
7. Click "Scan for Issues" button and when the scan completes, click the "Fix selected Issues..." button
8. When you're prompted about the backing up the registry, you can choose "Yes" and save the file to your Documents
9. On the next window click "Fix All Selected Issues" button and wait for the process to complete
10. Now repeat the steps 7-9 until there are no more issues to be found
11. When you're done, you can select "Custom Clean" on the left menu and "Run Cleaner" for the desired selected options

### Step 5: Use ShupUp10

1. Navigate to [O&O ShutUp10](https://www.oo-software.com/en/shutup10) homepage and download their free software
2. Move the downloaded file from your "Downloads" directory to your "Program Files" directory on your System disk (usualy C:)
3. Run the file "OOSU10.exe"
4. Select "Actions" / "Apply only recommended settings"
5. Check the switches to get acknowledged with the services you're disabling and enable/disable more of them
6. Once you close the program, you'll have to restart the system

### Step 6: You're done!

Once you do all of the steps above, you're finished and your Windows 10 OS should be runing much faster and smoothly.

## Guide on how to maintain the new status

### Step 1: Keep up to date

We suggest you check for new Windows updates at least twice a month and update your system accordingly.
After every update, run disk cleanup and clear up your disk space.
Same goes for CCleaner - use it at least twice a month, clean up your regitry and other files.

### Step 2: Use IObit Uninstaller for removing programs

Every time, you need to uninstall/remove any of the installed software on your computer, always use IObit Unintaller and clean up the residual files as well.

### Step 3: Check ShutUp10 once in a while

Some Windows updates might turn some Windows services back on, so check the enabled Windows services with ShutUp10 once a month or so.

## Author and maintenance

Author of this project is [Blaž Oražem](https://github.com/BlazOrazem), www.orazem.si

This project is supported and maintained by [Spletna postaja](https://spletna-postaja.com/), a web development company.

Ta projekt podpira in vzdržuje [Spletna postaja](https://spletna-postaja.com/), podjetje za razvoj in [izdelavo spletnih strani](https://spletna-postaja.com/izdelava-spletnih-strani) in [izdelavo spletnih trgovin](https://spletna-postaja.com/izdelava-spletnih-trgovin).

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

[<img src="https://img.shields.io/packagist/l/doctrine/orm.svg?style=flat-square" alt="MIT License">](LICENSE)
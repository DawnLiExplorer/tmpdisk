TmpDisk
=======

TmpDisk is an Open Source simple RamDisk management tool. RamDisks are disks that use your memory (RAM) to create virtual hard disks on your Mac. RamDisks can be any size, limited only by your total memory and lightning fast. They are also temporary. Any files stored on a RamDisk will be permanently deleted when the disk is ejected. No need to worry about deleting, trash or cleaning up temporary files anymore. **Warning** A TmpDisk will not survive a restart or ejecting. Any files or information on the disk will be PERMANENTLY deleted once the computer is shutdown or the disk ejected. TmpDisks are perfect for 
* Saving large files such as photos while editing 
* Downloading and extracting zip files 
* Storing of temporary logs and files 
* Easily cleaning up tmp files

Support
-------

For support, tracking updates, announcement and to participate in the Imothee Community please join us on [Discord](https://discord.gg/5UgyRYaEq6)

Maintaining TmpDisk for over [10 years](https://www.macupdate.com/app/mac/44022/tmpdisk) has been expensive and exhausting. If you can, please support us! We're looking for testers, volunteers, translators, advocates and donations.

Installing
----------

After 2.0.4 TmpDisk supports a minimum MacOS version of 10.14.6.

Down the latest release https://github.com/imothee/tmpdisk/releases/latest or clone the repository and build the application yourself. All required files are included.

Usage
-----

TmpDisk installs as a Status Bar application. You can use the menu to create new tmpdisks, eject existing tmpdisks and click on a disk to open it in finder.

As of 1.0.4 you can also run the app from the command line and pass in arguments to create a TmpDisk on startup.

`open -a /Applications/TmpDisk.app --args -name=TestDisk -size=64`

Will create a TmpDisk name TestDisk with 64MB space.

# WindowsBackupScript
Powershell scripts to backup Windows Server based on scripts written by Alexandre Augagneur ( http://www.alexwinner.com )

Currently two scripts are used :
* one for system state of bare metal backup ( Backup-Task.ps1 ). It uses 7zip for compression

* second was modified for daily backup of several folders

Functionalities
* backup using Windows backup functions
* can be used to backup complete server ( using system state / bare metal options ) or some folders
* synchronization with remote folder using robocopy
* multiple retention methods ( deletion broken )
* native zip compression 
* FTP support ( alpha )

Prerequisites
* Powershell 3
* .Net framework 4.5

Known problems
* for some reason Windows backup could failed on remote folder hosted by Linux




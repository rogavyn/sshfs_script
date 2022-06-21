# sshfs_script

Small script to simplify mounting/unmounting drives over sshfs

Just add the remote folder and local folders in the folders file in the typical sshfs format:
username@999.999.999.999:/your/folder for the remote machine
/folder/location/you/want/to/mount on your local machine

Kill function will completely kill the process in case of a hangup

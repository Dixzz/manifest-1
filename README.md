<img src="https://github.com/Devilian-Os/Logos/blob/pie/Artboard%201.jpg" >
</p>




                                                    >>  DevilianOS <<

A ROM Based on Aosp, with features from almost all Custom ROMs available. 

# ======== # ======== # ======== # ======== #

To initialize your local repository, use this command:

    repo init -u https://github.com/Devilian-Os/manifest -b pie

To sync the repository, use this command:

    repo sync -f -c -j8 --force-sync --no-clone-bundle --no-tags

To Build, use following commands:

    . build/envsetup.sh && lunch devilian_<device>-userdebug && make bacon

Change device with your device code name. Ex.- mido, oneplus3, dumpling, etc.
	
# ======== # ======== # ======== # ======== #

## My shop keyboard-hoarders.com and keyboardhoarders.etsy.com
<img width="5328" height="4000" alt="402270884-27092a5b-7a79-4b93-8dbd-51b5fb032c02" src="https://github.com/user-attachments/assets/b1f7157e-c2ac-4501-8208-147835bfd03d" />


# Now offering wired version running Vial-QMK.  Check my shop for listings with that variant.

# keymap
<img width="984" height="1173" alt="421307589-43d4eedf-1694-4e77-b864-f2ef3c20e46b" src="https://github.com/user-attachments/assets/2053055d-8f8a-4df5-a4cd-548e88ac0575" />


# Flashing instructions.
Flash firmware:

1.Keep both halves powered on.

2. Plug in right half. > press the physical reset button(located on the inner sides) twice quickly. > That will open a new directory on your computer called nice nano. > drag and drop the settings_reset file into that directory. (after transfer it will auto unmount and may give an error. Ignore this error and continue.) > after transfer unplug right half.

3. Plug in left half. > press physical reset button twice quickly. > Drag and drop same settings_reset file into directory. > after transfer leave plugged in.

4. Press physical reset button twice. > drag and drop lily58_left firmware into directory. > after transfer unplug.

5. Plug in right half > press reset button twice again > drag and drop lily58_right firmware into directory.


# Bluetooth
ZMK uses secure bluetooth profiles.  This means only one device per profile.  If you run into bluetooth issues I recommend wiping the stored profiles with BT_CLR_ALL button combo thats found on the lower layer.  If you want to flash your own firmware I have a guide on my website over at https://keyboard-hoarders.com/pages/guides-1

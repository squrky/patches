# Patches for libvterm library by Paul "Leonerd" Evans

Library obtained like so:

`bzr clone http://bazaar.leonerd.org.uk/c/libvterm`

## r783-remove-vla.patch

Patch to remove use of VLAs which aren't compatible with MSVC compiler(s)

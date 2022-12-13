# ucShellTree
Shell TreeView Control for twinBASIC (x64 compatible), ported from VB6 version.

# Experimental

### This version is for alpha testing only; it's not meant as a general public release intended for normal use.

User control support in twinBASIC is brand new and a work in progress, and this control is complex and a lot of testing still needs to be done. But it's basically working, so I'm posting a preview for people to check out.

Currently, it must be placed at 0,0 on a Form due to resizing issues, and you'll have to manually adjust the value subtracted in UserControl_Resize if you don't want it to take up the whole form. Also, a bypass is in place for UserControl_Initialize not firing. 

# ucShellTree v2.8
Shell TreeView Control for twinBASIC (x64 compatible), ported from VB6 version.

### Beta Release

User control support in twinBASIC is brand new and a work in progress, and this control is complex and a lot of testing still needs to be done. But it's basically working, so I'm posting a preview for people to check out.

With the fixes in tB Beta 207, the control appears to be working properly and now resizing properly-- provided that you have a resize routine on your form that actually adjusts the size. If your form is resizable, the control must be too. If not, you can just put the constant size from design mode in the resize event. This is a tB bug that will hopefully be fixed soon.

One other caveat is that after being run from the IDE a few times, the program will no longer start until the IDE is restarted. This is likely related to the Terminate event not firing causing a lot of leaks, as well as other known memory leak issues currently in tB. 

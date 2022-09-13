#### About
This release contains an fix of the **cras compile error** during the installation of crouton [#4804](https://github.com/dnschneid/crouton/issues/4804).  This fix is replaces the whole target.

#### What does the fix do?
The fix changes the **CFLAGS** to pass the compile error durring setup of crouton (which prevents crouton to create the chroot).


#### Usage

- Download (git clone) original crouton!
- Download the Fix (audio target file).
- Copy Fix in original crouton target dir
- Open Terminal and `cd` into crouton directory
- Run `make` to compile crouton
- Install crouton the usual way, with the new compiled crouton

# CBT919
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 919 is from John McKown and contains the executables      *   FILE 919
//*           and source code for a port of BASH 4.2 to z/OS.       *   FILE 919
//*           This code was compiled and tested on z/OS 2.1.        *   FILE 919
//*                                                                 *   FILE 919
//*           This code incorporates all patches for BASH 4.2       *   FILE 919
//*           thru patch 53.                                        *   FILE 919
//*                                                                 *   FILE 919
//*           This same code, with executables only, is on File     *   FILE 919
//*           918.  In compliance with the GPL license, where       *   FILE 919
//*           source code has to be made available as well, we      *   FILE 919
//*           are including the entire z/OS port here, including    *   FILE 919
//*           the source code.                                      *   FILE 919
//*                                                                 *   FILE 919
//*         In compliance with the GPL license, the entire source   *   FILE 919
//*         has been included in this distribution, along with the  *   FILE 919
//*         support files used to do the configuration and compile  *   FILE 919
//*         of BASH. These reside in a PAX archive which will need  *   FILE 919
//*         to be unwound into a UNIX directory. There is an        *   FILE 919
//*         example job in the distributed PDS which can be         *   FILE 919
//*         customized to do this.                                  *   FILE 919
//*                                                                 *   FILE 919
//*           email:  john.archie.mckown@gmail.com                  *   FILE 919
//*                                                                 *   FILE 919
//*     Description of Release Level 4.2.53.                        *   FILE 919
//*                                                                 *   FILE 919
//*     This is a port of BASH 4.2, patch level 53, to the z/OS     *   FILE 919
//*     UNIX environment. It should work substantially like it      *   FILE 919
//*     does on other platforms. This includes all of the           *   FILE 919
//*     current patches, including the one for the SHELLSHOCK       *   FILE 919
//*     exploit. Of course, this functionality only applies to      *   FILE 919
//*     the BASH shell, and does not supply other GNU utilities     *   FILE 919
//*     such as GNU grep, sed, gawk, and so on. This port was       *   FILE 919
//*     developed on z/OS 2.1 and has been successfully tested      *   FILE 919
//*     on both z/OS 2.1 and 1.12. It may, or may not, work on      *   FILE 919
//*     z/OS releases prior to 1.12. It does not have any           *   FILE 919
//*     release dependent code it in, but it may have implicit      *   FILE 919
//*     dependencies in Language Environment levels due to it       *   FILE 919
//*     being written in C. This port does _NOT_ implement the      *   FILE 919
//*     "local spawn" functionality which the standard /bin/sh      *   FILE 919
//*     shell for z/OS UNIX does. This means that the               *   FILE 919
//*     _BPX_SHAREAS environment variable has no effect and         *   FILE 919
//*     there is no way to share an address space with the          *   FILE 919
//*     shell process. This could have an impact on performance     *   FILE 919
//*     and functionality of some UNIX commands and shell           *   FILE 919
//*     scripts. This lack does not stop the sharing of an          *   FILE 919
//*     address space by UNIX commands run under BASH. That is,     *   FILE 919
//*     the command can share its (not BASH's) address space by     *   FILE 919
//*     use of the _BPX_SHAREAS and the spawn() functionality.      *   FILE 919
//*     Assuming that said command is set up to do so. BASH         *   FILE 919
//*     neither enables nor disables another command's ability      *   FILE 919
//*     in this respect. One other possible "gotcha" is that        *   FILE 919
//*     many shell scripts start with a line like: "#!/bin/sh".     *   FILE 919
//*     This is supported by BASH, but results in the script        *   FILE 919
//*     running under the IBM supplied /bin/sh instead of under     *   FILE 919
//*     BASH.                                                       *   FILE 919
//*                                                                 *   FILE 919
```

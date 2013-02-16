-*- ASCII -*-

------------
About FasTeX
------------
FasTeX is a system of keyboard shortcuts for speeding up the typing of TeX
from the keyboard. It replaces any keyboard shortcut by the equivalent TeX
command or group of commands in Plain TeX, AMS-TeX, AMS-LaTeX, or LaTeX.

------------------
Benefits of FasTeX
------------------
The use of FasTeX can speed up the typical users typing input by a factor of
about 3. This speed up is achieved by not only faster inputting, but through
the fact that it avoids simple typing errors.

-----------------
FasTeX for WinEdt
-----------------
This version of FasTeX, known as FasTeX for WinEdt, favors only LaTeX
(AMS-LaTeX) commands, there are no shortcuts for TeX and AMS-TeX (unlike the
original FasTeX for Mac and UNIX). This is, as far as I know, the first port
of FasTeX to Windows.

All shortcuts (around 1550) are implemented as WinEdt Active Strings, this
was made possible only with the advent of WinEdt v6, since previous
versions had a limit of 999 maximum active strings.

------------
FasTeX Usage
------------
FasTeX does not conflict with normal English usage; however, versions of
FasTeX suitable for foreign languages would require the replacement of
certain shortcut names. To avoid language conflicts, FasTeX for WinEdt uses
space bar twice to expand all shortcuts, for example:

"beq  xph  lxa  ox  eq  intu  l0  hx  fu  fot  fof  xa  sq  pl  xh2  eb  spdt  eeq"

If you typeset only in English you can (probably) change the trigger key to a
single space bar inside "FasTeX.ini" and then load the changed script.

------------------
Installation Steps
------------------
1. Extract both "ConfigEx" and "Macros" directories to %b (or %B if you don't
   have a user profile). Note: it is safe to replace original folder contents
   when asked for.

2. Execute "_install_FasTeX.edt" Macro Script (Ctrl+F9) from
   "%b\Macros\Active Strings\FasTeX" directory.

   Remember that %b usually maps to something like this:
       "C:\Users\<user>\AppData\Roaming\WinEdt Team\WinEdt 7"
   and %B maps to:
       "C:\Program Files (x86)\WinEdt Team\WinEdt 7"

-------------------
Uninstall procedure
-------------------
FasTeX for WinEdt consists in thousands of Active Strings, in order to
uninstall FasTeX accomplish the steps below in the following order OR run the
uninstall script "%b\Macros\Active Strings\FasTeX\_uninstall_FasTeX.edt":

1. Load "ActiveStrings.ini" from "Delimiters, Active Strings,..." branch
   inside Options interface.

2. (Optional) Load your "Private.ini" from "Advanced Configuration..."

3. (Optional) Delete the "FasTeX" folder inside "%b\Macros\Active Strings"
   directory. Delete "FasTeX.ini" from "%b\Macros\ConfigEx".

-------------
Documentation
-------------
"tb49mars.pdf" - This is an outline of the FasTeX system that has been
published as an article: "Introduction to FasTeX: A System of Keyboard
Shortcuts for the Fast Keying of TeX", in TUGboat Volume 16, Number 4,
Proceedings of the Annual Tex Users Group Meeting 1995.

"FasTeX_Shortcuts_List.pdf" - This is an Alphabetical Listing of all FasTeX
shortcuts. Note that some shortcuts have changed after the publication of
this document, so a small number of (implemented WinEdt) shortcuts may differ
from this file.

The original FasTeX is available for the Macintosh and UNIX from
    http://www.cds.caltech.edu/~fastex/

Full documentation is available at
    http://www.cds.caltech.edu/~fastex/fastex_docs.html

---------------
Version History
---------------

20100531: Debut version
20120411: supports WinEdt v7 (thanks to Karl Koeller)

-----------------------
Bugs and/or Suggestions
-----------------------
Please send suggestions or bugs to:

Bernhard Enders < b g e n e t o @  gm a i l  . c o m >


Happy FasTeXing!!!

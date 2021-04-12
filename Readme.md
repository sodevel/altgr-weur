A western european keyboard layout for Windows, with AltGr dead keys
and precomposed diacritics,

Inspired by https://altgr-weur.eu and
https://github.com/thomasfaingnaert/win-us-intl-altgr, forked from
https://github.com/cjuniet/altgr-weur.

Made by means of https://github.com/39aldo39/klfc after importing
altgr-weur version v2.0 from https://altgr-weur.eu/altgr-weur into my
/usr/share/X11/xkb/symbols/us.  As klfc didn't do OEM_102 I added the
missing line in altgr-weur.klc by hand.

I had to change the name of this keyboard into an 8 character string
altgrweu and changed the filename from us-altgr-weur.klc to
altgr-weur.klc.  unix2dos was used as well as the Microsoft Keyboard
Layout Creator cannot handle files with lf's only.

Some dead keys like dead_greek don't work.

This is altgr-weur,v2.0 2021/04/12 11:27:12 by adriaan. It's the same 
layout as v1.13.

HOWTO:

0. Download the Microsoft Keyboard Layout Creator
(https://www.microsoft.com/en-us/search?q=keyboard+layout+creator).  You
need the .NET framework.

1. Load the altgr-weur.klc source file in Microsoft Keyboard Layout
Creator.  (File menu, Load Source File...)

2. Build DLL and Setup Package and follow all the prompts.  (Project menu)

3. Run the generated setup.exe.

4. https://www.windowscentral.com/how-change-your-keyboard-layout-windows-10.

5. https://superuser.com/questions/955783/setting-the-default-input-method-for-the-windows-10-login-screen.

![AltGrg](AltGr.jpg)

![Shift+AltGr](ShiftAltGr.jpg)

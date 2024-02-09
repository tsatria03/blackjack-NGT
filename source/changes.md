# blackjack game changes

Use heading level 2 to move between versions, heading level 3 to view changes in each version.

## new in version 1.0.4:
* added translation into the game! the tran.lng has been provided in the source directory. you can copy it to the lang folder with your language name to translate, as that is just the template. enjoy. you can translate and make PR, or send through telegram. the translated text should be placed after the equal sign (=).

## new in version 1.0.3:

### fixes
* fixed the bug where dollars wouldn't be removed upon losing.

### features and extras
* added *delay(5);* function to reduce CPU and fan usage.
* updated text_input to latest, optimizing CPU and fan usage at the maximum possibility.
* updated the build engine to version 2.09. do to this, all dll files have been updated, copied from the original engine file.

## new in version 1.0.2:

### fixes
* Fixed the bug of the f1 key saying "active one" instead of "activate one".

### updates
* Updated the libraries to the latest. Now, all DLL files are not needed so have been removed. However, the NVDA and SAAPI DLL files are needed so have not been removed.
* Integrated with the very latest functions provided by the engine to align with the requirements of the game.

### features and extras
* The game is now portable.
* You can no longer run the game more than once.
* The icons *new*, *hit*, *stand* have been inserted with the button to ensure readability.
* Upon the stand, it will now speak not only finish message, but also the winning message. As such, the total cards, total numbers will also be announced upon stand.
* You can now see your all cards information by pressing the *c* key.

## new in version 1.0.1 (build 2024.01.01):

### updated
* Updated the computer sequence function to determine the hit of the card, to make it more randomized.
* Updated the keyboard shortcuts, and help message. Pressing *f1* gives you help message, and *f2* gives you shortcuts, that is, if you're lazy to read the readme.
* Updated documentation readme.

### fixes
* Fixed a bug in the installer version displaying "readme" as "breadme". Please delete the *breadme* start menu shortcut!
* Fixed a bug that waits too longer than it should be in the stand.

## new in version 1.0.0:

*First release*
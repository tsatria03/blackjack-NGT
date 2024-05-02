# Blackjack game changes

Use heading level 2 to move between versions, heading level 3 to view changes in each version.

## New
* Readme has been changed to introduction, and it is now in MD format.
* You can no longer press escape to quit to the main menu while the game is active.
* Added 1 new translation string, and updated localizations.
* Updated scripts to the latest.
* For the developers to know, the sound path is now changed. Instead of using the sp string, the game now uses the engine's default sound storage setting.
* Dollars will no longer incorrect, they will now be spoken properly for the numbers as using uint64 type instead, which accepts 0 and above.
* Fixed speech interrupting.

## New in version 1.0.6
* Game language can now be saved. `data.ini` is the file.
* Added new language strings.
* Added an option into the main menu to change to a new language.
* Updated Burmese localization.
* Fixed translator bug which causes the changed language to fail getting data.
* Added Thai, Turkish, and Chinese localizations.

## New in version 1.0.5
* The game will bring you to the main menu upon pressing escape on the game area, rather than directly executing to quit.
* Added play stat into the main menu. You will see how many times you've played, the number of times you've won, draw, and lost.
* Added new translation strings. `tran.lng` file was also been updated as of it.
* Fixed the bug where you can keep playing the game even If your bet is greater than your dollars.
* Initialized the `input.reset();` function into `changebet` function to insure the previous inputs are properly reset.
* Added `play_s` function into `includes/src.ngt`.
* Added a sound when you get blackjack 21 when hit, thanks to **Tew Hong Jun**
* Added comments in `bj.ngt` to make less confuse with the codes.

## New in version 1.0.4
* Added translation into the game! The tran.lng has been provided in the source directory. You can copy it to the lang folder with your language name to translate, as that is just the template. Enjoy. You can translate and make PR, or send through Telegram. The translated text should be placed after the equal sign (=).

## New in version 1.0.3

### Fixes
* Fixed the bug where dollars wouldn't be removed upon losing.

### Features and extras
* Added **delay(5);** function to reduce CPU and fan usage.
* Updated text_input to latest, optimizing CPU and fan usage at the maximum possibility.
* Updated the build engine to version 2.09. Do to this, all DLL files have been updated, copied from the original engine file.

## New in version 1.0.2

### Fixes
* Fixed the bug of the f1 key saying "active one" instead of "activate one".

### Updates
* Updated the libraries to the latest. Now, all DLL files are not needed so have been removed. However, the NVDA and SAAPI DLL files are needed so have not been removed.
* Integrated with the very latest functions provided by the engine to align with the requirements of the game.

### Features and extras
* The game is now portable.
* You can no longer run the game more than once.
* The icons **new**, **hit**, **stand** have been inserted with the button to ensure readability.
* Upon the stand, it will now speak not only finish message, but also the winning message. As such, the total cards, total numbers will also be announced upon stand.
* You can now see your all cards information by pressing the **c** key.

## New in version 1.0.1 (build 2024.01.01)

### Updated
* Updated the computer sequence function to determine the hit of the card, to make it more randomized.
* Updated the keyboard shortcuts, and help message. Pressing **f1** gives you help message, and **f2** gives you shortcuts, that is, if you're lazy to read the readme.
* Updated documentation readme.

### Fixes
* Fixed a bug in the installer version displaying "readme" as "breadme". Please delete the **breadme** start menu shortcut!
* Fixed a bug that waits too longer than it should be in the stand.

## New in version 1.0.0

**First release**
1.2.4 changelog
- Made it improbable to click anything else while the script is running, keyboard interference is still an issue

1.2.3 Changelog
- Seamlessly browse your computer while PokeCordAutoCatcher runs.
- Fixed a bug that would make the script click and type whenever it wanted under certain conditions.
- Removed splitting and cleaning during the pyinstaller process, seemingly worked out some pixel coordinate bugs.
- Depending on user preferences, our original point for the mouse to click on might not hit the text input box, so we moved it over 50px.

1.2.1 Changelog
- Removed five-second wait from starting, considering the following changes.
- Added "auto-click", the only clicking you do during the script now is to throw your pokeball.
- Added hotkeys to start script (F11) and stop script (F12).
- Added a "safe exit" so the script cannot continue if you close the program while running the script.
- Added Screen Info dependency, so that the application only acts within the monitor your mouse is inside of, on a multi-monitor setup.
- Added Pynput dependency, so that the shortcuts to start and stop work, whether you are in the script window or not.
- Made an icon for the application.
- Changed window title from "Catch Pokémon Helper" to "PokéCord Auto Catcher vx.x.x", this will be the standard further on.
- Changed buttons to say "Pokémon" instead of "Pokemon".
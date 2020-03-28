This consists of two applescripts that are used with Voiceover screenreader and Safari on OSX.
Save_text will get the current tab's title or URL and prompt you to type a text to search, which is used with the next script
Retrieve_text will get the text saved with the first script if a text for the current active safari is found and will try to search it o the page.
It uses voiceover's search functionality and simulated keystrokes so it will not be reliable if you are holding down some key while the script is performing its action. I have to do it this way because you can't control voiceover search from Applescript.

## usage

Just drop the scripts somewhere and use the voiceover utility to assign the scripts to a keyboard shortcut. I recommend something in the keyboard commander or the trackpad commander.

The information is stored in jumpspots.plist file in my documents, which is created the first time save_text is ran.

Enjoy!
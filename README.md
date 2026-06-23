# Simple Python Keylogger

Hey guys, this is just a quick and simple keylogger script I put together using Python and the pynput library. I made this to learn more about how background listeners and keystroke tracking work in security auditing.

## How it works
The script runs in the background and listens to your keyboard. It separates normal letters/numbers from special keys (like Shift, Space, Enter) so the final output doesn't look totally messy. Everything you type gets saved directly into a local file called `log.txt`.

## How to run it
1. Make sure you install pynput first or it won't work:
   pip install pynput

2. Run the script from your terminal/command prompt:
   python KeyloggerProject.py

3. To stop the logger, just hit the 'Esc' key on your keyboard.

## Note / Disclaimer
Please only run this on your own machine. I made this purely for educational purposes and testing out my python skills, so don't go using it for anything dumb or unauthorized.


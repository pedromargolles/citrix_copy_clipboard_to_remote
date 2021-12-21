# citrix_copy_clipboard_to_remote
A python script to copy text from clipboard to a remote Citrix session simulating key presses when remote Copy/Paste is not allowed

## Install dependencies:
pip install pyperclip

pip install pynput

## Instructions:
- Copy some text (ex., https://loremipsum.io/generator/).
- Run the script with: python copy.py in a local terminal.
- You have 5 seconds (this time can be modified) to activate a remote Citrix window and place cursor where you want your local clipboard text is copied (ex., remote notepad).
- Script will loop through your local clipboard text letters and characters simulating their respective key presses.
- Text will be progresively be copied in remote session active window as if you were written it manually **[Warning: Do not change neither active window nor cursor position while text is being copied].**

## Optional
Bind script execution with a custom local hotkey shorcut. Then, your clipboard text will be copied automatically to remote session after 5 seconds.

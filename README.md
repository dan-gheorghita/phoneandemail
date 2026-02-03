# phoneAndEmail.py

**Phone and Email Extractor Script**

This Python script uses regular expressions to extract phone numbers and email addresses from the text on the system clipboard. It then copies the extracted information to the clipboard.

**Key Features:**

1. **Phone Number Extraction:** The script uses a regular expression to find phone numbers in the format `XXX-XXX-XXXX` or `XXX XXX XXXX` with an optional extension `xXXX`.
2. **Email Address Extraction:** The script uses another regular expression to find email addresses in the format `username@domain.name`.
3. **Clipboard Interaction:** The script uses the `pyperclip` library to read and write text to the clipboard.

**How it Works:**

1. The script imports the necessary libraries: `pyperclip` for clipboard interaction and `re` for regular expressions.
2. It defines two regular expressions: `phoneRegex` for phone numbers and `emailRegex` for email addresses.
3. It reads the text from the
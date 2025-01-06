# Lyrics_with_python
#@codewith_kareena

import time

import sys

# Text to display

text = ("/*your fav song*/")
# Display each letter one by one

for char in text:

sys.stdout.write(char) # Print one character at a time

sys.stdout.flush() # Ensure it appears immediately

time.sleep(0.15) # Delay between letters

print() # Move to a new line after the text

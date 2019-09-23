# explanation
- vscode supports hot diff, the diff between the **current buffer** and the **versioned file**.
- as it handles current buffer rather than current file(in the hard disk), hot diff shows the same result no matter the buffer is saved or not.

# thin columns and red triangle
vscode uses **thin columns** and **red triangle** to signify hot diff.
## green column
added lines
## blue column
modified lines
## red triangle
deleted lines

# clicking thin columns or red triangle
clicking thin columns or red triangle **toggles unified diff**.
---
actions can be conducted in the popup diff:
- stage change
- revert change
- next diff and previous diff

The PrefixedDuplicator takes a list of text lines and duplicates each line with one or more prefixes, 
with optional find/replace and formatting controls.

Typically used for generating many prefixed variants of quoted strings, such as utility class names or configuration entries.


<img width="763" height="676" alt="Screenshot_PrefixedDuplicator" src="https://github.com/bryonyleachdev/PrefixedDuplicator/blob/a9b12d6cd54845f8f437bfddad3e109262bd0995/Screenshot_PrefixedDuplicator.jpg" />

Input box: paste multiple lines of text (one per line).

Prefixes field: comma-separated prefixes to add in front of each line.

Find / Replace: optional text substitution before duplication.

Include original text toggle: keeps the unmodified lines in the output.

Include indentation toggle: adds fixed leading spaces to each output line.

Modes:

Interleafed: original line followed immediately by its prefixed versions.

Batched Results: all originals first, then prefixed lines grouped by prefix.
<br><br>

Output: results are shown in the output area.

Copy button: copies the output to the clipboard.

Clear buttons: empty individual input fields.

<br><br><br>

Processing behavior:

Each line is trimmed (leading and trailing spaces removed).

The first character of each line is removed before prefixing (assumes a leading quote).

Prefixes are inserted right after a new opening quote.

# Acronyms-Word
Automatically read a Word document or latex .tex file and build a list of the
used acronyms

All files contained in the indicated input folder will be scanned for acronyms
and a word table will be the output contained inside 'Acronyms Table.docx'.
Definitions of the acronyms will also tried to be inferred from the text.

## Known limitations
- the definition of acronym is set to be every string exclusively in uppercase
   which is made by at least two characters

## Tricks
- it is possible to change the acronym definition modifying the ``PAT_ACRONYM``
   variable;
- it is possible to force the research of acronym definition in the entire document
   and not only in the paragraph where the acronym appears for the first time.
   In order to do that, one can simply comment the `break` instruction in the 
   `check_definition()` function.

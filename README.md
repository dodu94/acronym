# Acronyms-Word
Automatically read a Word document and build a list of the used acronyms

Posizionando questo script nella stessa cartella del file su cui si sta
lavorando (vedi la sezione user input) viene creato un file denominato
'Acronyms Table.docx' che contiene la tabella degli acronomi di un documento
(da editare e verificare).

## Limitazioni note
- Tutto ciò che viene scritto con più di due lettere maiuscole consecutive
   è considerato un acronimo, occhio ai titoli in maiuscolo che saranno da
   eliminare. Per questo motivo l'attivazione della lettura delle tabelle può
   essere disattivata

## Tricks
**cambia il codice solo se sai quello che fai**
- è possibile cambiare la definizione dell'acronimo cambiando ``PAT_ACRONYM``
- è possibile forzare la ricerca delle definizioni degli acronimi in tutto il documento (e non solo la prima volta che l'acronimo compare) commentando/eliminando il `break` nel loop principale.

# CornellNotesTemplate
LaTeX code and SVG for a Cornell Notes [Stylus Labs Write template](https://github.com/styluslabs/templates).

Adapted by Florian Lengyel from code posted at https://tex.stackexchange.com/questions/70570/cornell-notes-a-lyx-or-latex-solution-needed/145779#145779 
by user sgmoye https://tex.stackexchange.com/users/11131/sgmoye under a [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/legalcode). 
See the [Timeline for Cornell Notes - A lyx or latex solution needed
Current License: CC BY-SA 3.0](https://tex.stackexchange.com/posts/145779/timeline).

## Adaptation

The adaptations to sgmoye's original LaTeX code were as follows. The command to draw grid lines were replaced with the standard twenty-seven ruled lines. The step size was set grid height divided by 27. The cue section width and the summary section height were modified accordingly. Page numbers were suppressed and the margins were modified.

## Compilation

The LaTeX file ```CornellNotesTemplate.tex``` was compiled with ```MiKTeX``` to ```CornellNotesTemplate.dvi```. The dvi file was converted to Scalable Vector Graphics with the following command.

>  dvisvgm -p1 -bpapersize --stdout CornellNotesTemplate.dvi > CornellNotes.svg

## Usage

The file ```CornellNotes.svg``` is opened in [Stylus Labs Write](https://github.com/styluslabs), which will open a "Foreign docment" dialog informing you that "[t]his file does not appear to be a Write document. Saving with Write could result in data loss - you will be prompted to save a copy." Select "Use as background" and then save the file under a new filename -- don't overwrite ```CornelNotes.svg```! See [Stylus Labs Write template](https://github.com/styluslabs/templates) for further details.

## License 

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International Public License](https://creativecommons.org/licenses/by-sa/4.0/legalcode) in addition to the original CC BY-SA 3.0 license. The CC BY-SA 4.0 is compatible with the CC BY-SA 3.0 license, as stated under [Compatible Licenses](https://creativecommons.org/share-your-work/licensing-considerations/compatible-licenses). The terms of both the CC BY-SA 4.0 license and the original CC BY-SA 3.0 license apply to this adaptation (downstream users have a choice).

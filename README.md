# Thesis: Studies on bridged Troponophanes
## Title: Studies on 2,7-bridged Tropones - \[4\](2,7)-Troponophanes -

### Annotations

This is my thesis written in german, I release it into the public domain.

This publication was written 1975 on an Olivetti Typewriter Praxis 48 \*).

After more than 40 years I decided to digitize my work and publish it electronically via internet.

The original manuscript was still existing and thus scanned with an Epson XP 810 using its automatic document feeder. The individual pages were stored in TIF format, transformed into normalized PNGs with 300 dpi resolution by ImageMagick's convert and subjected to OCR with the Java program VietOCR which internally uses tesseract. This gave the thesis in raw text format.

The final formatting of the text was done under LaTeX (lastly TeX Live 2020) first under macOS with TeXShop and after switching to Fedora Linux with TeXWorks as text editor. Using the monospaced font Bera Sans Mono the type face matches closely the original Quadrato font of the Olivetti machine.

The chemical formulas were drawn with the ChemFig (package version 1.56 dated 13 July 2020).

The spectra and other diagrams were cut out of the scanned image files and included into the TeX document.

The final output (compiled at least in two passes) resulted in thesis-1975.pdf in Adobe's portable document format.

With a special perl-based command in terminal this task is automagically simple:

```
    latexmk -pdf Thesis-1975.tex
```
Alternatively use your preferred GUI in known manner.

You can learn a lot about LaTeX and TeX as I had to in doing this piece of work ...

***
\*) The mechanical part was projected 1964 by Rinaldo Salto, the design was done by Ettore Sottsass in cooperation with Hans von Klier. Of grey color with green keys the whole machine has a weight of more than 9 kilograms.

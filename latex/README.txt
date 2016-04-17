- Place source files of figures (e.g. PSD, DIA, PPTX) in diagrams/
- Place figures references in paper (e.g. eps) in figures
- Place raw images collection in images/
- refs.bib is the bibtex file
- ase.bbl is the processed bibliography included in the paper
- Place tex files in sections within following rules:
    * Each section is defined by a tex file, e.g. mySection.tex
    * When a section has sub-sections, they are defined within their own folder,
      e.g. mySection.tex has a sub-section ==> mySection/mySubSection.tex
    * Recursively do the same thing for sub-section, unless un-necessary (e.g. for paragraphs or very short sub-sub-sections)
- Please don't commit garbage files like .aux .dvi .log .blg etc...
- Do commit .pdf .bib .bbl
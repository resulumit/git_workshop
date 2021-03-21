# Version Control and Collaboration with Git and

This repository holds the materials for a workshop on writing reproducible research papers with R Markdown, first taught at [Campus Luzern](https://www.campus-luzern.ch/) in March 2021.

Unless otherwise noted, all material is copyright Resul Umit, licensed [CC-BY-SA 3.0](https://github.com/resulumit/git_workshop/blob/master/LICENCE.md). An easy to read summary of this permissive licence is available on the [Creative Commons website](https://creativecommons.org/licenses/by-sa/3.0/).

## Contents

The workshop is divided into six parts. Most parts include exercises &mdash; 30+ in total.


|[]() |      |
|------|------|
| **Part 1. Introduction** <br /> - e.g., getting ready to work together | **Part 4. What to Version** <br /> - e.g., using a `.gitignore` file | 
| **Part 2. Tools** <br /> - e.g., downloading workshop material | **Part 5. Collaboration** <br /> - e.g., working on the same remote repository | 
| **Part 3. Version Control** <br /> - e.g., versioning by typing commands | **Part 6. Third-Party Applications** <br /> - e.g., using GitHub Desktop |
   

##  Material

Below are the workshop materials kept in this repository.

- `manuscript\reproduce_this.pdf`
    - a document, formatted in Word but saved as PDF, to be re-created with R Markdown 
    - random sentences in the document are generated with the `stringi` package  (Gagolewski, 2020)
    - figures and tables are based on a fabricated dataset (`journals.csv`, see below)
    - key sections in-need of attention are highlighted

- `manuscript\journals.Rmd`
    - an R Markdown document to work on during the workshop
        - includes unformatted text from `reproduce_this.pdf` to save time
        - major components, such as paragraphs and tables, are numbered and marked in comments to facilitate navigation
        
- `manuscript\references.bib` 
    - a BibTeX document with three fabricated references
    
- `manuscript\apa_7th.csl`
    - a Citation Style Language document, with APA (7th Edition) referencing style (Wiernik, 2020)

- `data\journals.csv`

    - a dataset created with the `fabricatr` package (Blair et al., 2019), imagined to explore the Google Scholar rankings of fictitious journals
    
    - includes the following variables 
        - **name**: journals (1090 random titles)
        - **origin**: geographic origins (five continents)
        - **branch**: major discipline of journals (four branches)
        - **since**: time of first publication (years)
        - **h5_index**: H5 Index (integers)
        - **h5_median**: H5 Median (integers)
        - **english**: English (1) *vs.* other-language (0) journals
        - **subfield**: subfield (1) *vs.* generalist (0) journals
        - **issues**: number of issues published per year (integers)
   

- `image\google_scholar.png`
    - a screeenshot image of the Google Scholar homapage, copyright Google, LLC 

- `presentation\rmd_workshop.pdf`
    - slides in PDF format
    - HTML version is available at <https://resulumit.com/teaching/rmd_workshop.html>
        - offers, among others, the ability to scroll across long codes on some slides

- `presentation\rmd_workshop.Rmd`
    - an R Markdown file behind the slides, produced with the `xaringan` package (Xie, 2020)
        
- `test\run_this.R`
    - an R script that 
        - installs the packages needed for the workshop
        - attempts to knit an R Markdown into PDF file
    - useful for tasking participants with a pre-workshop setup
        
- `test\the_test.Rmd`
    - an R Markdown file, to be used for the attempt in `test\run_this.R`

 
## References

Blair, G., Cooper, J., Coppock, A., Humphreys, M., Rudkin, A. and Fultz, N. (2019). [fabricatr: Imagine your data before you collect it](https://cran.r-project.org/web/packages/fabricatr/index.html). R package, version 0.10.0.

Gagolewski, M. (2020). [stringi: Character String Processing Facilities](https://cran.r-project.org/web/packages/stringi/index.html). R package, version 1.4.6.

Wiernik, B. M. (2020). [American Psychological Association 7th edition (no ampersand)](https://www.zotero.org/styles/apa-no-ampersand). Citation style language file, version 1.0.

Xie, Y. (2020). [xaringan: Presentation Ninja](https://cran.r-project.org/web/packages/xaringan/index.html). R package, version 0.18.


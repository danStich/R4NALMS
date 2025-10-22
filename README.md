# R4NALMS

Files and GitHub page related to R workshops for the 
International North American Lake Management Society (NALMS) 
Symposium


## Workshop participants
The data for the workshop are stored in the `data` folder. 

You can download these data files individually by clicking on the 
`data` folder, then clicking on data file name, then clicking on 
download button that is two buttons to the right of the `Raw` button.

Alternatively, you can download the entire repository as a compressed
folder by clicking on the green code button in the main 
repository. This will also provide you with the markdown files
and R code used to generate the workshop examples.


## Repository structure
Files in the main directory include `rmarkdown` (.Rmd) files used to 
generate web pages (.html) that are managed and styled through 
YAML and CSS code.

Most folders (sub-directories) include `site_libs` and cached files 
for markdown-generated html pages, all of which is 
generated using `render_site()` from the `rmarkdown` package.

The `data` sub-directory contains data used for workshop examples.

The `image` sub-directory contains images used in rendered websites.
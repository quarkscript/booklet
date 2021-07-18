#### rasterized pdf or djvu combiner
[**rpdc**](rpdc) - bash script to process pdf or djvu documents. It is some kind of  advanced alternative to [**mbkl**](mbkl) and it could:
- convert to booklet / split double pages to single pages / glue single pages to double
- apply imagemagick filters to each page
- run in different stages / multipass processing / lets manual intervention

and it has a 'gui' (Xdialog required)
> **for more help see script code or run `./rpdc -h`**
#### pdf -> 'booklet'.pdf (a4)
[**mbkl**](mbkl) - bash script to make pdf booklets. It use ghostscript and it could:
- make simple booklet / make complex booklet
- split to odd and reversed even pages / split to parts with custom pages count
- display selected page with scale and position shift for testing that parameters.
> **for more help see script code or run `./mbkl -h`**
###### Sometimes useful simple scripts
- [glue_pdfs](glue_pdfs)
- [remake_pdfs](remake_pdfs)
- [gcfdp](gcfdp) - gen cover for pdfs and djvus

# jewish_texts

This is a collection of texts used for Jewish prayer. 
1. Grace after meals
2. A guide for the Gabbai of a synagogue to use
3. A full siddur. The siddur is in accordance with Western Ashkenazi custom as outlined by Machon Moreshes Ashkenaz (http://www.moreshesashkenaz.org/)

Since the name of G-d is holy, there is also a python script used to convert the shem-havaya into the (somewhat moreso) printer friendly double-yud.

One must be running XeLaTeX (not just LaTeX) in order to build the code.

The Bidi package is necessary in order for Hebrew text to be properly displayed in XeLaTeX.

Bidi and Hebrew have sometimes caused unexpected results in the page layout, so creative workarounds were necessary. This results in some ugly code in some parts.

**Packages used**: fancyhdr, longtable,paracol,multirow,multicol,xcolor,pbox, wrapfig, mdframed,array,graphicx, afterpage, marginnote, morefloats, marginfix, xunicode, adforn, amssymb, tikz, tabularx, ragged2e, libertine, setspace, sectsty, nowidow, titlesec, titlesec, fontspec, bidi.

Shlomo font available under SIL OFL

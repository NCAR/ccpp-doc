# ccpp-doc
Documentation for the [GMTB](http://www.dtcenter.org/GMTB/html/) Common Community Physics Package (CCPP).
A viewable version of the latest documentation resides
[here](https://dtcenter.org/community-code/common-community-physics-package-ccpp/documentation).

## Notes to Developers
This repository contains the technical documentation for CCPP. The documentation is generated with
Sphinx, using the reStructuredText (.rst) files in the CCPPtechnical/source directory.  Output can
be generated in HTML or PDF formats.

## Creating the technical documentation

To generate the technical documentation:

1. Clone the repository.
```
git clone https://github.com/NCAR/ccpp-doc.git
```
2. Build the HTML document.
From the directory above source and build, the ccpp-doc project directory:
```
cd ccpp-doc/CCPPtechnical
make html
```
This will generate a HTML files in ./build/html.
3.  Build the PDF document.
```
cd ccpp-doc/CCPPtechnical
make latexpdf
```
This will generate a PDF file ./build/latex/CCPPtechnical.pdf.

# DWS Book Templates

When I started writing an eBook with LibreOffice Writer I could not find
a template that worked and demonstrated the styles used within the
template, so I created two. In March 2021, the the first version of the
novel template won a prize in a [template
contest](https://adfinis.com/en/blog/winners-of-the-libreoffice-template-contest-2020/)
and paid for half of my new 13" 2020 MacBook Air M1. Now I can a faster
writer than ever ;=}

## What's Included

1.  LibreOffice Writer templates for both a novel and light technical
    books containing a style sheet and sample content for a book. Both
    templates work for print/paperback (PDF) and eBook (EPUB 3) formats.

2.  There is also a version of the technical template that is
    reformatted for printed technical reports.

3.  A step-by-step set of instructions (DWS-BookTemp-Instructions.pdf)
    for:

    a.  Setting up the environment on Mac or Windows PC.
    b.  Starting a book project and producing a PDF file for viewing and
        printing on US letter (8.5″ x 11″) paper, and an EPUB 3 for
        viewing and submitting to Amazon. **Note:** Amazon now wants
        EPUB files for submission!
    c.  Creating both the JPEG cover for an eBook and a PDF file for the
        front cover, back cover and spine of a paperback book.
    d.  Final post processing for paperback printing.
    e.  Producing an EPUB 3 file for viewing and submitting to book
        distributors.

4.  A LibreOffice Calc Worksheet to calculate the dimensions for a
    paperback cover. (DWS-Book-Calc.ods).

## Files Included

-   DWS-BookTempNovel in PDF, EPUB 3 and ODT source (\~65 pages)
-   DWS-BookTempTech in PDF, EPUB 3 and ODT source (\~75 pages)
-   DWS-BookTempReport in PDF and ODT source (\~10 pages)
-   DWS-BookTempMaster only in ODT source (\~75 pages)
-   DWS-BookTemp-Instructions in PDF and ODT source (\~40 pages)
-   Calc/DWS-BookCalc.ods (a worksheet)

The PDF and EPUB 3 versions are included in this repository so that you
can see how a sample book would be formatted as a paperback or an eBook.

## Getting Started

****W****arning: ****When viewing PDF files at GitHub, hyperlinks and
links in the Table of Contents ***may*** not be clickable! In the actual
PDF files, when downloaded they are.

The file **DWS-BookTemp-Instructions.pdf **contains the instructions
for:

-   Software Installation on macOS & Windows.
-   New Book Project Setup---The instructions to process the template
    into a paperback, EPUB 3 and Kindle MOBI files.
-   Post Processing Steps---The final steps prior to producing an eBook
    or paperback for production.
-   Creating both an eBook cover and a paperback book cover.
-   Other useful stuff.

## Prerequisites

None. It is assumed that you know how to use basic word processing
software such as LibreOffice Writer, Microsoft Word or Apple's Pages.

## Installing

-   See **DWS-BookTemp-Instructions.pdf**

## Running the tests

If you follow the examples in the instructions, you will have a sample
8.5x11ʺ paperback, an EPUB 3 eBook built using the templates as a test.
Each showing the named style elements. **DWS-BookTempNovel\_Epub3.epub
**is what the novel will look like. You can view this in any EPUB
reader, including Amazon's Kindle Previewer.

You can follow the same instructions using the DWS-BookTempTech template
and get an example from the light technical template.
**DWS-BookTempTech\_Epub3.epub **is now included in the repository.

## Versioning

LibreOffice Writer isn't a good format for software version control.
However, each file contains a date-formatted version ID near the top of
the file similar to the two lines below.

**File:** README.odt **Title**: README.odt **Author:** David Snow

**Last Modified:** 2020-09-14 03:22 PM by David Snow ― 306 words 2
pages.

Also each template has an *Edition Number* near its beginning. Usually
the whole set of templates and the instructions are updated as a set and
the edition number is incremented.

## Authors

David W. Snow

## License

This project is licensed under **** a CC0 (****[****CC0 1.0
Universal****](https://creativecommons.org/publicdomain/zero/1.0/)****)
license.****

## ***Edition*** History (Git tag)

-   1.1.0 January 2021 The basic templates (Novel & Technical) plus
    instructions. The novel template won
    [Adfinis](https://adfinis.com/en/)' template contest. See
    [thier](https://adfinis.com/en/blog/winners-of-the-libreoffice-template-contest-2020/)
    blog.
-   1.2.1 June 2021 Updated several sections and a report template
    (DWS-BookTempReport) added. Tested with LibreOffice Writer 7.1.4.2

## ** Notes:**

****README.md is created with pandoc via:****\
pandoc README.odt -o README.md****

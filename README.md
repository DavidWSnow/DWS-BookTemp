## Description

When I started writing an eBook with LibreOffice Writer I could not find
a template that worked and demonstrated the styles used within the
template, so I created two. In March 2021, the first version of the
novel template won a prize in a [template
contest](https://adfinis.com/en/blog/winners-of-the-libreoffice-template-contest-2020/)
and paid for half of my 13" 2020 MacBook Air M1. Now I can write 50%
faster than before ;=}

The Novel and Technical book templates are designed such that you can
easily produce and eBook (EPUB3) file for Amazon Kindle and a PDF file
for a paperback from a common source file.

## Author

David W. Snow

## License

This project is licensed under **** a CC0 (****[****CC0 1.0
Universal****](https://creativecommons.org/publicdomain/zero/1.0/)****)
license.****

## Prerequisites

****None. ****It is assumed that you know how to use basic word
processing software such as LibreOffice Writer, Microsoft Word or
Apple's Pages.****

## What's Included

1.  LibreOffice Writer templates for both a novel and light technical
    books containing a style sheet and sample content for a book. Both
    templates work for print/paperback (PDF) and eBook (EPUB3) formats.
    Note: Amazon Kindle now wants EPUB formated files for eBooks, so
    these templates work for Amazon Kindle books.

2.  There is also a version of the technical template that is
    reformatted for printed technical reports.

3.  A step-by-step set of instructions for:

    a.  Setting up the environment on Mac or Windows PC.
    b.  Starting a book project and producing a PDF file for viewing and
        printing on 6″ x 9″ paper, and an EPUB3 for viewing and
        submitting to Amazon, Apple, etc.
    c.  Creating both the JPEG cover for an eBook and a PDF file for the
        front cover, back cover and spine of a paperback book.
    d.  Final post processing for paperback printing.
    e.  Producing an EPUB3 file for viewing and submitting to book
        distributors.

4.  A LibreOffice Calc Worksheet to calculate the dimensions for a
    paperback cover.

## Changed in Version 25.01.0

-   Changed the format of the version/edition number.
-   Make a separate *DWS-BookTempNovel *and *DWS-BookTempTech* that are
    much leaner and not just copies of the relevant sections of
    *DWS-BookTempMaster. *
-   The novel was resized to 5"x8". The Tech and Master templates were
    resized to 6"x9".
-   Make an EPUB3 file for *DWS-BookTempMaster *and dropped the two
    other ebook files.

## Files Included

****W****arning: ****When viewing PDF files at GitHub, hyperlinks and
links in the Table of Contents ***may*** not be clickable! In the actual
PDF files, when downloaded they are.

1.  DWS-BookTemp-Instructions in
    [PDF](https://github.com/DavidWSnow/DWS-BookTemp/blob/main/DWS-BookTemp-Instructions.pdf)
    and ODT source (\~40 8.5"x11" pages)
2.  DWS-BookTempNovel in
    [PDF](https://github.com/DavidWSnow/DWS-BookTemp/blob/main/DWS-BookTempNovel.pdf)
    and ODT source (\~40 5"x8" pages)
3.  DWS-BookTempTech in
    [PDF,](https://github.com/DavidWSnow/DWS-BookTemp/blob/main/DWS-BookTempTech.pdf)
    and ODT source (\~40 6"x9" pages)
4.  DWS-BookTempReport in
    [PDF](https://github.com/DavidWSnow/DWS-BookTemp/blob/main/DWS-BookTempReport.pdf)
    and ODT source (\~6 8.5"x11" pages)
5.  DWS-BookTempMaster in PDF, EPUB3 and ODT source (\~130 6"x9"pages)
6.  OutTakes.odt a holder for work that has been "cut" out of your book
    and that you might want to use later.
7.  Calc/DWS-BookCalc.ods (a worksheet)

## Getting Started

The file [**DWS-BookTemp-Instructions.pdf
**](https://github.com/DavidWSnow/DWS-BookTemp/blob/main/DWS-BookTemp-Instructions.pdf)contains
the instructions for:

-   Software Installation on macOS & Windows.
-   New Book Project Setup---The instructions to process the template
    into a paperback, EPUB3 and Kindle files.
-   Post Processing Steps---The final steps prior to producing an eBook
    or paperback for production.
-   Creating both an eBook cover and a paperback book cover.
-   Other useful stuff.

## Running tests

If you follow the examples in the instructions, you will have a sample
6x9ʺ paperback (PDF), an EPUB3 eBook built using the templates as a
test. Each showing the named style elements.
**DWS-BookTempNovel\_Epub3.epub **is what the novel will look like. You
can view this in any EPUB reader, including [Amazon's Kindle
Previewer](https://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000765261).

You can follow the same instructions using the DWS-BookTempTech template
and get an example from the light technical template.
**DWS-BookTempTech\_Epub3.epub **is now included in the repository.

## Version Control

LibreOffice Writer's ODT files are not a good format for software
version control. However, each file contains version ID, usually near
the top of the file, similar to the image below.

![](Pictures/10000001000005660000011435BAC746.png){width="6.4252in"
height="1.2827in"}

Also, each template has an *Edition Number* near its beginning. Usually
the whole set of templates and the instructions are updated as a set and
the edition number is incremented.

## ***Edition*** History (Git tag)

-   v1.1.0 January 2021 The basic templates (Novel & Technical) plus
    instructions. The novel template won
    [Adfinis](https://adfinis.com/en/)' template contest. See
    [thier](https://adfinis.com/en/blog/winners-of-the-libreoffice-template-contest-2020/)
    blog.
-   v1.2.1 June 2021 Updated several sections and a report template
    (DWS-BookTempReport) added. Tested with LibreOffice Writer 7.1.4.2
-   v25.01.0 Jan 2025 Applied more *Chicago Manual of Style* / Turabian
    style elements to the report template. Tested with LibreOffice
    Writer 24.8.4.2 and Jutoh v3.16.4. I also charged to the same format
    of version numbering as LibreOffice at this time. It includes an
    OutTakes.odt file in the package. This is the file that I store
    content that I have written, but haven't decided where to use.

## ** Notes:**

****README.md is created with pandoc via:****\
pandoc README.odt -o README.md****

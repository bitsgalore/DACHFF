# DACH 2016 - file formats

Johan van der Knijff, KB / National Library of the Netherlands

Below is an overview of the topics that are covered by the file formats session with suggested background reading for each topic. It also lists some advanced topics that are not addressed in the session, but which may be useful for interested readers. Note that this overview is a work in progress, and I will add further updates during the week leading up to the session on 3 March.

After the session I will also make the presentation slides available here.

## Introduction to digital data 

* Bits and bytes
* Representation of numbers
* Representation of text characters

### Background reading

* [Binary data](https://en.wikipedia.org/wiki/Binary_data)
* [Counting in binary](https://en.wikipedia.org/wiki/Binary_number#Counting_in_binary) (you can skip the other sections in this article!)
* [Practice converting between decimal and binary representation](http://acc6.its.brooklyn.cuny.edu/~gurwitz/core5/nav2tool.html)

## Text-based formats

* ASCII

### Background reading

* [ASCII - American Standard Code for Information Interchange](https://en.wikipedia.org/wiki/ASCII)
* [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets](http://www.joelonsoftware.com/articles/Unicode.html) - explains the most widely-used approach for representing text characters that are not covered by ASCII. Advanced topic that is not covered by this session, but Unicode's ubiquity means you'll most likely run into it sooner or later.

## Binary formats

* Representation of RGB image data

## Mixed binary / text formats

* PDF
* DOCx

## File format specifications

Some examples:

* [Portable Document Format 1.7, First Edition](http://wwwimages.adobe.com/content/dam/Adobe/en/devnet/pdf/pdfs/PDF32000_2008.pdf) (748 pages!)
* [TIFF Revision 6.0](http://partners.adobe.com/public/developer/en/tiff/TIFF6.pdf)
* [EPUB 3.01](http://www.idpf.org/epub/301/spec/epub-overview.html) (actually made up of 4 separate parts)
* [Office Open XML File Formats](http://www.ecma-international.org/publications/standards/Ecma-376.htm) (docx, xlsx, pptx, etc.)
* [Portable Network Graphics (PNG) Specification](https://www.w3.org/TR/PNG/)

Note: this is just to give you an idea what a file format specification looks like. Obviously I don't expect anyone to actually read through the whole of any of these documents!

## Open formats vs proprietary formats

* [Open format](https://en.wikipedia.org/wiki/Open_format) - includes list of examples.
* [Proprietary format](https://en.wikipedia.org/wiki/Proprietary_format) - includes list of examples.

## Format validation

* [Online HTML validator](https://validator.w3.org/)
* [Online EPUB validator](http://validator.idpf.org/)

## Information about file formats on the web

* [Archive Team File Formats Wiki](http://fileformats.archiveteam.org/) - Collaborative effort at bringing together information about file formats, initiated by the [Archive Team](http://archiveteam.org/index.php?title=Main_Page) collective. Very good resource with wide coverage of formats.
* [Sustainability of Digital Formats](http://www.digitalpreservation.gov/formats/index.shtml) - information on file formats by the Library of Congress, with focus on sustainability.

<!--
## Extra: hex editing (advanced topic, not covered by session!) 

A [hex editor](https://en.wikipedia.org/wiki/Hex_editor) is a computer program that allows you to view / inspect / edit files at the level of individual bytes. Hex editors represent each byte as a pair of [hexadecimal](https://en.wikipedia.org/wiki/Hexadecimal) digits. The reason for this is that for a human it is much easier to read hexadecimal (where each byte is represented as exactly 2 symbols) than binary. This can be a bit confusing at first, but it doesn't usually take much time to get used to it. 

Here's a good explanation of the basic concepts:

[Basic Hex editing guide](http://clockworkcore.org/hex.html)

Then try for yourself in this browser-based hex editor (no need to install anything!):

[Hexed.it](https://hexed.it/)
-->
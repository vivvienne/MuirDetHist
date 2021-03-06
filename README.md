# MuirDetHist
An ongoing project to convert [Thomas Muir's works on the history of determinants](https://en.wikipedia.org/wiki/Thomas_Muir_(mathematician)#Publications_by_Sir_Thomas_Muir) into Markdown format. My aim is to convert the following books:

1. *The theory of determinants in the historical order of development*
   1. (1906) vol 1 - [*General and special determinants up to 1841*](https://quod.lib.umich.edu/u/umhistmath/acm9350.0001.001/6?view=image&size=100)
   2. (1911) vol 2 - [*The period 1841 to 1860*](https://quod.lib.umich.edu/u/umhistmath/acm9350.0002.001/6?view=image&size=100)
   3. (1920) vol 3 - [*The period 1861 to 1880*](https://quod.lib.umich.edu/u/umhistmath/acm9350.0003.001/6?view=image&size=100)
   4. (1923) vol 4 - [*The period 1880 to 1900*](https://quod.lib.umich.edu/u/umhistmath/acm9350.0004.001/6?view=image&size=100)
2. (1930) *Contributions To The History Of Determinants 1900-1920*

## Progress
Please note that my main aim is to read the book, manually correcting on the way, so the conversion process is expected to be very slow.
- vol 1 ![](https://progress-bar.dev/9/?scale=491&width=500&color=babaca&suffix=/491)
  - [single markdown file](vol1.md)
  - [read on the web](https://vivvienne.github.io/MuirDetHist/)

## Implimentation (conversion) details

- The target format is planned to be Markdown with raw html (for marking additional typographical formatting, especially small caps) and TeX (for math).
- The markdown files will not be an exact reproduction of the original text. Generally, book-format specific information that are not necessary for normal viewing of continuous markdown files, such as page headers and footers, page numbers, and pagination in general will be omitted. Also, line breaks in a single paragraph and line-end hyphens in the original text will not be preserved.
- On the other hand, typographical formatting (such as italics and small caps) will be preserved.
- Conversion is done by manually visual inspection, that is, comparing the OCR text to the pdf file and correcting errors.
- The online version differs in minor details to optimize for online viewing. For example, ToC tables are converted into unordered lists, subsections in chapters may be divided into separate pages and their internal subsection structure flattened.
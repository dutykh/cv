<!-- Author: Dr. Denys Dutykh (Mathematics Department, Khalifa University of Science and Technology, Abu Dhabi, UAE) -->

# cv: the curriculum vitae of Denys Dutykh in PDF

This repository holds the curriculum vitae of Dr Denys Dutykh, mathematician at the Mathematics Department of Khalifa University of Science and Technology (Abu Dhabi), and nothing else: three documents, each kept at two fixed addresses, six PDF files in all.

## Contents

| File | Document |
|------|----------|
| `Modern/build/ModernFullCV-Dutykh.pdf` | Full CV in the modern style: sans-serif type, section icons, and a page of highlights counted from the entries themselves |
| `Classic/build/ClassicFullCV-Dutykh.pdf` | Full CV in the classic style: serif type, numbered sections, a table of contents |
| `Short/build/ShortCV-Dutykh.pdf` | Short CV of two pages |
| `out/ModernFullCV-Dutykh.pdf` | Same file as the modern full CV above |
| `out/ClassicFullCV-Dutykh.pdf` | Same file as the classic full CV above |
| `out/ShortCV-Dutykh.pdf` | Same file as the short CV above |

The two full CVs carry the same content in two designs; the short CV has its own condensed content. The files in `out/` are byte-for-byte copies of those in the three `build/` folders. Every one of these paths is fixed and will not change, because websites and tools download the documents from their raw addresses, such as

https://raw.githubusercontent.com/dutykh/cv/main/Modern/build/ModernFullCV-Dutykh.pdf

## Where the files come from

The documents are typeset with Typst from the sources kept in the repository CVDutykh. There `make all` compiles the three styles, and `make publish` copies the six PDFs into this repository, committing only when they have changed. Nothing here is edited by hand, so each commit of this repository is one new version of the CV. His website shows the current version at

https://www.denys-dutykh.com/cv/modern

## Licence

No licence is granted for these documents: all rights are reserved.

## Author

Dr. Denys Dutykh, Mathematics Department, Khalifa University of Science and Technology, Abu Dhabi, United Arab Emirates.

https://www.denys-dutykh.com/

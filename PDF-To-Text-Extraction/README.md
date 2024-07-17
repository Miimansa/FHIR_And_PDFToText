# PDF-to-Text Extraction README

## Overview

PDF-to-text extraction encounters several challenges that must be addressed for accurate and reliable data retrieval. These obstacles include:

- Accurately identifying and extracting subsections within documents to maintain structural coherence.
- Parsing complicated two-column layouts commonly found in academic papers and reports.
- Effectively detecting and converting tables into usable formats.
- Removing redundant headers and footers to focus solely on core content.
- Ensuring the clarity and legibility of extracted text amidst variations in font styles and the use of italics.

In response to these challenges, we explored the Adobe PDF Services API as a potential solution. The API offered promising features, including output in JSON format, facilitating the identification of section headers and corresponding section text within PDF documents.

## Files/Folders

- **protocols_zuma**: Example input PDF files used for testing.
- **ExtractTextInfoFromPDF_zuma1**: Output folder containing all conversions for the Zuma1 protocol PDF.
- **adobe_text_extraction.ipynb**: Python notebook containing code for all conversions, including table extraction and integration of tables into text files.



# PDF-to-Text Extraction README

## Overview

PDF-to-text extraction encounters several challenges that must be addressed for accurate and reliable data retrieval. These obstacles include:

- Accurately identifying and extracting subsections within documents to maintain structural coherence.
- Parsing complicated two-column layouts commonly found in academic papers and reports.
- Effectively detecting and converting tables into usable formats.
- Removing redundant headers and footers to focus solely on core content.
- Ensuring the clarity and legibility of extracted text amidst variations in font styles and the use of italics.

We explored the Adobe PDF Services API as a potential solution in response to these challenges. The API offered promising features, including output in JSON format, facilitating the identification of section headers and corresponding section text within PDF documents.

## Files/Folders

- **protocols_zuma**: Example input PDF files used for testing.
- **ExtractTextInfoFromPDF_zuma1**: Output folder containing all conversions for the Zuma1 protocol PDF.
- **adobe_text_extraction.ipynb**: Python notebook containing code for all conversions, including table extraction and integration of tables into text files.

## Obtaining Credentials from Adobe API Services

To use the Adobe PDF Services API, you need to obtain API credentials. Follow these steps:

1. Visit the [Adobe PDF Services API page](https://acrobatservices.adobe.com/dc-integration-creation-app-cdn/main.html?api=pdf-services-api).

2. Sign in with your Adobe ID or your Google account.

3. After signing in, set up a name for your credentials and choose Python as the language.

4. Click on 'Create credentials' to generate your credentials.

5. Upon submission, you will receive your credentials, including the `API Key` and `Client Secret.`

6. Use these credentials in your application to authenticate and make requests to the Adobe PDF Services API.



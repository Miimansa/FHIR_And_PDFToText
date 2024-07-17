# Task Descriptions

## Overview

This repository contains the code files for two major tasks:

1. **FHIR Resource Generation**
2. **PDF-To-Text Extraction**

### FHIR Resource Generation

**Objective:** Advance the interoperability of health data for both health research and practice.

**Description:** Fast Healthcare Interoperability Resources (FHIR), developed by HL7 International, is a widely recognized healthcare data standard that addresses the need for interoperability. However, translating Electronic Health Record (EHR) data into FHIR resources poses challenges due to the heterogeneous structures and formats of health data. This task focuses on overcoming these challenges, particularly when health information is embedded within unstructured data rather than neatly organized in structured formats.

### PDF-To-Text Extraction

**Objective:** Extract text from PDF documents.

**Description:** PDF-to-text extraction involves converting the information stored in PDF files into plain text format. PDF documents often contain valuable data presented in diverse forms, including text, tables, and figures. Extracting text from PDFs enables simpler indexing, searching, and processing of the information, supporting applications like data mining, text analytics, and information retrieval.

## Directory Structure

.
├── FHIR_Resource_Generation
│ ├── README.md
│ ├── Prompt_Engineering.ipynb
│ ├── prompt1.txt
│ └── prompt_dose.txt
└── PDF_To_Text_Extraction
├── README.md
├── adobe_text_extraction.ipynb
├── protocols_zuma
└── ExtractTextInfoFromPDF_zuma1
## Getting Started

### Prerequisites

- Python 3.x
- Required Python packages: `pdfservices-sdk`, `anthropic_bedrock`, `openai`

### Installation

1. Clone the repository:
    1. Clone the repository:
    ```bash
    git clone https://github.com/ilaananta/Miimansa.git
    cd Miimansa
    ```

2. Install the required packages:
    ```bash
    pip install pdfservices-sdk
    pip install anthropic_bedrock
    pip install openai
    ```







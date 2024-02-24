# PDF_Summarizer

## 1. **Problem Statement:**

The project aims to automate the extraction of specific information from a variety of PDF documents, including details such as deed numbers, real estate license plates, acts, grantors, beneficiaries, values, and identity document numbers. This process involves handling documents in different languages and formats, requiring robust extraction techniques.

## 2. **Data Loading:**
   - **Input and Output Directories:** Defined directories to handle input PDF files and store output Excel files for extracted information.
   - **Extract PDFs Directory:** Identified the directory containing the PDF documents to be processed.
   - **Directories for Images:** Created directories to store images extracted from the PDFs, ensuring organized data management.
   - **Image Extraction:** Utilized appropriate tools or libraries to extract images embedded within the PDF documents.
   - **PDF Dictionaries Dict:** Developed dictionaries to organize the extracted data from the PDF documents, facilitating further processing and analysis.

## 3. **Model Utilization:**
   - **Gemini Vision and Gemini Pro:** Leveraged the Gemini Vision model for extracting text from images within the PDF documents. Gemini Pro was employed for comprehensive information extraction from the text. Despite some limitations, such as occasional errors and processing time for large documents, Gemini Vision and Gemini Pro provided satisfactory results.
   - **Tesseract and Gemini Pro:** Implemented Tesseract, an open-source OCR engine, for text extraction from images. While Tesseract may not offer the same level of accuracy as Gemini Vision, it serves as a viable alternative, especially considering its cost-effectiveness. Gemini Pro was used for information extraction from the extracted text.
   - **Document AI Integration:** Explored the integration of Document AI, a sophisticated tool designed for document processing and analysis. Identified the steps required for implementation, including processor selection, creation, and integration with the project-specific repository.

## 4. **Document AI Integration Steps:**
   - **Processor Selection:** Determined the appropriate type of Document AI processor based on the nature of the documents and the extraction requirements.
   - **Processor Creation:** Created the processor within the Document AI framework to initiate the extraction process for the specified document types.
   - **Model ID and Project ID Retrieval:** Obtained the unique identifiers required for integrating the selected Document AI models and projects with the project repository.
   - **Repository Exploration and Modification:** Explored the available Document AI repository for relevant examples and templates. Modified the repository to include the necessary Model ID and Project ID for seamless integration with the project workflow.

## 5. **Challenges and Considerations:**
   - **Processing Efficiency:** Addressed challenges related to processing efficiency, particularly when dealing with large PDF documents. Explored techniques to optimize processing time and resource utilization.
   - **Tool Limitations:** Acknowledged the limitations of the selected extraction tools, such as occasional inaccuracies and processing delays. Explored strategies to mitigate these limitations and improve overall extraction accuracy.
   - **Integration Hurdles:** Faced challenges related to the integration of advanced tools like Document AI due to billing issues and technical complexities. Explored alternative solutions and potential workarounds to overcome integration hurdles effectively.

![](https://images.ctfassets.net/7xchb4r9mgls/2Hi5vNfDfihFMkCutRHg4m/3096ea435408f94ffc6ed0f3919b2ae1/Header_02.png)

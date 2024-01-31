# [Vist the Legal Draft Website](https://hhachem001.github.io/Legal_Tech/LandingPage.html)

## New features in Legal Draft Beta v1.024A

- Happy new year. New year, new features.
- Added memo upload feature to memos generator. It extracts text from a DOCX memo and places them automatically in the correct boxes. (currently only for supervising attorney memos).
- Added new A.I. feedback feature that reads the text for grammar and cohesiveness and provides the user with feedback. (currently only for supervising attorney memos).
- Added new A.I. citizen letter generator (replaced old system of selecting letter type).
- Added new contract generator tool (experimental).
- Added new tool to assist with responding to citizen complaints.
- Minor UI / theme enhancements. 
  
# Legal Draft

Legal Draft is a prototype toolbox designed for law school interns who secure internships in the government sector. The project aims to assist interns with basic tasks such as drafting memos in the proper format for their supervising attorneys or composing emails to be sent to supervisors and the public. The goal is to streamline these tasks and reduce the likelihood of errors, especially in fundamental aspects like memo formatting. You only get one chance to make a first impression. 

## Goals

- **No API Key required:** The goal was to create a self contained website that does not rely on costly API keys for A.I. Integration
- **Integrated JavaScript:** All JavaScript code is contained within the HTML code using <script> tags and content delivery networks to simply file management
- **All code runs client-side:** The features listed below do not rely on server-side processing. You can download this project and run it locally on your computer. The only downside is that it is only as fast as your computer and your internet speed. 
  
## Features

- **Document Drafting:** Legal Draft helps interns draft memos and letters in the correct format for legal communication.

- **Email Drafting:** Legal Draft helps interns draft emails to their supervising attorney.

- **AI Assistant:** The project includes an AI assistant to provide guidance and support in legal document creation.
  
- **AI Contract Evaluation Tools:** Legal Draft features AI tools for evaluating contracts, providing interns with valuable insights.

- **Inspiration from Docassemble:** Legal Draft draws inspiration from [Suffolk University Law School's Docassemble, developed by the Legal Innovation & Technology Lab](https://suffolklitlab.org/portfolio/).

- **Under Construction:** Additional features are still under development, including a database search feature to enhance the tool's capabilities.

## Technologies Used

- **AI Utilization:** The project leverages the [Transformer.js AI library](https://github.com/xenova/transformers.js) for AI functionality, enhancing the user experience.

- **Document Generation:** Legal Draft utilizes the [DOCXTemplater library](https://github.com/open-xml-templating/docxtemplater) for document generation, ensuring efficient and accurate document creation.
  
- **PDF Processing:** Legal Draft utilizes Mozillas PDF.js library for uploading and extracting text from PDF documents and contracts. It is currently utilized in the Contract Toolbox.
 
## Current Known Issues in Legal Draft Beta v1.024A

- A.I. Responses across the site may be cutoff, not giving the user the entire response. Increasing the Max Token count to 1000 has partially fixed the issue.
- PDF Upload function in the contract summarizer does not display extracted contents properly in the text input field
- "Thinking..." status in the chatbot may not always appear on the page if the LLM was already loaded into browser cache upon first visit
- Downloading the A.I. Model causes the page to stutter / freeze
- Tokenizer feature in the experimental contract summarizer does not properly re-assemble the generated output causing some words to be cut off at the beginning or end of a sentence.
- Authorization pop-up appears everytime the user goes back to the main-menu / redirect page

## Acknowledgments

- **Creator:** The Legal Draft website and the Legal Draft A.I. Frontend was designed and created by Hashim Hachem.

- **Assistance:** Special thanks to Professor Quinten Steenhuis for his assistance in the development process, and to GitHub for providing free access to the Copilot A.I.

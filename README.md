# [Vist the Legal Draft Website](https://hhachem001.github.io/Legal_Tech/LandingPage.html)

# Legal Draft

Legal Draft is a prototype toolbox designed for law school interns who secure internships in the public/government sector. The project aims to assist interns with basic tasks such as drafting memos in the proper format for their supervising attorneys or composing emails to be sent to supervisors and the public. The goal is to streamline these tasks and reduce the likelihood of errors, especially in fundamental aspects like memo formatting. You only get one chance to make a first impression. 

## Goals

- **No API Key required:** The goal was to create a self contained website that does not rely on costly API keys for A.I. Integration
- **Integrated JavaScript:** All JavaScript code is contained within the HTML code using <script> tags and content delivery networks to simply file management
- **All code runs client-side:** The features listed below do not rely on server-side processing. You can download this project and run it locally on your computer. The only downside is that it is only as fast as your computer and your internet speed. 
  
## Features

- **Document Drafting:** Legal Draft helps interns draft memos and letters in the correct format for legal communication.
  
- **AI Assistant:** The project includes an AI assistant to provide guidance and support in legal document creation.
  
- **AI Contract Evaluation Tools:** Legal Draft features AI tools for evaluating contracts, providing interns with valuable insights.

- **Inspiration from Docassemble:** Legal Draft draws inspiration from [Suffolk University Law School's Docassemble, developed by the Legal Innovation & Technology Lab](https://suffolklitlab.org/portfolio/).

- **Under Construction:** Additional features are still under development, including a database search feature to enhance the tool's capabilities.

## Technologies Used

- **AI Utilization:** The project leverages the [Transformer.js AI library](https://github.com/xenova/transformers.js) for AI functionality, enhancing the user experience.

- **Document Generation:** Legal Draft utilizes the [DOCXTemplater library](https://github.com/open-xml-templating/docxtemplater) for document generation, ensuring efficient and accurate document creation.
  
- **PDF Processing:** Legal Draft utilizes Mozillas PDF.js library for uploading and extracting text from PDF documents and contracts. It is currently utilized in the Contract Toolbox.

## New features in Legal Draft Beta v11.023C

- Mask AI. Functionality added to document generation where users can seamlessly enhance their sentences by replacing uncertain or unknown words with the [MASK] tag, enabling the AI to intelligently fill in the blanks for a more polished and coherent expression. Plain language is key!
- Database search functionality
- New Intern Task Management System
- New A.I. Email Generator
- Better Regular Expression logic will added to the Contract Judge tool
  
  
## Features added in Legal Draft Beta v11.023B

- Added loading indicator to the Legal Draft A.I. Chatbot
- Added error messages to indicate whether the A.I. model has been loaded into the browser cache
- Updated A.I. Pipeline on the feedback page from version 2.4.1 to version 2.8.0
- Added MD5 hash encryption to default login password
- Added redirect blockers to ensure that the user utilizes the official login page
- Added ready-status message to the chatbot so the user know when to proceed
- Added "Thinking..." status to the chatbot
- Added disclaimer on Login Page that user must agree to in order to access Legal Draft

## Current Known Issues in Legal Draft Beta v11.023C

- A.I. Responses across the site may be cutoff, not giving the user the entire response.
- PDF Upload function in the contract summarizer does not display extracted contents properly in the text input field
- ChatBot does not give answers related to legal document drafting and legal questions (Currently it answers any question, although current tests show progress with context awareness)
- "Thinking..." status in the chatbot may not always appear on the page if the LLM was already loaded into browser cache upon first visit
- Downloading the A.I. Model causes the page to stutter / freeze
- Tokenizer feature in the experimental contract summarizer does not properly re-assemble the generated output causing some words to be cut off at the beginning or end of a sentence.
- Authorization pop-up appears everytime the user goes back to the main-menu / redirect page

## Acknowledgments

- **Creator:** The Legal Draft website and the Legal Draft A.I. Frontend was designed and created by Hashim Hachem.

- **Assistance:** Special thanks to Professor Quinten Steenhuis for his assistance in the development process, and to GitHub for providing free access to the Copilot A.I.

# [Vist the Legal Draft Website](https://hhachem001.github.io/Legal_Tech/LandingPage.html)

# Legal Draft

Legal Draft is a prototype toolbox designed for law school interns who secure internships in the public/government sector. The project aims to assist interns with basic tasks such as drafting memos in the proper format for their supervising attorneys or composing letters to the general public. The goal is to streamline these tasks and reduce the likelihood of errors, especially in fundamental aspects like memo formatting.

## Goals

- **No API Key required:** The goal was to create a self contained website that does not rely on costly API keys for A.I. Integration
- **Integrated JavaScript:** All JavaScript code is contained within the HTML code using <script> tags and content delivery networks to simply file management
- **All code is client-side:** The features listed below do not rely on server-side processing. You can download this project and run it locally on your computer. The only downside is that it is only as fast as your computer and your internet speed. 
  
## Features

- **Document Drafting:** Legal Draft helps interns draft memos and letters in the correct format for legal communication.
  
- **AI Assistant:** The project includes an AI assistant to provide guidance and support in legal document creation.
  
- **AI Contract Evaluation Tools:** Legal Draft features AI tools for evaluating contracts, providing interns with valuable insights.

- **Inspiration from Docassemble:** Legal Draft draws inspiration from [Suffolk University Law School's Docassemble, developed by the Legal Innovation & Technology Lab](https://suffolklitlab.org/portfolio/).

- **Under Construction:** Additional features are still under development, including a database search feature to enhance the tool's capabilities.

## Technologies Used

- **AI Utilization:** The project leverages the [Transformer.js AI library](https://github.com/xenova/transformers.js) for AI functionality, enhancing the user experience.

- **Document Generation:** Legal Draft utilizes the [DOCXTemplater library](https://github.com/open-xml-templating/docxtemplater) for document generation, ensuring efficient and accurate document creation.
  
## New Features in Legal Draft Beta v11.023B

- Added loading indicator to the Legal Draft A.I. Chatbot
- Added error messages to indicate whether the A.I. model has been loaded into the browser cache
- Updated A.I. Pipeline on the feedback page from version 2.4.1 to version 2.8.0
- Added MD5 hash encryption to default login password
- Added redirect blockers to ensure that the user utilizes the official login page
- Added ready-status message to the chatbot so the user know when to proceed
- Added "Thinking..." status to the chatbot
- Added disclaimer on Login Page that user must agree to in order to access Legal Draft

## Current Known Issues in Legal Draft Beta v11.023B

- "Thinking..." status in the chatbot may not always appear on the page if the LLM was already loaded into browser cache upon first visit
- Downloading the A.I. Model causes the page to stutter / freeze
- ~~Page does not display loading status while A.I. is generating a response. User may be led to believe page is frozen while it is in fact generating a response~~ Fixed by adding a loading mechanism / visual feedback
- ~~Document generator may occasionally place "undefined" in document text instead of users text.~~ Fixed
- Tokenizer feature in the experimental contract summarizer does not properly re-assemble the generated output causing some words to be cut off at the beginning or end of a sentence.
- Authorization pop-up appears everytime the user goes back to the main-menu / redirect page

## Acknowledgments

- **Creator:** The Legal Draft website and the Legal Draft A.I. Bot Frontend was designed and created by Hashim Hachem.

- **Assistance:** Special thanks to GitHub Copilot for their assistance in the development process and for providing free access to the Copilot A.I.

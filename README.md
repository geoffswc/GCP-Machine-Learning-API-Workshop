# GCP-Machine-Learning-API-Workshop

### Short Description
This tutorial is an introduction to extracting, classifying, and assessing sentiment for text from image documents using the Google Colab and the Google Cloud Platform API.

### Long Description
This workshop will review how to use Python, along with Google Colab and the Google Cloud Discovery API, to perform common machine learning and natural laanguage processing tasks using pre-trained models and methods.

In this workshop, participants will create three documents, each written in a different style: typed, hand printed, and cursive. Participants will capture these files as images, upload them to a github repository, and use the Google Cloud Discovery API to:

1) Extract the text from the image document, using the TEXT_DETECTION method from the translate API.

2) Determine the sentiment of the document by using a pre-trained model available from the language API.

3) Classify the document through a set of pre-trained categories ("media", "sports", "health"), along with the estimated probabily that the classification is an accurate match, using the classification service from the language API.

### Prerequisites

Participants should have basic introductory level Python programming skills, including the ability to write loops, conditionals, and methods.

### Setup and Configuration

Participants will need a Google Drive account 

https://www.google.com/drive/

and a Google Cloud Platform account. 

https://cloud.google.com

The free tier for both accounts is sufficient for this workshop. 

## Workbooks

### Extraction-Sentiment-Category.ipynb

This workbook reviews the process of connecting to the Google Cloud Console, generating an API key, and using it to call the text extraction, sentiment analysis, and document classification services available through the Google Cloud Discovery API.

### External Links

For a fuller description of the discovery API, including audio translation and other examples:

https://colab.research.google.com/drive/1hPH7skySCZR-ZMJ6TmYLN1ug6vbq2cpb

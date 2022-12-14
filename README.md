### Bank of Baroda Microsoft Azure 2022 Hackathon

This repository is for the project for the Bank of Baroda Hackathon 2022 conducted by TechGig and sponsored by Microsoft Azure.

## Table of Contents
- [Problem Title](#problem-title)
- [Problem Statment](#problem-statement)
- [About the Problem](#about-the-problem)
- [Tools and Tech Stack](#tools-and-tech-stack)
- [Prerequisites](#prerequisites)
- [Flow Diagram](#flow-diagram)
- [Presentation Link](#presentation-link)
- [UI Designs](#ui-designs)
- [Authors](#authors)

## Problem Title:
Automated Cheque Processing

## Problem Statement:
* Bank handles large volumes of cheques in the clearing process. The process involves many technical verifications including signature verification. Some of these steps are manual and require human intervention to complete the process. The current process requires the high human capital deployment and longer processing time.

## About the Problem:
* We will first collect the end user's information through our portal.
* We will check if the end user's information entered is correct through the KYC verifictation
* We will then store the end user's information in our Azure Database.
* End user's will then upload the cheque they want to process through our portal.
* We will the pass the uploaded cheque through our Image Proceesing Model which will extract all the neccessary information of the end user using computer vision, siamese networks and optical character recognition(OCR).
* We will then use Natural Language Processing to process the extracted infromation and convert it to English if the User has not entered their details in English.
* After the extraction of the information we will compare the signature present of the cheque to the signature present in our database using computer vision.
* Once the signature is verfied we will then compare the amount to the amount present in the database if the required amount to transact is less than the amount in the database we will then process the transaction.

## Tools and Tech Stack:
* ReactJS
* Redux
* Azure Machine Learning
* Azure AI
* OpenCV
* Natural Language Processing
* NodeJS
* ExpressJS
* Azure Cosmos Database
* Azure Cloud
* Tensorflow
* Keras
* Tessaract

## Prerequisites:

Ensure that your system have the following softwares
installed:

- [Git](https://git-scm.com/downloads)
- [Python](https://www.python.org/downloads/)
- [NodeJS](https://nodejs.org/en/download/)
- [Tesseract](https://tesseract-ocr.github.io/)

## Flow Diagram
![BOB Flow Diag (1)](https://user-images.githubusercontent.com/50861092/191328464-f7b2866e-754b-4d86-98dc-2fc4399fa82e.png)

## Presentation Link: [Link](https://www.canva.com/design/DAFMvdneAEg/WsOTDa24USuewpJUID840w/view?utm_content=DAFMvdneAEg&utm_campaign=designshare&utm_medium=link&utm_source=publishpresent)

## UI Designs

<p float="left">
  <img src = "https://user-images.githubusercontent.com/50861092/191314811-b6eff532-c93e-400e-a894-9ad53afea468.svg" width = 20% height = 20%>
  <img src = "https://user-images.githubusercontent.com/71393033/191317212-ae020a7a-6616-4463-a395-868750ff6a89.svg" width = 20% height = 20%>
  <img src = "https://user-images.githubusercontent.com/71393033/191330030-2ca005d5-b9ac-44eb-a807-ef586ba95e2c.svg" width = 20% height = 20%>
  <img src = "https://user-images.githubusercontent.com/71393033/191318210-cf9d0955-b18c-4a0a-9fe4-63caf73595b0.svg" width = 20% height = 20%>
  <img src = "https://user-images.githubusercontent.com/71393033/191318413-589a17f6-244c-4e10-9ff1-ebe50821ec58.svg" width = 20% height = 20%>
  <img src = "https://user-images.githubusercontent.com/71393033/191318503-c5cf9cf3-6323-4dc9-a882-7e0c772fb8e9.svg" width = 20% height = 20%>
  <img src = "https://user-images.githubusercontent.com/71393033/191318574-3cda5cc4-35ee-47ee-b60b-4899d6511f6d.svg" width = 20% height = 20%>
</p>


## Authors

#### Neeraj J Manurkar
* [GitHub](https://github.com/Neerajjr11)
* [LinkedIn](https://www.linkedin.com/in/neeraj-j-manurkar-64372b212/)

#### Vishal Singh
* [GitHub](https://github.com/vishalsinghhh)
* [LinkedIn](https://www.linkedin.com/in/vishal-singh-2046841b7)

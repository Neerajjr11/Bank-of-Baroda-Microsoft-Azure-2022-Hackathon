### Bank of Baroda Microsoft Azure 2022 Hackathon

This repository is for the project for the Bank of Baroda Hackathon 2022 conducted by TechGig and sponsored by Microsoft Azure.

## Table of Contents
- [Problem Title](#problem-title)
- [Problem Statment](#problem-statement)
- [About the Problem](#about-the-problem)
- [Tools and Tech Stack](#tools-and-tech-stack)
- [Prerequisites](#prerequisites)

## Problem Title:
Automated Cheque Processing

## Problem Statement:
* Bank handles large volumes of cheques in the clearing process. The process involves many technical verifications including signature verification. Some of these steps are manual and require human intervention to complete the process. The current process requires the high human capital deployment and longer processing time.

## About the Problem:
* We will first collect the end user's information through our portal.
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

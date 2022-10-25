# ETL SSIS Telecome CaseStudy
# Document Introduction

This is an example of some source system data for different businesses and it doesn’t relate or correlate to any actual telecom company data. We simulate some data for general demo purposes as part of educational free content.
The dataset is a sample generated using a script and it does not describe the full telecom dataset for signalling but it simulates the general idea.
# Introduction
This specification aims to document the source system data analysis and its properties. It provides the information related to the process of integration, data formats, and constraints of the data.
This document contains the following topics:
Source system life cycle with customer interaction.
Source system integration mechanism, data latency, and security concerns.
Source system data format.
Data integration failure and recovery mechanism.
Business requirements and use cases.
Data Archiving.
# Source System Overview and Life-Cycle
Signalling data describes the subscriber network activities and interaction. Subscriber does an event such as call, browsing, latching, SMS, etc.
The network vendor collects the subscriber data in real-time and bulk every 5 min activity in one fill and push it to landing servers.
 
Resources:
Mobile network technologies GSM/GPRS/UMTS/LTE: https://youtu.be/9FSDcDlVGP4
GSM Architecture https://youtu.be/6qR102lcXoY
Making a Voice Call in 4G https://youtu.be/AdmaSwdTDmI
GSM Authentication https://youtu.be/FN5APZQBGJ0
![Screenshot (80)](https://user-images.githubusercontent.com/105324794/197868439-87cd4368-d896-490c-9329-a51976704a0d.png)
![Screenshot (81)](https://user-images.githubusercontent.com/105324794/197868476-d5c73d1f-9880-45cb-9521-0030bb69efd4.png)
![WhatsApp Image 2022-10-25 at 9 28 42 PM (1)](https://user-images.githubusercontent.com/105324794/197868487-33c2bf6d-be0e-4bcd-8196-36eb113cadf3.jpeg)
![WhatsApp Image 2022-10-25 at 9 28 42 PM](https://user-images.githubusercontent.com/105324794/197868497-68b87a2b-5fd1-4bbe-9195-b337e685959a.jpeg)

# Overview
A friend's start up was focused on bringing AI to automate backend processes in the healthcare industry. The business plan was focused on 2 aspects - call center automation and insurance claim automation. My focus was on the latter. Doctors have to spend a lot of time filling out these claims once making a diagnosis on a patient and if something is missed or incorrect (as insurance documentation changes frequently) it can be very tedious. To help mitigate this the idea was to create a system that works alongside the doctor or nurse as they are filling out information about the patient, using that information in real time to fill out that claim with the appropriate codes, etc based on the latest insurance information. 

The part I am going to show here is the core proof of concept RAG pipeline I created that ingests these insurance documents and creates a knowledge graph to organize the information to be queried as needed. 

# Key Features


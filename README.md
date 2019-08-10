# Readme
DocuSign API Evaluation.

## Overview
This Project was amazing! I learned a lot. I had to evaluate the API Explorer, Python CLient Libary, Developer Sandbox, Developer Admin Page and the Documentation.

For External resources, I had to use Stackoverflow & 1 interesting blog.

## I had Three concern:
- was there a need to use one of the client Libarys?
- Was the point of this challenge to see if I can use and refactor the python Launcher application?
- is it ok that I just used the API Explorer?


## My Decision
I decided to go with the easiest route and only use the API explorer. Also, Based on the fact that the resource shared with me refer to an "API Call" as an unformatted JSON file, and the API explorer returns the same format, I decided to submit my solution in the same structure as the Problem.

## Project Requirements
1. Modify the API call in   [API TEST 1](https://github.com/DSTCSM/Technical-Assessment/blob/master/API%20Test%20) to send successfully.
2. Modify the API call in  [API TEST 2](https://github.com/DSTCSM/Technical-Assessment/blob/master/API%20Test%202) to send successfully.
3. Create an API call to DocuSign that creates a single DocuSign envelope that combines the templates "TestJSON1" and "TestJSON2" and is directed to the following recipients: John Doe, johndoe@test.test and Jane Doe, janedoe@test.test.
4. When prompted, please return your completed API calls to your recruiting coordinator.

## Workflow
1. I explored the documentation
2. I opened a dev sandbox
3. I Use the API Explorer
4. I fixed issues with the request in the API Explorer and shared the results of a successful API call
5. if I had an issue I used Stackoverflow

## Issues
1. MAC OS python 3.7 uses a built-in SSLopen.
   A. URL: https://timonweb.com/tutorials/fixing-certificate_verify_failed-error-when-trying-requests_html-out-on-mac/
2. I needed to find a way to combine two templates
   A. URL: https://stackoverflow.com/questions/18258186/two-templates-in-one-envelope-with-docusign-api
   B. I uploaded the template information to the sandbox
   C. then I ran the call using compositeTemplates
      URL: https://docs.google.com/document/d/1BinLmEzktszFMDk-qzGBpZFNQymHGwqiapBBPuZbTF4/edit?usp=sharing

## Solutions
1. URL: https://docs.google.com/document/d/1DNKtMGNsITAkXZEvSGyb9ltsFkJhVTzSCkqEFmm-lsU/edit?usp=sharing
2. URL: https://docs.google.com/document/d/1pp0UXpFl5F7twhdTkPgFDET78cCS0bmGQk_O6Q02Pxs/edit?usp=sharing
3. URL: https://docs.google.com/document/d/1BinLmEzktszFMDk-qzGBpZFNQymHGwqiapBBPuZbTF4/edit?usp=sharing

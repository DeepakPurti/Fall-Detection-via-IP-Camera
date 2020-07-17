## Introduction
Human Fall Detection via IP Camera in Smart phone, with E-mail Alert to user

## Requirements
1. MATLAB - R2019b or higher
2. MATLAB Toolboxes:
   <br>a. Image Acquisition Toolbox
   <br>b. Image Processing Toolbox
   <br>c. Computer Vision Toolbox
3. Smartphone with IP Camera application

## Execution
Run 'falldetection_via_ipcamera.m' .
This would read from the IP camera app in the smartphone, and detect the falling action of a human from the feed.
An e-mail alert would be send to user after fall detection.

## Modification
To edit sender's and receiver's email addresses (and password and message), modify 'sendemail.m' .

## Reference Paper
Caroline Rougier, Jean Meunier, Alain St-Arnaud, Jacqueline Rousseau ; “Fall Detection from Human Shape and Motion History Using Video Surveillance”; 21st International Conference on Advanced Information Networking and Applications Workshops (AINAW’07), 2007.


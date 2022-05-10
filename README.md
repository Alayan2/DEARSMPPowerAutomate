# FDEP Mobile Application
DEAR SMP Power Automate Flow (forked from my alternate account)

At the Florida Department of Environmental Protection (FDEP) I led a workgroup of representatives from 7 regional FDEP offices tasked with incorporating 
tablets into our water quality monitoring routine. In addition to leading the workgroup, I developed a custom mobile application based on stakeholder 
feedback. 

<p align="center">
<img src="https://user-images.githubusercontent.com/90277439/167675093-6e8a595d-1b50-467c-b6b9-f4810892fff1.jpeg" width="60%">
</p>

It was important to develop this application using tools that would be accessible to FDEP staff with no programming experience. The app integrates ArcGIS mobiles apps (Collector and Survey123) with Microsoft Office applications (OneDrive, Word, Excel) using Power Automate. Power Automate was the most cost 
effective automation tool available to the Department, which would enable the program to integrate AcrGIS with Microsoft Office cloud applications. 

<p align="center">
<img src="https://user-images.githubusercontent.com/90277439/167675310-52c77165-d1af-4b6e-861b-576586f756b7.jpeg" width="60%">
</p>

The app works by:
  1. Opening to an ArcGIS collector map pre-loaded with FDEP monitoring stations.
  2. The user selects the station and then clicks the Survey123 hyperlink in the infowindow. 
  3. The hyperlink prepopulates the Survey123 form with station information which eliminates the risk of transcriptions errors in documentation. 
              
     <img src="https://user-images.githubusercontent.com/90277439/167675952-8f48ce5e-9b11-4f95-8b4d-bfd06518271a.jpeg" width="60%">

  4. The user then enters field observations and YSI meter readings in accordance with FDEP SOPs. 
  5. Once complete, the user submits the survey which triggers Power Automate to generate:
              
      a. Field reports of the data collected

      b. A running log of sites collected for documenting data collection progress for the project. 
      
      c. Chain of custody documentation for submission of samples to the laboratory. 
      
      <p align="center">
      <img src="https://user-images.githubusercontent.com/90277439/167676217-eea88ee9-5496-4c48-9704-018c30476743.jpeg" width="50%"><img src="https://user-images.githubusercontent.com/90277439/167679105-190bc297-d173-4cea-b06f-7342b8f2fbf1.jpeg" width="50%">
      </p>

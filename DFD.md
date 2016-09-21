This is the DFD file.


image
![alt text] (https://cloud.githubusercontent.com/assets/21348764/18294205/2ef8c2ac-745d-11e6-98aa-57909156b522.jpg)

This is the Screenshot from Wednesday's Lecture
![screenshot] (https://cloud.githubusercontent.com/assets/21348764/18692196/391fa384-7f5e-11e6-88f9-d9dac6d5fa3a.png)


Outline for Professor Germonprez
Here are the rules:
1. List of entities:

Developer (Entity)
Manager (Entity)

2. List of Processes:
a.) Management of Software Packages
(this can be broken down into three other processes)
- Verify for Open Source Software Components
- Scan for Licenses
- Scan Software for Published Software Vulnerabilities

3. List of Data Repositories

- OSS Software Package Datastore

4. List of Data Flow arrows (only using verbs HERE to help myself understand where & which direction the processes are going, cannot allow on the DFD)

-Developer submits "software package" to the process of Managing Software Packages.
-The "OSS package" gets verified through the three processes of checking for OSS Components, Licensing, and Vulnerabilites. Each process will change the DF line name following verification.
-The "verified OSS data" (three separate DFs for each package from each process) gets stored into the data repository called "OSS Package Datastore."
-Developer/Manager submits "project request"
 @gavorialfox

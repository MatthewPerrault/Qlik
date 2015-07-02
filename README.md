# Qlik
Creating Qlik Code
Create 3 seperate files

Step 1: Create Extract File
  File imports data from database
  Store all files into a .qvd file

Step 2: Transform
  Remove all synthetic keys and concatonnate files into a Fact Table
  - Pull in .qvd files from Store files.
  - Tranform process including concatonation
  - Store in .qvd files the same as Extract process

Step 3: Final Model
  Load all .qvd table files from Transform
  -Build dashboard when all .wvd files are uploaded
  - Final Model not included in this.
  - Load .qvd files and replace fields with * to load all.

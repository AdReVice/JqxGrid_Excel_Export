# JqxGrid_Excel_Export
Custom Method To Export JqxGrid Data to Excel

This is a customize Downloader or say Excel Exporter for JQXGrid 

## Steps
  1. Download the Zip file 
  2. Include the Files from js folder to your Workspace
  3. Call my custom download method which takes three parameter  :- 
  ```
   var colToExclude - Array of Jqxgrid Datafields to Exclude from downloaded Excel
   var gridId - Your JqxGrid ID
   var fileNm - File Name
   ```
   Now Call below method.
   ### function dynDownload(colToExclude,gridId,fileNm);
  
### External API's Used are-
  * xlxs.min.js
  * jhxlsx.js
  
#### P.S I have customized it to be 'IE Compatible'

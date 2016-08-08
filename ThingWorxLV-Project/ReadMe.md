This is a myRIO project that uses the VI's in the previous folder (i.e. SetService.vi, GetProperties.vi, and GetPropertyValues.vi) to send and receive information from a ThingWorx server. In order to use this project, complete the following steps. <br>
1. Download the myRIO software bundle for your version of LabVIEW, if you do not already have it (For LabVIEW 2015: <a href ="http://www.ni.com/download/ni-myrio-software-2015/5727/en/">http://www.ni.com/download/ni-myrio-software-2015/5727/en/</a> ). <br>
2. Download the "HTTP Client" library on the myRIO using the NI Max (NI Measurement & Automation Explorer) program. <br>
      &nbsp;&nbsp;&nbsp;&nbsp; i. Find your myRIO after expanding the "Remote Systems" tab in the tree on the left of the NI MAX user interface. <br>
      &nbsp;&nbsp;&nbsp;&nbsp; ii. Click on the arrow to the left of your myRIO name to expand the tree. <br>
     &nbsp;&nbsp;&nbsp;&nbsp; iii. Click on "Software" and then click the "Add/Remove Software" button at the top of the right side of the NI MAX user interface.<br>
      &nbsp;&nbsp;&nbsp;&nbsp; iv. Choose the most recent version of the software (for example "NI myRIO 15.0 - August 2015") and hit "Next."<br>
      &nbsp;&nbsp;&nbsp;&nbsp; v. Keep your current libraries installed, but also check off the box to the left of "Web Services" and the boxes to the left of "Network Streams," "Network Variable Engine," and "Variable Client Support for LabVIEW RT" under the "Network I/O" tab. <br>
3. You have the correct software on your myRIO, open the project "ThingWorxLV Project.lvproj." <br>
4. Change the IP address to that of your myRIO by right clicking on the myRIO icon in the project menu and selecting "Properties." <br>
5. Then make sure you can connect to your myRIO. <br>
6. Now create a ThingTemplate in ThingWorx. <br>
7. 

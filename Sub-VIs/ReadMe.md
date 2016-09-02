These are the subVI's for the programs in the previous folder. <br>
Descriptions of VI's: <br>
- "ThingWorxInit.vi" - combines the necessary information (i.e. ThingWorx server address, port number, etc.) into a format suitable for passing to the following VI's as well as begins an HTTP Client connection to the ThingWorx server. <br>
- "GetProperties.vi" - sends a GET request to a ThingWorx server to request the properties and their values of a particular Thing. <br>
- "SetProperty.vi" - sends a PUT request to a ThingWorx server to change the value of a particular property of a particular Thing. <br>
- "SetServiceVI.vi" - sends a POST request to a ThingWorx server to change the values of the specified properties of a particular Thing (Polymorphic VI that includes "SetServiceArrayInputs.vi" and "SetServiceClusterInputs.vi"). <br>
- "ParseGetRequest.vi" - parses the body of the returned message from ThingWorx server after sending it a GET request. <br> 
- "ThingWorxResponseErrorCatcher.vi" - catches errors from the body of the reply from the ThingWorx server. <br>
- "ThingWorxClose.vi" - closes the HTTP connection with the ThingWorx server <br>

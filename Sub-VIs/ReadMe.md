These are the subVI's for the programs in the previous folder. <br>
Descriptions of VI's: <br>
- "ThingWorxInit.vi" - combines the necessary information (i.e. ThingWorx server address, port number, etc.) into a format suitable for passing to the following VI's as well as begins an HTTP Client connection to the ThingWorx server. <br>
- "GetProperties.vi" - sends a GET request to a ThingWorx server to request the properties and their values of a particular Thing. <br>
- "ServiceSendProperties.vi" - sends a POST request to a ThingWorx server to change the values of the specified properties of a particular thing (Polymorphic VI that includes "SetService.vi" and "SetServiceClusterInputs.vi"). <br>
- "SendPropertyValues.vi" - sends a PUT request to a ThingWorx server to change the value of a particular property of a particular Thing. <br> 
- "ParseGetRequest.vi" - parses the body of the reply from the ThingWorx server after it is sent a GET request. <br>
- "ThingWorxResponseErrorCatcher.vi" - catches errors from the body of the reply from the ThingWorx server. <br>


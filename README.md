# roomManager
 job recruitment project. 

They best way to start unit tests is cloning repository and start it from IDE, I made project in InteliJ IDEA. 
assigning room can be done by sending POST request to https://roommanagerjobtask.azurewebsites.net/assignRooms with following JSON body structure. 

example JSON: 
{
    "CustomersPrices": [3, 5.3, 325.55, 115.54],
    "EconomyRoomsNumber" : 3,
    "PremiumRoomsNumber" : 2
}

Preferred way to use API is using jar file in my other repo https://github.com/Groundy/roomManagerClient, which gives proper output and format json response to be more readable. Description how to use that jar file is in roomManagerClient readme file.

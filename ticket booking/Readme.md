Build & Run Instructions - 

Frondend:
1.npm install -g create-react-app
2.cd trainbooking
3.npm install
4.npm start

Backend: 
1.cd Backend/
2.mvn clean install
3.java -jar target/CaliforniaRailTransportSystem-0.0.1-SNAPSHOT.jar
Screenshots:
### Login using Google or Facebook OAuth
![login](https://user-images.githubusercontent.com/22604867/36648886-94db91b6-1a4d-11e8-80bc-630ebb7c3b8a.jpg)

### Search Ticket:
![search](https://user-images.githubusercontent.com/22604867/36648924-ed151726-1a4d-11e8-8f9c-d89b1add8599.jpg)

### Search Results
On clicking find search the API gets called which fetches the results sorted according to
ascending order and are five in number. These results are then populated on the screen
Can be configured to display results with connections, without connections, and with the exact time flag along with specifying the train types (Express or Regular).

![searchresult](https://user-images.githubusercontent.com/22604867/36648989-6b81dcfc-1a4e-11e8-8963-2f22f6e6089f.jpg)

### View Bookings
![booking](https://user-images.githubusercontent.com/22604867/36649150-af045e04-1a4f-11e8-9bbf-f8bc407e52e7.jpg)

### Train Cancellation
![cancel](https://user-images.githubusercontent.com/22604867/36649420-cb52adca-1a51-11e8-94be-f0f57330a836.jpg)

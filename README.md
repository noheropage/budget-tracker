# Budget-Tracker
A budget tracker that has both online and offline functionality.

## Description
Users can add the name and amount of a transaction and select if this transaction adds funds or substracts them. Transactions are listed in an easy to read table and graph. Transactions are recorded in a client-side cache and indexDB. If a user loses internet connection they will still have full functionality using this client-side data. When internet connection resumes the transactions recorded locally will be pushed to the server-side database.

## Screenshot
![Homepage](./assets/screenshot.png)
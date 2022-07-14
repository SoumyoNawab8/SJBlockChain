# How to test your application functionalities?

To test your application I recommend you to use POSTMAN, this tool will help you to make the requests to the API.
Always is useful to debug your code see what is happening in your algorithm, so I will let you this video for you to check on how to do it >https://www.youtube.com/watch?v=6cOsxaNC06c . Try always to debug your code to understand what you are doing.

1. Run your application using the command `node app.js`
You should see in your terminal a message indicating that the server is listening in port 8000:
> Server Listening for port: 8000

## Tested Screenshots

2. To make sure your application is working fine and it creates the Genesis Block you can use POSTMAN to request the Genesis block:
    ![Request: http://localhost:8000/block/0 ](Screenshots/Test%20case%201.png)
3. Make your first request of ownership sending your wallet address:
    ![Request: http://localhost:8000/requestValidation ](Screenshots/Test%20Case%202.png)
4. Sign the message with your Wallet:
    ![Use the Wallet to sign a message](Screenshots/Test%20Case%203.png)
5. Submit your Star
     ![Request: http://localhost:8000/submitstar](Screenshots/Test%20Case%204.png)
6. Retrieve Stars owned by me
    ![Request: http://localhost:8000/blocks/<WALLET_ADDRESS>](Screenshots/Test%20Case%205.png)
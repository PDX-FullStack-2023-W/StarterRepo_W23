#for the middleware
Problem: The app doesn't respond as expected when sending a DELETE request to "/users/:userID".
Solution Attempts:
Checked if the route is defined correctly, "/users/:userID".
Verified that the correct HTTP method (DELETE) is being used for the request.
Checked the console log to see if there are any error messages.
Added console.log statements before and after the if statement to check the value of randomNum and the execution flow.
Used a tool such as Postman to send the request and see the response.
Error Messages:

None found in the console log.
The response status is 500 and the message is "User [userID] NOT FOUND!".

#for the 1.path
Problem: The GET request to "/users" doesn't load the HTML file properly.

Solution Attempts:

Checked if the file path to the HTML file is correct, "/users.html".
Verified that the file exists in the correct directory.
Checked the console log to see if there are any error messages.
Used a tool such as Postman to send the request and see the response.
Tried using the res.sendFile method with a different file type to see if the issue is specific to HTML files.
Error Messages:

None found in the console log.
The response status is 200 but the content is not the expected HTML file.

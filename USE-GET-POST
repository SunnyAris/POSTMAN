1. On the “collections” tab click on the “+” button to create a new collection. A new collection will appear and you will be able to edit its name, description, and many other settings.

2. Request URL has three parts 
- protocol(such as http:// or https://)

- host (location of the server) library-api.postmanlabs.com

- path (route on the server) /books

- query ?id=1&type=new 


np. https://library-api.postmanlabs.com/books?id=1&type=new 


Query Parameter: These are appended to the end of the request URL, Query parameters are appended to the end of the request URL, following '?' and listed in key-value pairs, separated by '&' Syntax:

?id=1&type=new  



Path parameters are request parameters attached to a URL that point to a specific REST API resource. 
The path parameter is separated from the URL by a `/`, and from the query parameter(s) by a question mark (`?`). The path parameter defines the resource location, while the query parameter defines sort, pagination, or filter operations. The user's input (the query) is passed as a variable in the query parameter, while each path parameter must be substituted with an actual value when the client makes an API call. The path parameter is contained within curly braces.

Path parameters are part of the endpoint and are required. For example, `/users/{id}`, `{id}` is the path parameter of the endpoint `/users`- it is pointing to a specific user's record. An endpoint can have multiple path parameters, like in the example `/organizations/{orgId}/members/{memberId}`. This would be pointing to a specific member's record within a specific organization, with both `{orgID}` and `{memberID}` requiring variables.



3. In the workspace GET

Set your HTTP request to GET.
In the request URL field, input link
Click Send
You will see 200 OK Message
There should be 10 user results in the body which indicates that your test has run successfully.

4. In the new tab POST

Set your HTTP request to POST.
Input the same link in request url 
switch to the Body tab

In Body,

Click raw
Select JSON

Copy and paste just one user result from the previous get request. Change id to 11 and name to any desired name. You can also change other details like the address.

Click Send.
Status: 201 Created should be displayed
Posted data are showing up in the body.
## PUT, POST, and PATCH
To send body data with requests whenever you need to add or update structured data. For example, if you're sending a request to add a new customer to a database, you might include the customer details in JSON. Typically you will use body data with PUT, POST, and PATCH requests.

The `Body` tab in Postman enables you to specify the data you need to send with a request. You can send various different types of body data to suit your API.

Choose the data type you need for your request body—form data, URL-encoded, raw, binary, or GraphQL.

### Form data
Website forms often send data to APIs as multipart/form-data. You can replicate this in Postman using the form-data Body tab. Form data enables you to send key-value pairs, and specify the content type.


You can attach files using form data. When you repeatedly make API calls that send the same files, Postman will persist your file paths for later use. This also helps you run collections that contain requests requiring file upload. Uploading multiple files each with their own content type isn't supported.

### URL-encoded
URL-encoded data uses the same encoding as URL parameters. If your API requires url-encoded data, select x-www-form-urlencoded in the Body tab of your request. Enter your key-value pairs to send with the request and Postman will encode them before sending.


### Raw data
Use raw body data to send anything you can enter as text. Use the raw tab, and the type dropdown list to indicate the format of your data (Text, JavaScript, JSON, HTML, or XML) and Postman will enable syntax-highlighting and appending the relevant headers to your request.

Body JSON
Set a content type header manually if you need to override the one Postman sends automatically.

Use variables in your body data and Postman will populate their current values when sending your request.

For JSON raw body data add comments, and they will be stripped out when the request is sent. Single-line comments delimited with // and multi-line comments delimited with /* */ will be removed in the request.



### Binary data
Use binary data to send information you can't enter manually in the Postman editor with your request body, such as image, audio, and video files (you can also send text files).

### GraphQL
Send GraphQL queries with your Postman requests by selecting the GraphQL tab in the request Body. Enter your code in the Query area and any variables in the GraphQL Variables section.


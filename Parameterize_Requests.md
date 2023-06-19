## Instead of creating the same requests with different data, you can use variables with parameters. These data can be from a data file or an environment variable.


1. Set your HTTP request to GET
2. Input this link: https://jsonplaceholder.typicode.com/users. Replace the first part of the link with a parameter such as {{url}}. Request url should now be {{url}}/users.
3. Click send.


## To use the parameter you need to set the environment

1. Click the eye icon
2. Click edit to set the variable to a global environment which can be used in all collections.


In variable,

set the name to the url which is https://jsonplaceholder.typicode.com
click Save.


Go back to your Get request then click send. There should now be results for your request.
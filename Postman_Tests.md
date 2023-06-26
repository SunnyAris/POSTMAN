## TEST 1

1. Go to your GET.

2. Switch to the tests tab. On the right side are snippet codes.

3. From the snippets section, click on “Status code: Code is 200”.

## TEST 2 

1. From the snippets section, click on “Response body:JSON value check”. We will be checking if Leanne Graham has the userid 1.

2. Replace “Your Test Name” from the code with “Check if user with id1 is Leanne Graham” so that the test name specifies exactly what we want to test.

3. Replace jsonData.value with jsonData[0].name. 

4. To get the path, check the body in Get result earlier. 

5. Since Leanne Graham is userid 1, jsonData is in the first result which should start with 0. 

6. If you want to get the second result, use jsonData[1] and so on for succeeding results.

7. In to eql, input “Leanne Graham”
## TEST  200

1. Go to your GET.

2. Switch to the tests tab. On the right side are snippet codes.
```
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
```

3. From the snippets section, click on “Status code: Code is 200”.

## TEST 

1. Replace in GET adress correct path with wrong path 
   
2. From the snippets section, click on “Status code: Code is 200”
   
3. Click send
   
   The test results must be fail


   ## TEST

```
pm.test("Status code is 200", () => {
    pm.response.to.have.status(200);
});
```
1. Copy an paste in onother request on test tab
2. Click send 
3. 
   If test fail with 201 change 200 to 201



## TEST  GET Status
OK


const response = pm. response.json();


console.log(response);



1. Go to the console 
   
2. Click clear
   
3. Send 
   
   On the console status should be "OK" 
```
console.log(response.status);
console.log(response['status']);
```
## TEST 
```
pm.test("Status should be OK", ()=> {
    pm.expect(1).to.eql(1);
});
```
Pass
```
pm.test("Status should be OK", ()=> {
    pm.expect(1).to.eql(2);
});
```
Fail

```
pm.test("Status should be OK", ()=> {
    pm.expect(response.status).to.eql("OK");
});
```
Pass

```
pm.test("Status should be OK", ()=> {
    pm.expect(response.status).to.eql("OK");
});
```
Fail


## TEST 

1. From the snippets section, click on “Response body:JSON value check”. We will be checking if Leanne Graham has the userid 1.

2. Replace “Your Test Name” from the code with “Check if user with id1 is Leanne Graham” so that the test name specifies exactly what we want to test.

3. Replace jsonData.value with jsonData[0].name. 

4. To get the path, check the body in Get result earlier. 

5. Since Leanne Graham is userid 1, jsonData is in the first result which should start with 0. 

6. If you want to get the second result, use jsonData[1] and so on for succeeding results.

7. In to eql, input “Leanne Graham”
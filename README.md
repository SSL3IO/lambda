# SSL3.IO Serverless/Lambda functions
Documention for how to use lambda and routes with SSL3.IO

## Handler format

In the code editor, the format of the function you are writing is this one:

```js
async function(req, res) {

}
```

your function needs to use `res.end(string)` to send data.

## The `req` object

The `req` object contains the request information. 

## The `res` object

The `res` object contains the response methods and parameters (like response code, response headers etc).

## Deploy stack and documentation

```
npm install
./deploy.sh
```

After that you the documentation is going to be updated on `Amazon API Gateway`

`APIs -> dev-serverless-aws-documentation`

If you want to check the models you can go to:

`APIs -> dev-serverless-aws-documentation -> Models`

Here is an example:
![](https://ibin.co/3e0xGO8ucIVB.png)

## Generate Swagger File

You can get the swagger file on:

`APIs -> dev-serverless-aws-documentation -> Stages -> Export`

Or an easier way, just run this script, then grab the downloaded file and copy-paste it into http://editor.swagger.io/

`./download-swagger-json.sh`

Example of the result:

![](https://ibin.co/3e0yZFjwtUTY.png)





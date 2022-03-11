# Subindo imagem no S3 usando Serverless

## Test Example
```bash
curl -H "Content-type: application/json" -d '{"photoUrl":"https://www.petmd.com/sites/default/files/what-does-it-mean-when-cat-wags-tail.jpg"}' 'https://0sdampzeaj.execute-api.eu-west-1.amazonaws.com/dev/upload'
```

## Deploy using serverless
> AWS_PROFILE=rafael-study npx serverless deploy

## Remove Service
> AWS_PROFILE=rafael-study npx serverless remove



https://stackify.com/aws-lambda-with-node-js-a-complete-getting-started-guide/
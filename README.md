# aws-serverless-nodejs-honeycomb-otel
Opentelemetry with honeycomb


```
aws ssm put-parameter \
     --name "/service/demo-lambda-honeycomb/honeycomb/apikey" \
     --description "Honeycomb API key" \
     --type "String" \
     --value "api-key"
"
```
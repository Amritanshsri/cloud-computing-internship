# Task 3 - Create a Serverless Function using AWS Lambda

## Objective

Create a serverless AWS Lambda function that returns JSON output and expose it through a public Function URL.

## Services Used

- AWS Lambda
- Python 3.x

## Function Code

```python
import json

def lambda_handler(event, context):
    return {
        'statusCode': 200,
        'body': json.dumps({
            'message': 'Hello from AWS Lambda',
            'status': 'success'
        })
    }
```

## Steps Performed

1. Created an AWS Lambda function.
2. Selected Python runtime.
3. Added code to return JSON output.
4. Created a test event.
5. Tested the function successfully.
6. Created a public Function URL.
7. Accessed the endpoint through browser.

## Output

```json
{
  "message": "Hello from AWS Lambda",
  "status": "success"
}
```

## Outcome

Successfully deployed and tested a serverless function using AWS Lambda and generated a public endpoint returning JSON data.

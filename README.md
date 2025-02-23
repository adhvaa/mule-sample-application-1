# mule-sample-application-1

curl -L 'https://sample-application-1-roun9e.5sc6y6-1.usa-e2.cloudhub.io/calc' \
-H 'Content-Type: application/json' \
-d '{
    "num1": 10,
    "num2": 2
}'

Expected:
{
    "sum": 12,
    "subtract": 8,
    "multiply": 20,
    "divide": 5
}
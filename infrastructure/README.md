# Create domain stack
```
aws cloudformation create-stack --stack-name techdocs-domain --template-body file:///Users/ethan.mills/code/di-report-a-death-techdocs/infrastructure/custom-domain.yaml --tags Key=Product,Value="GOV.UK Sign In" Key=System,Value="Report a Death" Key=Environment,Value=dev Key=Owner,Value="report-a-death-dev@digital.cabinet-office.gov.uk"
```

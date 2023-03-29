# Build and deploy

Command to build the application. PLease remeber to change the project name and application name
```
gcloud builds submit --tag gcr.io/ntd-costing-tool/ntd-costing-tool --project=ntd-costing-tool
```

Command to deploy the application
```
gcloud run deploy --image gcr.io/ntd-costing-tool/ntd-costing-tool --platform managed  --project=ntd-costing-tool --allow-unauthenticated
```
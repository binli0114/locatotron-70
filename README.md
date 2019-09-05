# Locatotron 70

Locatotron is an application that notifies users of events within a geographic area.

## Requirements

- npm
- AWS CLI
- Serverless framework

## Sls frontend deployment info

Serverless: Stack update finished...
Service Information
service: locatotron-infra
stage: dev
region: us-east-1
stack: locatotron-infra-dev
resources: 21
api keys:
None
endpoints:
None
functions:
None
layers:
None

## sls backend deployment info

Serverless: Stack update finished...
Service Information
service: locatotron-backend
stage: dev
region: us-east-1
stack: locatotron-backend-dev
resources: 60
api keys:
None
endpoints:
PUT - https://sg3z99r9xj.execute-api.us-east-1.amazonaws.com/dev/user
POST - https://sg3z99r9xj.execute-api.us-east-1.amazonaws.com/dev/user/{id}
GET - https://sg3z99r9xj.execute-api.us-east-1.amazonaws.com/dev/user/{id}
DELETE - https://sg3z99r9xj.execute-api.us-east-1.amazonaws.com/dev/user/{id}
PUT - https://sg3z99r9xj.execute-api.us-east-1.amazonaws.com/dev/campaign
GET - https://sg3z99r9xj.execute-api.us-east-1.amazonaws.com/dev/campaign/{id}
POST - https://sg3z99r9xj.execute-api.us-east-1.amazonaws.com/dev/campaign/{id}
PUT - https://sg3z99r9xj.execute-api.us-east-1.amazonaws.com/dev/notify
functions:
setupPostGIS: locatotron-backend-dev-setupPostGIS
createTables: locatotron-backend-dev-createTables
createUser: locatotron-backend-dev-createUser
updateUser: locatotron-backend-dev-updateUser
getUser: locatotron-backend-dev-getUser
deleteUser: locatotron-backend-dev-deleteUser
createCampaign: locatotron-backend-dev-createCampaign
getCampaign: locatotron-backend-dev-getCampaign
updateCampaign: locatotron-backend-dev-updateCampaign
notify: locatotron-backend-dev-notify
layers:
None

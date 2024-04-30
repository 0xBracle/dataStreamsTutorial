
go mod tidy

## Set environment variables
export BASE_URL="test-api.bracle.network"
export CLIENT_ID="YOUR_CLIENT_ID"
export CLIENT_SECRET="YOUR_CLIENT_SECRET"

BASE_URL is the REST endpoint to poll for specific reports.
Replace CLIENT_ID and CLIENT_SECRET with your API credentials

## Fetch and decode a report 

* go run main.go 0x00030a496c736f9e4da3e10c9460c7d7977228e3d22f3df405baf741267f2a29
* go run main.go 0x00030a496c736f9e4da3e10c9460c7d7977228e3d22f3df405baf741267f2a29 0x00030a496c736f9e4da3e10c9460c7d7977228e3d22f3df405baf741267f2a29
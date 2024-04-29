
go mod tidy

## Set environment variables
export BASE_URL="test-api.bracle.network"
export CLIENT_ID="YOUR_CLIENT_ID"
export CLIENT_SECRET="YOUR_CLIENT_SECRET"

BASE_URL is the REST endpoint to poll for specific reports.
Replace CLIENT_ID and CLIENT_SECRET with your API credentials

## Fetch and decode a report 

go run main.go 0x000359843a543ee2fe414dc14c7e7920ef10f4372990b79d6361cdc0dd1ba782
go run main.go 0x000359843a543ee2fe414dc14c7e7920ef10f4372990b79d6361cdc0dd1ba782 0x000359843a543ee2fe414dc14c7e7920ef10f4372990b79d6361cdc0dd1ba782
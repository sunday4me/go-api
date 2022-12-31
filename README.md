# Go API Practice using the Gin framework.

## code to view the data inside the body.json

curl localhost:8080/books --include --header "Content-Type: application/json" -d @body.json --request "POST"

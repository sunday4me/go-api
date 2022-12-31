# Go API Practice using the Gin framework.

## code to add the data inside the body.json to the books

curl localhost:8080/books --include --header "Content-Type: application/json" -d @body.json --request "POST"

## code to checked the added data

curl localhost:8080/books

Once you are running your server from one terminal and using curl in the other terminal to access the files


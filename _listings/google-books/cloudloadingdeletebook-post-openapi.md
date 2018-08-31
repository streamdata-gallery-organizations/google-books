---
swagger: "2.0"
x-collection-name: Google Books
x-complete: 0
info:
  title: Google Books API Remove Book
  description: Remove the book and its contents
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /books/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /cloudloading/addBook:
    post:
      summary: Add Book
      description: Adds a book and its contents
      operationId: books.cloudloading.addBook
      x-api-path-slug: cloudloadingaddbook-post
      parameters:
      - in: query
        name: drive_document_id
        description: A drive document id
      - in: query
        name: mime_type
        description: The document MIME type
      - in: query
        name: name
        description: The document name
      - in: query
        name: upload_client_token
      responses:
        200:
          description: OK
      tags:
      - Book
  /cloudloading/deleteBook:
    post:
      summary: Remove Book
      description: Remove the book and its contents
      operationId: books.cloudloading.deleteBook
      x-api-path-slug: cloudloadingdeletebook-post
      parameters:
      - in: query
        name: volumeId
        description: The id of the book to be removed
      responses:
        200:
          description: OK
      tags:
      - Book
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
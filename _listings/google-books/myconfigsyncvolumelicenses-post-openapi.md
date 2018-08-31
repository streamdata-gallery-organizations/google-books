---
swagger: "2.0"
x-collection-name: Google Books
x-complete: 0
info:
  title: Google Books API Sync Volume Licenses
  description: Request downloaded content access for specified volumes on the My eBooks
    shelf.
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
  /cloudloading/updateBook:
    post:
      summary: Update Book
      description: Updates a book and its contents
      operationId: books.cloudloading.updateBook
      x-api-path-slug: cloudloadingupdatebook-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Book
  /dictionary/listOfflineMetadata:
    get:
      summary: Get Dictionary
      description: Returns a list of offline dictionary metadata available
      operationId: books.dictionary.listOfflineMetadata
      x-api-path-slug: dictionarylistofflinemetadata-get
      parameters:
      - in: query
        name: cpksver
        description: The device/version ID from which to request the data
      responses:
        200:
          description: OK
      tags:
      - Dictionary
  /myconfig/getUserSettings:
    get:
      summary: Get User Settings
      description: Gets the current settings for the user.
      operationId: books.myconfig.getUserSettings
      x-api-path-slug: myconfiggetusersettings-get
      responses:
        200:
          description: OK
      tags:
      - User
  /myconfig/releaseDownloadAccess:
    post:
      summary: Release Access Restrictions
      description: Release downloaded content access restriction.
      operationId: books.myconfig.releaseDownloadAccess
      x-api-path-slug: myconfigreleasedownloadaccess-post
      parameters:
      - in: query
        name: cpksver
        description: The device/version ID from which to release the restriction
      - in: query
        name: locale
        description: ISO-639-1, ISO-3166-1 codes for message localization, i
      - in: query
        name: source
        description: String to identify the originator of this request
      - in: query
        name: volumeIds
        description: The volume(s) to release restrictions for
      responses:
        200:
          description: OK
      tags:
      - Access
  /myconfig/requestAccess:
    post:
      summary: Request Access
      description: Request concurrent and download access restrictions.
      operationId: books.myconfig.requestAccess
      x-api-path-slug: myconfigrequestaccess-post
      parameters:
      - in: query
        name: cpksver
        description: The device/version ID from which to request the restrictions
      - in: query
        name: licenseTypes
        description: The type of access license to request
      - in: query
        name: locale
        description: ISO-639-1, ISO-3166-1 codes for message localization, i
      - in: query
        name: nonce
        description: The client nonce value
      - in: query
        name: source
        description: String to identify the originator of this request
      - in: query
        name: volumeId
        description: The volume to request concurrent/download restrictions for
      responses:
        200:
          description: OK
      tags:
      - Access
  /myconfig/syncVolumeLicenses:
    post:
      summary: Sync Volume Licenses
      description: Request downloaded content access for specified volumes on the
        My eBooks shelf.
      operationId: books.myconfig.syncVolumeLicenses
      x-api-path-slug: myconfigsyncvolumelicenses-post
      parameters:
      - in: query
        name: cpksver
        description: The device/version ID from which to release the restriction
      - in: query
        name: features
        description: List of features supported by the client, i
      - in: query
        name: includeNonComicsSeries
        description: Set to true to include non-comics series
      - in: query
        name: locale
        description: ISO-639-1, ISO-3166-1 codes for message localization, i
      - in: query
        name: nonce
        description: The client nonce value
      - in: query
        name: showPreorders
        description: Set to true to show pre-ordered books
      - in: query
        name: source
        description: String to identify the originator of this request
      - in: query
        name: volumeIds
        description: The volume(s) to request download restrictions for
      responses:
        200:
          description: OK
      tags:
      - Volume License
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
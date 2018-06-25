---
name: Google Books
x-slug: google-books
description: Google Books is our effort to make book content more discoverable on
  the Web. Using the Google Books API, your application can perform full-text searches
  and retrieve book information, viewability and eBook availability. You can also
  manage your personal bookshelves.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
  Shot 2017-03-16 at 4.28.26 PM.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Books
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/apis.md
specificationVersion: "0.14"
apis:
- name: Google Books API Add Book
  x-api-slug: google-books-api
  description: Adds a book and its contents
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//cloudloading/addBook
  tags: Book
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/cloudloadingaddbook-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/cloudloadingaddbook-post-openapi.md
- name: Google Books API Remove Book
  x-api-slug: google-books-api
  description: Remove the book and its contents
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//cloudloading/deleteBook
  tags: Book
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/cloudloadingdeletebook-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/cloudloadingdeletebook-post-openapi.md
- name: Google Books API Update Book
  x-api-slug: google-books-api
  description: Updates a book and its contents
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//cloudloading/updateBook
  tags: Book
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/cloudloadingupdatebook-post-openapi.md
- name: Google Books API Get Dictionary
  x-api-slug: google-books-api
  description: Returns a list of offline dictionary metadata available
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//dictionary/listOfflineMetadata
  tags: Dictionary
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/dictionarylistofflinemetadata-get-openapi.md
- name: Google Books API Get User Settings
  x-api-slug: google-books-api
  description: Gets the current settings for the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//myconfig/getUserSettings
  tags: User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/myconfiggetusersettings-get-openapi.md
- name: Google Books API Release Access Restrictions
  x-api-slug: google-books-api
  description: Release downloaded content access restriction.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//myconfig/releaseDownloadAccess
  tags: Access
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/myconfigreleasedownloadaccess-post-openapi.md
- name: Google Books API Request Access
  x-api-slug: google-books-api
  description: Request concurrent and download access restrictions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//myconfig/requestAccess
  tags: Access
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/myconfigrequestaccess-post-openapi.md
- name: Google Books API Sync Volume Licenses
  x-api-slug: google-books-api
  description: Request downloaded content access for specified volumes on the My eBooks
    shelf.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//myconfig/syncVolumeLicenses
  tags: Volume License
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/myconfigsyncvolumelicenses-post-openapi.md
- name: Google Books API Update User Settings
  x-api-slug: google-books-api
  description: Sets the settings for the user. If a sub-object is specified, it will
    overwrite the existing sub-object stored in the server. Unspecified sub-objects
    will retain the existing value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//myconfig/updateUserSettings
  tags: User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/myconfigupdateusersettings-post-openapi.md
- name: Google Books API Get Annotations
  x-api-slug: google-books-api
  description: Retrieves a list of annotations, possibly filtered.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/annotations
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibraryannotations-get-openapi.md
- name: Google Books API insert Annotation
  x-api-slug: google-books-api
  description: Inserts a new annotation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/annotations
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibraryannotations-post-openapi.md
- name: Google Books API Get Annotation
  x-api-slug: google-books-api
  description: Gets the summary of specified layers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/annotations/summary
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibraryannotationssummary-post-openapi.md
- name: Google Books API Delete Annotation
  x-api-slug: google-books-api
  description: Deletes an annotation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/annotations/{annotationId}
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibraryannotationsannotationid-delete-openapi.md
- name: Google Books API Update Annotation
  x-api-slug: google-books-api
  description: Updates an existing annotation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/annotations/{annotationId}
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibraryannotationsannotationid-put-openapi.md
- name: Google Books API Get Bookshelves
  x-api-slug: google-books-api
  description: Retrieves a list of bookshelves belonging to the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/bookshelves
  tags: Bookshelf
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibrarybookshelves-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibrarybookshelves-get-openapi.md
- name: Google Books API Get Bookshelf
  x-api-slug: google-books-api
  description: Retrieves metadata for a specific bookshelf belonging to the authenticated
    user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/bookshelves/{shelf}
  tags: Bookshelf
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibrarybookshelvesshelf-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibrarybookshelvesshelf-get-openapi.md
- name: Google Books API Add Volume
  x-api-slug: google-books-api
  description: Adds a volume to a bookshelf.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/bookshelves/{shelf}/addVolume
  tags: Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibrarybookshelvesshelfaddvolume-post-openapi.md
- name: Google Books API Clear Volumes
  x-api-slug: google-books-api
  description: Clears all volumes from a bookshelf.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/bookshelves/{shelf}/clearVolumes
  tags: Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibrarybookshelvesshelfclearvolumes-post-openapi.md
- name: Google Books API Move Voume
  x-api-slug: google-books-api
  description: Moves a volume within a bookshelf.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/bookshelves/{shelf}/moveVolume
  tags: Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibrarybookshelvesshelfmovevolume-post-openapi.md
- name: Google Books API Remove Volume
  x-api-slug: google-books-api
  description: Removes a volume from a bookshelf.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/bookshelves/{shelf}/removeVolume
  tags: Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibrarybookshelvesshelfremovevolume-post-openapi.md
- name: Google Books API Get Volume
  x-api-slug: google-books-api
  description: Gets volume information for volumes on a bookshelf.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/bookshelves/{shelf}/volumes
  tags: Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibrarybookshelvesshelfvolumes-get-openapi.md
- name: Google Books API Get Reading Position
  x-api-slug: google-books-api
  description: Retrieves my reading position information for a volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/readingpositions/{volumeId}
  tags: Reading Position
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibraryreadingpositionsvolumeid-get-openapi.md
- name: Google Books API Set Reading Position
  x-api-slug: google-books-api
  description: Sets my reading position information for a volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/readingpositions/{volumeId}/setPosition
  tags: Reading Position
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibraryreadingpositionsvolumeidsetposition-post-openapi.md
- name: Google Books API Get Notification
  x-api-slug: google-books-api
  description: Returns notification details for a given notification id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//notification/get
  tags: Notification
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/notificationget-get-openapi.md
- name: Google Books API List Categoies
  x-api-slug: google-books-api
  description: List categories for onboarding experience.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//onboarding/listCategories
  tags: Category
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/onboardinglistcategories-get-openapi.md
- name: Google Books API List Volumes
  x-api-slug: google-books-api
  description: List available volumes under categories for onboarding experience.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//onboarding/listCategoryVolumes
  tags: Volue
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/onboardinglistcategoryvolumes-get-openapi.md
- name: Google Books API Get Stream
  x-api-slug: google-books-api
  description: Returns a stream of personalized book clusters
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//personalizedstream/get
  tags: Stream
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/personalizedstreamget-get-openapi.md
- name: Google Books API Accept Promotion Offer
  x-api-slug: google-books-api
  description: Accept promotion offer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//promooffer/accept
  tags: Promotion
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/promoofferaccept-post-openapi.md
- name: Google Books API Dismiss Promotion Offer
  x-api-slug: google-books-api
  description: Dismiss promotion offer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//promooffer/dismiss
  tags: Promotion
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/promoofferdismiss-post-openapi.md
- name: Google Books API Get Promotion Offer
  x-api-slug: google-books-api
  description: Returns a list of promo offers available to the user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//promooffer/get
  tags: Promotion
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/promoofferget-get-openapi.md
- name: Google Books API Get Series
  x-api-slug: google-books-api
  description: Returns Series metadata for the given series ids.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//series/get
  tags: Series
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/seriesget-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/seriesget-get-openapi.md
- name: Google Books API Get Series Membership
  x-api-slug: google-books-api
  description: Returns Series membership data given the series id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//series/membership/get
  tags: Series
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/seriesmembershipget-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/seriesmembershipget-get-openapi.md
- name: Google Books API Get Public Bookkshelves
  x-api-slug: google-books-api
  description: Retrieves a list of public bookshelves for the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//users/{userId}/bookshelves
  tags: Bookshelf
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/usersuseridbookshelves-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/usersuseridbookshelves-get-openapi.md
- name: Google Books API Get Public Bookshelf
  x-api-slug: google-books-api
  description: Retrieves metadata for a specific bookshelf for the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//users/{userId}/bookshelves/{shelf}
  tags: Bookshelf
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/usersuseridbookshelvesshelf-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/usersuseridbookshelvesshelf-get-openapi.md
- name: Google Books API Get Public Volumes
  x-api-slug: google-books-api
  description: Retrieves volumes in a specific bookshelf for the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//users/{userId}/bookshelves/{shelf}/volumes
  tags: Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/usersuseridbookshelvesshelfvolumes-get-openapi.md
- name: Google Books API Book Search
  x-api-slug: google-books-api
  description: Performs a book search.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes
  tags: Search
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumes-get-openapi.md
- name: Google Books API Get My Books
  x-api-slug: google-books-api
  description: Return a list of books in My Library.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/mybooks
  tags: Book
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesmybooks-get-openapi.md
- name: Google Books API Get Recommend
  x-api-slug: google-books-api
  description: Return a list of recommended books for the current user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/recommended
  tags: Recommended
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesrecommended-get-openapi.md
- name: Google Books API Rate Recommend
  x-api-slug: google-books-api
  description: Rate a recommended book for the current user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/recommended/rate
  tags: Recommended
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesrecommendedrate-post-openapi.md
- name: Google Books API Get Uploaded
  x-api-slug: google-books-api
  description: Return a list of books uploaded by the current user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/useruploaded
  tags: Upload
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesuseruploaded-get-openapi.md
- name: Google Books API Get Volume
  x-api-slug: google-books-api
  description: Gets volume information for a single volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/{volumeId}
  tags: Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesvolumeid-get-openapi.md
- name: Google Books API Get Associated
  x-api-slug: google-books-api
  description: Return a list of associated books.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/{volumeId}/associated
  tags: Associated
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesvolumeidassociated-get-openapi.md
- name: Google Books API Get Volume Annotations
  x-api-slug: google-books-api
  description: Gets the volume annotations for a volume and layer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/{volumeId}/layers/{layerId}
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesvolumeidlayerslayerid-get-openapi.md
- name: Google Books API Get Volume Annotion
  x-api-slug: google-books-api
  description: Gets the volume annotation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/{volumeId}/layers/{layerId}/annotations/{annotationId}
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesvolumeidlayerslayeridannotationsannotationid-get-openapi.md
- name: Google Books API Get Annotations
  x-api-slug: google-books-api
  description: Gets the annotation data for a volume and layer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/{volumeId}/layers/{layerId}/data
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesvolumeidlayerslayeriddata-get-openapi.md
- name: Google Books API Get Annotation
  x-api-slug: google-books-api
  description: Gets the annotation data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/{volumeId}/layers/{layerId}/data/{annotationDataId}
  tags: Annotation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesvolumeidlayerslayeriddataannotationdataid-get-openapi.md
- name: Google Books API Get Layers
  x-api-slug: google-books-api
  description: List the layer summaries for a volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/{volumeId}/layersummary
  tags: Layer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesvolumeidlayersummary-get-openapi.md
- name: Google Books API Get Layer
  x-api-slug: google-books-api
  description: Gets the layer summary for a volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/{volumeId}/layersummary/{summaryId}
  tags: Layer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesvolumeidlayersummarysummaryid-get-openapi.md
- name: Google Books API
  x-api-slug: google-books-api
  description: The APIs in the Google Books API Family let you bringGoogle Booksfeatures
    to your site or application. The newGoogle Books APIlets you perform programmatically
    most of the operations that you can do interactively on the Google Books website.
    TheEmbedded Viewer APIlets you embed the content directly into your site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Google Books
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/openapi.md
x-common:
- type: x-blog
  url: http://booksearch.blogspot.com
- type: x-blog-rss
  url: http://booksearch.blogspot.com/feeds/posts/default?alt=rss
- type: x-branding-guidelines
  url: https://developers.google.com/books/branding
- type: x-code
  url: https://developers.google.com/books/docs/v1/libraries
- type: x-documentation
  url: https://developers.google.com/books/docs/overview
- type: x-embeddable
  url: https://developers.google.com/books/docs/viewer/developers_guide
- type: x-partners
  url: https://books.google.com/intl/en/googlebooks/partners/
- type: x-privacy-policy
  url: https://books.google.com/intl/en/policies/privacy/
- type: x-terms-of-service
  url: https://developers.google.com/books/terms.html
- type: x-website
  url: https://developers.google.com/books/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
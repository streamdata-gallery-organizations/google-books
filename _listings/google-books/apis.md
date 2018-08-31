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
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/apis.md
specificationVersion: "0.14"
apis:
- name: Books - Add Book
  x-api-slug: cloudloadingaddbook-post
  description: Adds a book and its contents
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/cloudloadingaddbook-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/cloudloadingaddbook-post-openapi.md
- name: Books - Remove Book
  x-api-slug: cloudloadingdeletebook-post
  description: Remove the book and its contents
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/cloudloadingdeletebook-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/cloudloadingdeletebook-post-openapi.md
- name: Books - Update Book
  x-api-slug: cloudloadingupdatebook-post
  description: Updates a book and its contents
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/cloudloadingupdatebook-post-openapi.md
- name: Books - Get Dictionary
  x-api-slug: dictionarylistofflinemetadata-get
  description: Returns a list of offline dictionary metadata available
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/dictionarylistofflinemetadata-get-openapi.md
- name: Books - Get User Settings
  x-api-slug: myconfiggetusersettings-get
  description: Gets the current settings for the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/myconfiggetusersettings-get-openapi.md
- name: Books - Release Access Restrictions
  x-api-slug: myconfigreleasedownloadaccess-post
  description: Release downloaded content access restriction.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/myconfigreleasedownloadaccess-post-openapi.md
- name: Books - Request Access
  x-api-slug: myconfigrequestaccess-post
  description: Request concurrent and download access restrictions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/myconfigrequestaccess-post-openapi.md
- name: Books - Sync Volume Licenses
  x-api-slug: myconfigsyncvolumelicenses-post
  description: Request downloaded content access for specified volumes on the My eBooks
    shelf.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/myconfigsyncvolumelicenses-post-openapi.md
- name: Books - Update User Settings
  x-api-slug: myconfigupdateusersettings-post
  description: Sets the settings for the user. If a sub-object is specified, it will
    overwrite the existing sub-object stored in the server. Unspecified sub-objects
    will retain the existing value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/myconfigupdateusersettings-post-openapi.md
- name: Books - Get Annotations
  x-api-slug: mylibraryannotations-get
  description: Retrieves a list of annotations, possibly filtered.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibraryannotations-get-openapi.md
- name: Books - insert Annotation
  x-api-slug: mylibraryannotations-post
  description: Inserts a new annotation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibraryannotations-post-openapi.md
- name: Books - Get Annotation
  x-api-slug: mylibraryannotationssummary-post
  description: Gets the summary of specified layers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibraryannotationssummary-post-openapi.md
- name: Books - Delete Annotation
  x-api-slug: mylibraryannotationsannotationid-delete
  description: Deletes an annotation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibraryannotationsannotationid-delete-openapi.md
- name: Books - Update Annotation
  x-api-slug: mylibraryannotationsannotationid-put
  description: Updates an existing annotation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibraryannotationsannotationid-put-openapi.md
- name: Books - Get Bookshelves
  x-api-slug: mylibrarybookshelves-get
  description: Retrieves a list of bookshelves belonging to the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibrarybookshelves-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibrarybookshelves-get-openapi.md
- name: Books - Get Bookshelf
  x-api-slug: mylibrarybookshelvesshelf-get
  description: Retrieves metadata for a specific bookshelf belonging to the authenticated
    user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibrarybookshelvesshelf-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibrarybookshelvesshelf-get-openapi.md
- name: Books - Add Volume
  x-api-slug: mylibrarybookshelvesshelfaddvolume-post
  description: Adds a volume to a bookshelf.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibrarybookshelvesshelfaddvolume-post-openapi.md
- name: Books - Clear Volumes
  x-api-slug: mylibrarybookshelvesshelfclearvolumes-post
  description: Clears all volumes from a bookshelf.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibrarybookshelvesshelfclearvolumes-post-openapi.md
- name: Books - Move Voume
  x-api-slug: mylibrarybookshelvesshelfmovevolume-post
  description: Moves a volume within a bookshelf.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibrarybookshelvesshelfmovevolume-post-openapi.md
- name: Books - Remove Volume
  x-api-slug: mylibrarybookshelvesshelfremovevolume-post
  description: Removes a volume from a bookshelf.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibrarybookshelvesshelfremovevolume-post-openapi.md
- name: Books - Get Volume
  x-api-slug: mylibrarybookshelvesshelfvolumes-get
  description: Gets volume information for volumes on a bookshelf.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibrarybookshelvesshelfvolumes-get-openapi.md
- name: Books - Get Reading Position
  x-api-slug: mylibraryreadingpositionsvolumeid-get
  description: Retrieves my reading position information for a volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibraryreadingpositionsvolumeid-get-openapi.md
- name: Books - Set Reading Position
  x-api-slug: mylibraryreadingpositionsvolumeidsetposition-post
  description: Sets my reading position information for a volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/mylibraryreadingpositionsvolumeidsetposition-post-openapi.md
- name: Books - Get Notification
  x-api-slug: notificationget-get
  description: Returns notification details for a given notification id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/notificationget-get-openapi.md
- name: Books - List Categoies
  x-api-slug: onboardinglistcategories-get
  description: List categories for onboarding experience.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/onboardinglistcategories-get-openapi.md
- name: Books - List Volumes
  x-api-slug: onboardinglistcategoryvolumes-get
  description: List available volumes under categories for onboarding experience.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/onboardinglistcategoryvolumes-get-openapi.md
- name: Books - Get Stream
  x-api-slug: personalizedstreamget-get
  description: Returns a stream of personalized book clusters
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/personalizedstreamget-get-openapi.md
- name: Books - Accept Promotion Offer
  x-api-slug: promoofferaccept-post
  description: Accept promotion offer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/promoofferaccept-post-openapi.md
- name: Books - Dismiss Promotion Offer
  x-api-slug: promoofferdismiss-post
  description: Dismiss promotion offer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/promoofferdismiss-post-openapi.md
- name: Books - Get Promotion Offer
  x-api-slug: promoofferget-get
  description: Returns a list of promo offers available to the user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/promoofferget-get-openapi.md
- name: Books - Get Series
  x-api-slug: seriesget-get
  description: Returns Series metadata for the given series ids.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/seriesget-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/seriesget-get-openapi.md
- name: Books - Get Series Membership
  x-api-slug: seriesmembershipget-get
  description: Returns Series membership data given the series id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/seriesmembershipget-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/seriesmembershipget-get-openapi.md
- name: Books - Get Public Bookkshelves
  x-api-slug: usersuseridbookshelves-get
  description: Retrieves a list of public bookshelves for the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/usersuseridbookshelves-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/usersuseridbookshelves-get-openapi.md
- name: Books - Get Public Bookshelf
  x-api-slug: usersuseridbookshelvesshelf-get
  description: Retrieves metadata for a specific bookshelf for the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/usersuseridbookshelvesshelf-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/usersuseridbookshelvesshelf-get-openapi.md
- name: Books - Get Public Volumes
  x-api-slug: usersuseridbookshelvesshelfvolumes-get
  description: Retrieves volumes in a specific bookshelf for the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/usersuseridbookshelvesshelfvolumes-get-openapi.md
- name: Books - Book Search
  x-api-slug: volumes-get
  description: Performs a book search.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumes-get-openapi.md
- name: Books - Get My Books
  x-api-slug: volumesmybooks-get
  description: Return a list of books in My Library.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesmybooks-get-openapi.md
- name: Books - Get Recommend
  x-api-slug: volumesrecommended-get
  description: Return a list of recommended books for the current user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesrecommended-get-openapi.md
- name: Books - Rate Recommend
  x-api-slug: volumesrecommendedrate-post
  description: Rate a recommended book for the current user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesrecommendedrate-post-openapi.md
- name: Books - Get Uploaded
  x-api-slug: volumesuseruploaded-get
  description: Return a list of books uploaded by the current user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesuseruploaded-get-openapi.md
- name: Books - Get Volume
  x-api-slug: volumesvolumeid-get
  description: Gets volume information for a single volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesvolumeid-get-openapi.md
- name: Books - Get Associated
  x-api-slug: volumesvolumeidassociated-get
  description: Return a list of associated books.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesvolumeidassociated-get-openapi.md
- name: Books - Get Volume Annotations
  x-api-slug: volumesvolumeidlayerslayerid-get
  description: Gets the volume annotations for a volume and layer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesvolumeidlayerslayerid-get-openapi.md
- name: Books - Get Volume Annotion
  x-api-slug: volumesvolumeidlayerslayeridannotationsannotationid-get
  description: Gets the volume annotation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesvolumeidlayerslayeridannotationsannotationid-get-openapi.md
- name: Books - Get Annotations
  x-api-slug: volumesvolumeidlayerslayeriddata-get
  description: Gets the annotation data for a volume and layer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesvolumeidlayerslayeriddata-get-openapi.md
- name: Books - Get Annotation
  x-api-slug: volumesvolumeidlayerslayeriddataannotationdataid-get
  description: Gets the annotation data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesvolumeidlayerslayeriddataannotationdataid-get-openapi.md
- name: Books - Get Layers
  x-api-slug: volumesvolumeidlayersummary-get
  description: List the layer summaries for a volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesvolumeidlayersummary-get-openapi.md
- name: Books - Get Layer
  x-api-slug: volumesvolumeidlayersummarysummaryid-get
  description: Gets the layer summary for a volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Books, Google APIs, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-books/master/_listings/google-books/volumesvolumeidlayersummarysummaryid-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.biquery.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.books.stack.network
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
---
name: Flat
x-slug: flat
description: Whether youre a beginner or a professional composer, our user-friendly
  music composition software gives you all the tools that you need to make your own
  sheet music. You can write, listen, share and discover music scores right in your
  web browser on any device
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Metadata
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/metadata/master/_listings/flat/apis.md
specificationVersion: "0.14"
apis:
- name: Flat Get a score's metadata
  x-api-slug: flat
  description: |-
    Get the details of a score identified by the `score` parameter in the URL.
    The currently authenticated user must have at least a read access to the document to use this API call.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2//scores/{score}
  tags: Scores,Metadata
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/metadata/master/_listings/flat/scoresscore-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/metadata/master/_listings/flat/scoresscore-get-openapi.md
- name: Flat Edit a score's metadata
  x-api-slug: flat
  description: |-
    This API method allows you to change the metadata of a score document (e.g. its `title` or `privacy`), all the properties are optional.

    To edit the file itself, create a new revision using the appropriate method (`POST /v2/scores/{score}/revisions/{revision}`).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2//scores/{score}
  tags: Edit,Scores,Metadata
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/metadata/master/_listings/flat/scoresscore-put-openapi.md
- name: Flat
  x-api-slug: flat
  description: 'The Flat API allows you to easily extend the abilities of the [Flat
    Platform](https://flat.io), with a wide range of use cases including the following:
    Creating and importing new music scores using MusicXML or MIDI files. Browsing,
    updating, copying, exporting the users scores (for example in MP3, WAV or MIDI).
    Managing educational resources with Flat for Education: creating &amp; updating
    the organization accounts, the classes, rosters and assignments. The Flat API
    is built on HTTP. Our API is RESTful It has predictable resource URLs. It returns
    HTTP response codes to indicate errors. It also accepts and returns JSON in the
    HTTP body.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2
  tags: Metadata
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/metadata/master/_listings/flat/openapi.md
x-common:
- type: x-developer
  url: https://flat.io/developers
- type: x-embeddable
  url: https://flat.io/developers/embed
- type: x-github
  url: https://github.com/FlatIO
- type: x-pricing
  url: https://flat.io/pricing
- type: x-privacy-policy
  url: https://flat.io/help/en/policies/#coppa-and-ferpa-compliance
- type: x-support
  url: https://flat.io/help
- type: x-twitter
  url: https://twitter.com/flat_io
- type: x-website
  url: http://flat.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
---
name: Google Cloud Natural Language
x-slug: google-cloud-natural-language
description: Google Cloud Natural Language API reveals the structure and meaning of
  text by offering powerful machine learning models in an easy to use REST API. You
  can use it to extract information about people, places, events and much more, mentioned
  in text documents, news articles or blog posts. You can use it to understand sentiment
  about your product on social media or parse intent from customer conversations happening
  in a call center or a messaging app. You can analyze text uploaded in your request
  or integrate with your document storage on Google Cloud Storage.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/powerful-text-analysis-2x.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Cloud Natural Language
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-natural-language/master/_listings/google-cloud-natural-language/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Natural Language - Find Named Entities
  x-api-slug: v1documentsanalyzeentities-post
  description: |-
    Finds named entities (currently proper names and common nouns) in the text
    along with entity types, salience, mentions for each entity, and
    other properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/powerful-text-analysis-2x.png
  humanURL: https://cloud.google.com/natural-language/
  baseURL: ://language.googleapis.com//
  tags: Sentiment Analysis, Machine Learning, Natural Language, Google APIs, Stack
    Network, API Service Provider, API Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-natural-language/master/_listings/google-cloud-natural-language/v1documentsanalyzeentities-post-openapi.md
- name: Google Cloud Natural Language - Analyze SEntiment
  x-api-slug: v1documentsanalyzesentiment-post
  description: Analyzes the sentiment of the provided text.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/powerful-text-analysis-2x.png
  humanURL: https://cloud.google.com/natural-language/
  baseURL: ://language.googleapis.com//
  tags: Sentiment Analysis, Machine Learning, Natural Language, Google APIs, Stack
    Network, API Service Provider, API Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-natural-language/master/_listings/google-cloud-natural-language/v1documentsanalyzesentiment-post-openapi.md
- name: Google Cloud Natural Language - Analyze Syntax
  x-api-slug: v1documentsanalyzesyntax-post
  description: |-
    Analyzes the syntax of the text and provides sentence boundaries and
    tokenization along with part of speech tags, dependency trees, and other
    properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/powerful-text-analysis-2x.png
  humanURL: https://cloud.google.com/natural-language/
  baseURL: ://language.googleapis.com//
  tags: Sentiment Analysis, Machine Learning, Natural Language, Google APIs, Stack
    Network, API Service Provider, API Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-natural-language/master/_listings/google-cloud-natural-language/v1documentsanalyzesyntax-post-openapi.md
- name: Google Cloud Natural Language - Annotate Text
  x-api-slug: v1documentsannotatetext-post
  description: |-
    A convenience method that provides all the features that analyzeSentiment,
    analyzeEntities, and analyzeSyntax provide in one call.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/powerful-text-analysis-2x.png
  humanURL: https://cloud.google.com/natural-language/
  baseURL: ://language.googleapis.com//
  tags: Sentiment Analysis, Machine Learning, Natural Language, Google APIs, Stack
    Network, API Service Provider, API Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-natural-language/master/_listings/google-cloud-natural-language/v1documentsannotatetext-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.cloud.machine.learning.engine.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.cloud.natural.language.stack.network
- type: x-change-log
  url: https://cloud.google.com/natural-language/release-notes
- type: x-documentation
  url: https://cloud.google.com/natural-language/docs/
- type: x-getting-started
  url: https://cloud.google.com/natural-language/docs/getting-started
- type: x-guides
  url: https://cloud.google.com/natural-language/docs/how-to
- type: x-libraries
  url: https://cloud.google.com/natural-language/docs/reference/libraries
- type: x-price
  url: https://cloud.google.com/natural-language/pricing
- type: x-rate-limits
  url: https://cloud.google.com/natural-language/limits
- type: x-sample-applications
  url: https://cloud.google.com/natural-language/docs/samples
- type: x-support
  url: https://cloud.google.com/natural-language/support
- type: x-website
  url: https://cloud.google.com/natural-language/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
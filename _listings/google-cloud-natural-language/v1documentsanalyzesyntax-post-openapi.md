---
swagger: "2.0"
x-collection-name: Google Cloud Natural Language
x-complete: 0
info:
  title: Google Cloud Natural Language API Analyze Syntax
  description: |-
    Analyzes the syntax of the text and provides sentence boundaries and
    tokenization along with part of speech tags, dependency trees, and other
    properties.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: language.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/documents:analyzeEntities:
    post:
      summary: Find Named Entities
      description: |-
        Finds named entities (currently proper names and common nouns) in the text
        along with entity types, salience, mentions for each entity, and
        other properties.
      operationId: language.documents.analyzeEntities
      x-api-path-slug: v1documentsanalyzeentities-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Entities
  /v1/documents:analyzeSentiment:
    post:
      summary: Analyze SEntiment
      description: Analyzes the sentiment of the provided text.
      operationId: language.documents.analyzeSentiment
      x-api-path-slug: v1documentsanalyzesentiment-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Sentiment
  /v1/documents:analyzeSyntax:
    post:
      summary: Analyze Syntax
      description: |-
        Analyzes the syntax of the text and provides sentence boundaries and
        tokenization along with part of speech tags, dependency trees, and other
        properties.
      operationId: language.documents.analyzeSyntax
      x-api-path-slug: v1documentsanalyzesyntax-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Syntax
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
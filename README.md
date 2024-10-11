# Master OpenAPI (formerly Swagger) to Create Specifications for Your APIs

## Overview of OpenAPI

### Why OpenAPI?
- OpenAPI - short for OpenAPI Specification
  - Often abbreviated as OA3 - for OpenAPI 3.x
- OpenAPI is a widely adopted standard for describing APIs
- Strong Industry Support for OpenAPI
  - Backers include - Microsoft, Google, and IBM
- OpenAPI is considered technology agnostic
  - Thus, developers using Java, .NET, PHP, Ruby, etc - can all benefit from OpenAPI
- OpenAPI Specifications are defined in YAML or JSON
- The OpenAPI Specification is backed by a formal schema
  - This defines the document’s properties and data types
- Because the OpenAPI is a structured document it can be read programmatically
- OpenAPI Tools - Converters, Validators, GUI Editors, Mock Services, SDK Generators,
Documentation
- OpenAPI CodeGen - Generate Server code for 20+ different languages; Client code for 40+
languages

### Pet CLinic Swagger
- [petstore.yaml](https://github.com/OAI/OpenAPI-Specification/blob/main/examples/v3.0/petstore.yaml)

### YAML Crash course
- [YAML syntax](https://learnxinyminutes.com/docs/yaml/)

## Defining a Microserice with OpenAPI
- [Swagger Editor](https://swagger.io/tools/swaggerhub/)
- [OpenAPI Specification](https://github.com/OAI/OpenAPI-Specification)
- [Implementations](https://tools.openapis.org/)

### OpenAPI Info Object
- Info object](https://github.com/OAI/OpenAPI-Specification/blob/main/versions/3.0.2.md#info-object)

### OpenAPI Servers Object
- [server-object](https://github.com/OAI/OpenAPI-Specification/blob/main/versions/3.0.2.md#server-object)

### OpenAPI Paths Object
- [Paths object](https://github.com/OAI/OpenAPI-Specification/blob/main/versions/3.0.2.md#pathsObject)

## OpenAPI Schema

### JSON Schema
- [JSON Schema Reference](https://json-schema.org/understanding-json-schema)
### OpenAPI Data Types
- [Data types](https://github.com/OAI/OpenAPI-Specification/blob/main/versions/3.0.2.md#data-types)

### OpenAPI Objects
-[Schema object](https://github.com/OAI/OpenAPI-Specification/blob/main/versions/3.0.2.md#schema-object)
### OpenAPI Enums
```
          enum:
          - AL
          - AK
          - AZ
          - AR
          - CA
          
          #OR
          enum: [AL, AK, AZ, AR, CA]
```
## OpenAPI Components
### OpenAPI Components Objects
- [Components object](https://github.com/OAI/OpenAPI-Specification/blob/main/versions/3.0.2.md#components-object)

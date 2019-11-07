# Swagger &

# Code Generation

#### COMPARISON OF AUTOMATIC CODE GENERATION TOOLS FOR SWAGGER FILE

#### FORMAT - 14 MAY 2015


## Criteria for selection

##### 1) Code generator must support Swagger file format

##### 2) Only client-side bindings are considered

##### 3) Must create complete libraries rather than just code snippets

##### 3) Only the following languages are considered

###### ◦ C#

###### ◦ Java / Android

###### ◦ Objective-C

###### ◦ PHP

###### ◦ Python

###### ◦ Ruby


## Code Generators Considered

##### INCLUDED (BASED ON CRITERIA)

##### 1) Swagger CodeGen (http://editor.swagger.io)

##### 2) REST United (http://restunited.com)

##### 3) Restlet Studio (http://studio.restlet.com)

##### 4) APIMATIC (https://apimatic.io)

##### EXCLUDED (BASED ON CRITERIA)

##### 1) Paw (https://luckymarmot.com/paw)

```
◦ Generates only code snippets
```
```
◦ Does not support Swagger
```
##### 2) Alpaca (https://github.com/pksunkara/alpaca)

```
◦ Does not support Swagger
```

## Code Base for CodeGen Engines

##### 1. Swagger.IO is the official host for open source Swagger CodeGen project

##### 2. REST United uses a customized version of Swagger CodeGen project and performs better

##### than the official branch

##### 3. Restlet Studio uses Swagger CodeGen for Objective-C, but has its own CodeGen engine for

##### Android and Java

##### 4. APIMATIC has its own CodeGen engine for all languages


### Test 1

### Google

### Spreadsheets

### API

###### Process Swagger.IO REST United APIMATIC

###### Import Partial Success Partial Success Success

```
Swagger JSON 2 Warnings 145 Warnings Success
```
###### Code Generation Partial Success Success Success

```
Android Error Success Success
```
```
C# Success Success Success
```
```
Java Error Success Success
```
```
Objective-C Error Success Success
```
```
PHP Success Success Success
```
```
Python Success Success Success
```
```
Ruby Success Success Success
```
###### Compilation Failed Partial Success Success

```
Android - Failed - 31 Errors Success
```
```
C# Failed - 18 Errors Failed - 46 Errors Success
```
```
Java - Failed - 31 Errors Success
```
```
Objective-C - Success Success
```
```
PHP Failed - 76 Errors Success Success
```
```
Python Failed - 1 Errors Failed - 1 Errors Success
```
```
Ruby Failed - 1 Errors Success Success
```
**Swagger Version:** 2.

**Swagger Url:**
https://raw.githubusercontent.com/
kinlane/api-stack/gh-pages/data/go
ogle/google-spreadsheets-swagger.j
son

**Swagger Author:** Kin Lane

**Number of Endpoints:** 76

**Number of Models:** 0

**Contains Auth Info:** No

**Contains Error Info:** No

```
Restlet Studio does not support Swagger 2.
```

### Test 2

### GitHub API

###### Process Swagger.IO REST United APIMATIC

###### Import Partial Success Partial Success Success

```
Swagger JSON 1 Warnings 249 Warnings Success
```
###### Code Generation Partial Success Success Success

```
Android Error Success Success
```
```
C# Success Success Success
```
```
Java Error Success Success
```
```
Objective-C Error Success Success
```
```
PHP Success Success Success
```
```
Python Success Success Success
```
```
Ruby Success Success Success
```
###### Compilation Partial Success Partial Success Success

```
Android - Success Success
```
```
C# Failed - 18 Errors Failed - 12 Errors Success
```
```
Java - Success Success
```
```
Objective-C - Failed – 43+ Errors Success
```
```
PHP Success Success Success
```
```
Python Failed - 1 Errors Failed - 1 Errors Success
```
```
Ruby Failed - 1 Errors Failed - 1 Errors Success
```
**Swagger Version:** 2.

**Swagger Url:**
https://raw.githubusercontent.com/
kinlane/api-stack/gh-pages/data/git
hub/github-swagger.json

**Swagger Author:** Kin Lane

**Number of Endpoints:** 131

**Number of Models:** 0

**Contains Auth Info:** No

**Contains Error Info:** No

```
Restlet Studio does not support Swagger 2.
```

### Test 3

### Uber API

###### Process Swagger.IO REST United APIMATIC

###### Import Partial Success Partial Success Success

```
Swagger YAML 8 Warnings YAML (Used JSON) Success
```
###### Code Generation Success Success Success

```
Android Success Success Success
```
```
C# Success Success Success
```
```
Java Success Success Success
```
```
Objective-C Success Success Success
```
```
PHP Success Success Success
```
```
Python Success Success Success
```
```
Ruby Success Success Success
```
###### Compilation Partial Success Partial Success Success

```
Android Failed - 2 Errors Success Success
```
```
C# Success Success Success
```
```
Java Success Success Success
```
```
Objective-C Success Success Success
```
```
PHP Success Success Success
```
```
Python Success Failed - 1 Errors Success
```
```
Ruby Success Failed - 6 Errors Success
```
**Swagger Version:** 2.

**Swagger Url:**
https://raw.githubusercontent.com/
swagger-api/swagger-spec/master/
examples/v2.0/yaml/uber.yaml

**Swagger Author:** Tony Tam

**Number of Endpoints:** 5

**Number of Models:** 7

**Contains Auth Info:** No

**Contains Error Info:** Yes

```
Restlet Studio does not support Swagger 2.
```

### Test 4

### Simple

### Pet-Store

### API

###### Process Restlet Studio REST United APIMATIC

###### Import Success Failed Success

```
Swagger JSON Failed at import Success
```
###### Code Generation Success Not Imported Success

```
Android Success - Success
```
```
C# Not Supported - Success
```
```
Java Success - Success
```
```
Objective-C Success - Success
```
```
PHP Not Supported - Success
```
```
Python Not Supported - Success
```
```
Ruby Not Supported - Success
```
###### Compilation Partial Success Not Generated Success

```
Android Success - Success
```
```
C# Not Supported - Success
```
```
Java Success - Success
```
```
Objective-C Failed – 10+ Errors - Success
```
```
PHP Not Supported - Success
```
```
Python Not Supported - Success
```
```
Ruby Not Supported - Success
```
**Swagger Version:** 1.

**Swagger Url:**
https://raw.githubusercontent.com/m
ission-liao/pyswagger/9b029f
31cca0aebac366754318230802a/pysw
agger/tests/data/v1_2/wordnik/pet.js
on

**Swagger Author:** Tony Tam

**Number of Endpoints:** 9

**Number of Models:** 4

**Contains Auth Info:** No

**Contains Error Info:** Yes

```
Swagger.IO does not support Swagger 1.
```

### Test 5

### Pet-Store

### Schema

### API

###### Process Restlet Studio REST United APIMATIC

###### Import Success Failed Success

```
Swagger JSON Failed at import Failed at import Success
```
###### Code Generation Not Imported Not Imported Success

```
Android - - Success
```
```
C# Not Supported - Success
```
```
Java - - Success
```
```
Objective-C - - Success
```
```
PHP Not Supported - Success
```
```
Python Not Supported - Success
```
```
Ruby Not Supported - Success
```
###### Compilation Not Generated Not Generated Success

```
Android - - Success
```
```
C# Not Supported - Success
```
```
Java - - Success
```
```
Objective-C - - Success
```
```
PHP Not Supported - Success
```
```
Python Not Supported - Success
```
```
Ruby Not Supported - Success
```
**Swagger Version:** 1.

**Swagger Url:**
https://raw.githubusercontent.com/
signalfx/swagger-cli-client/master/e
xample/petstore-schema.json

**Swagger Author:** Tony Tam

**Number of Endpoints:** 20

**Number of Models:** 5

**Contains Auth Info:** No

**Contains Error Info:** Yes

```
Swagger.IO does not support Swagger 1.
```

### Test 6

### Marvel

### Comics

### API

###### Process APIMATIC

###### Import Success

```
Swagger JSON Success
```
###### Code Generation Success

```
Android Success
```
```
C# Success
```
```
Java Success
```
```
Objective-C Success
```
```
PHP Success
```
```
Python Success
```
```
Ruby Success
```
###### Compilation Success

```
Android Success
```
```
C# Success
```
```
Java Success
```
```
Objective-C Success
```
```
PHP Success
```
```
Python Success
```
```
Ruby Success
```
**Swagger Version:** 1.

**Swagger Url:**

[http://gateway.marvel.com/docs/p](http://gateway.marvel.com/docs/p)

ublic

**Swagger Author:** Marvel Offical

**Number of Endpoints:** 39

**Number of Models:** 37

**Contains Auth Info:** No

**Contains Error Info:** Yes

```
Swagger 1.1, 1.2 are currently only supported by APIMATIC
```

## Compilation Success?

###### Successful compilation does not mean that the SDK will work out of the box!

###### 1. Missing Authentication Info

```
◦ Swagger.IO and Restlet Studio do not generate authentication code, even when auth info is available
◦ APIMATIC and REST United support OAuth 1 & 2, Basic Auth, and Custom Headers/Parameters
```
###### 2. Missing Schemas/Model definitions

```
◦ All except APIMATIC use “void” return type when schemas are missing
◦ This essentially means all responses are ignored, and no data is returned
```
###### 3. APIMATIC’s struggle: SDK’s should work out of the box!

```
◦ Generated code often does not work out of the box, AND to make matter even worse, its not even easy to fix by
hand
```
```
◦ APIMATIC has implemented fallbacks to handle missing schemas and model definitions
```
```
◦ Missing auth info cannot be fixed by any fallback measure
```

## Swagger Completeness

##### INCOMPLETE SWAGGERS

##### 1. Invalid JSON

##### 2. Missing BaseURIs

##### 3. Missing Authentication Information

##### 4. Missing Endpoint OperationIds/NickNames

##### 5. Missing Schemas/Models

##### 6. Missing Error Codes/Messages

##### PROPOSAL FOR ENHANCEMENTS

##### 1. Support for Streaming API/WebHooks

##### 2. Support for Error Models, not just Error

##### Messages


## Functionality + Code Quality

##### 1. Idiomatic Code

###### ◦ Naming conventions

###### ◦ Design patterns

###### ◦ Namespaces and packaging

##### 2. General Code Climate

###### ◦ High readability and general formatting

###### ◦ Code comments

###### ◦ Redundant and unreachable code

##### 3. Completeness

###### ◦ Generate IDE support (Visual Studio, XCode, Android Studio, Eclipse)

###### ◦ Enabled IDE type-hinting (PyCharm, Ruby Mine, Netbeans)

###### Functional

###### Code is not

###### good enough!


## CodeGen Settings


## Code-Generation-as-a-Service

##### 1. APIMATIC’s CGaaS is available as an API

###### ◦ Accepts API Description (Swagger, RAML, API Blueprint, IO Docs, Google Discovery)

##### 2. Embeddable JavaScript widget

###### ◦ Just maintain your API description, and the widget provides fresh SDKs from your own dev-portal

##### 3. GitHub widget

###### ◦ Uses API Commons discovery manifest to locate API description - Provides SDKs from GitHub repos

##### 4. APIMATIC On-Prem

###### ◦ Available as a universal Linux binary - Provides simple locally hosted API

##### 5. APIMATIC – SmartBear Ready! API Plugin

###### ◦ Generates SDKs from inside Ready! API

###### Only Possible

###### when SDKs

###### work out of

###### the box


## SDKS.IO – The SDK Search Engine

##### Statistics for Sources of API Descriptions


## SDKS.IO – The SDK Search Engine

##### Statistics for API Descriptions Located


## Our Latest Feature - Streaming APIs

##### 1. We have recently launched support for Streaming APIs

###### ◦ Deserializes a stream of JSON Objects asynchronously

##### 2. Currently available in C#, Java and Android

##### Examples

###### ◦ Twitter Streaming API

###### ◦ CBIX (bitcoin exchange – real-time index and trades)




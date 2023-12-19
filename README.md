# ww-swivle-postman-collection
# Introduction

This is a Postman collection for working with WoodWing Swivle. The collection itself contains all of the available API calls. The goal of the collection is to provide users a tool that helps a developer understand the API calls that Swivle has and allow the user to quickly see those calls working. 

This collection goes hand in hand with the API documentation that is provided along with Swivle. 

That includes the following: 

1. The Swivle API documentation located [here.](https://help.swivle.com/en/articles/1696707-the-swivle-api)
2. The Swivle API reference. Note that reference link is located in the 'API' menu in the management console of Swivle

In some cases we have added parameters to the calls so that they may be more useful as a starting point.

Note that the starting point for this collection is going into Swivle and obtaining the API Key via the management console. 

# Postman Explanation

When creating this collection we considered three parts of Postman's capabilities:

Collections
Environments
Flows (part of Postman 10)
Please note that to use this collection you will need to create your Environment and, if you wish to use Flows, you'll need to create those as well. Farther down we have included videos to help out with that process.

The relationship between the Collection and the Environments is particularly helpful. Environments allows us to create variables, attach values to the variables and then pass the variable value(s) to subsequent calls. The variables can be used calling each individual call within the collection or you can set up a Flow to use them.

In our environment, named 'WoodWing Swivle', we have a variety of variables:

- Swivle API URL: Add to the body parameters as {{Swivle API URL}}
- uploadUrl: Add to the body parameters as {{uploadUrl}}
- apiKey: Add to the body parameters as {{apiKey}}
- authToken: Add to the body parameters as {{authToken}}
- assetId: Add to the body parameters as {{assetId}}
- folderId: Add to the body parameters as {{folderId}}

# List of calls within the collection

Authentication
- api-key-login

Manage Assets
- Create Asset Placeholder
- Put Asset using Upload URL
- Create version via multi-part POST
- Create version via PUT
- Get Asset by ID
- Delete Asset by ID
- Copy Asset
- Update Asset Metadata
- Move Asset
- Download Asset File
- Download Asset Preview
- Download Asset Thumbnail

Collection
- Create Collection
- Retrieve Collection by Id
- Delete Collection by Id
- Add Children to Collection
- Remove Children from Collection
- Update Collection Metadata
- Move Collection
   
Folders
- Create a folder
- Retrieve Folder by Path
- Retrieve Folder by Id
- Move a Folder
- Delete a Folder
   
Search
- Search
   
Sharelinks
- Create a Sharelink

# Release Notes
v0.1 - Initial release of the collection

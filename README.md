# ww-swivle-postman-collection
# Introduction

This is a Postman collection for working with WoodWing Swivle. The collection itself contains all of the available API calls. The goal of the collection is to provide users a tool that helps a developer understand the API calls that Swivle has and allow the user to quickly see those calls working. 

This collection goes hand in hand with the API documentation that is provided along with Swivle. 

That includes the following: 

1. The Swivle API documentation located [here.](https://help.swivle.com/en/articles/1696707-the-swivle-api)
2. The Swivle API reference. Note that reference link is located in the 'API' menu in the management console of Swivle

In some cases we have added parameters to the calls so that they may be more useful as a starting point.

# Postman Explanation

When creating this collection we considered three parts of Postman's capabilities:

Collections
Environments
Flows (part of Postman 10)
Please note that to use this collection you will need to create your Environment and, if you wish to use Flows, you'll need to create those as well. Farther down we have included videos to help out with that process.

The relationship between the Collection and the Environments is particularly helpful. Environments allows us to create variables, attach values to the variables and then pass the variable value(s) to subsequent calls. The variables can be used calling each individual call within the collection or you can set up a Flow to use them.

In our environment, named 'WoodWing Studio', we have a variety of variables:

Swivle API URL - Add to the body parameters as {{Swivle API URL}}
uploadUrl - Add to the body parameters as {{uploadUrl}}
apiKey - Add to the body parameters as {{apiKey}}
authToken - Add to the body parameters as {{authToken}}
assetId - Add to the body parameters as {{assetId}}
folderId - Add to the body parameters as {{folderId}}

# List of calls within the collection

Authentication
1. api-key-login

Manage Assets
1. Create Asset Placeholder
2. Put Asset using Upload URL
3. Create version via multi-part POST
4. Create version via PUT
5. Get Asset by ID
6. Delete Asset by ID
7. Copy Asset
8. Update Asset Metadata
9. Move Asset
10. Download Asset File
11. Download Asset Preview
12. Download Asset Thumbnail

Collection
1. Create Collection
2. Retrieve Collection by Id
3. Delete Collection by Id
4. Add Children to Collection
5. Remove Children from Collection
6. Update Collection Metadata
7. Move Collection
   
Folders
1. Create a folder
2. Retrieve Folder by Path
3. Retrieve Folder by Id
4. Move a Folder
5. Delete a Folder
   
Search
1. Search
   
Sharelinks
1. Create a Sharelink

# Release Notes
v0.1 - Initial release of the collection

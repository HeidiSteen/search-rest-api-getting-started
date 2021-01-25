# Search-rest-api-getting-started sample

This legacy [Azure Cognitive Search](https://docs.microsoft.com/azure/search/) sample includes scripted REST API requests that demonstrate the following operations:

* [Create and Delete a search index](https://docs.microsoft.com/rest/api/searchservice/create-index)
* [Upload Documents](https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents) to a search index
* [Search & Filter Documents](https://docs.microsoft.com/rest/api/searchservice/search-documents) within an index

## Status: Archived

This sample is archived and will no longer be maintained. For an alternative resource, we recommend the [Azure-Samples/azure-search-postman-samples](https://github.com/Azure-Samples/azure-search-postman-samples) repository.

## Run the sample

The REST API sample is currently a PowerShell script that runs on Windows.

1. Edit the script `RestHowTo\RestHowTo.ps1`. Set the `$apiKey` and `$searchServiceName` variables at the top of the file to the admin key and name of your Azure Cognitive Search service.
1. Open a PowerShell command prompt.
1. Navigate to the `RestHowTo` directory and run `./RestHowTo.ps1`.

## About this project

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

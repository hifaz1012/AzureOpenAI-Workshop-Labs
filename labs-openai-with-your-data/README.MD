**Documentation :-**

Follow the steps below and upload travel_brochures PDF files.

https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/use-your-data?tabs=ai-search%2Ccopilot

https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart?tabs=command-line%2Cpython-new&pivots=programming-language-studio


**Sample Questions :-**

1. Tell me about London?

2. What are the accommodation options in London?

With "Azure OpenAI with your data" the responses will be grounded to the PDF documents.

**Deploy to webapps**

After Deploy to webapps, Follow these steps to assign Managed Identity permissions 

https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/use-web-app#assign-rbac-roles-to-enable-intra-service-communication

Check AZURE_OPENAI_KEY and AZURE_OPENAI_ENDPOINT is correctly set in environment variables of Azure APP Service.

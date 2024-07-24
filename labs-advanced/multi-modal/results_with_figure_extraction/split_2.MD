Architecturally, a search service sits between the external data stores that contain your un-indexed data, and your client app that sends query requests to a search index and handles the response.  
<figure>  
![](figures/0)<!-- FigureContent="The image you provided is a flowchart diagram that illustrates the architecture and data flow of a search system using Azure Cognitive Search. Here's the step-by-step process depicted in the diagram:  
1. "Your content": This refers to the data source, represented by icons suggesting cloud storage and a firewall, indicating that the content can be located both in the cloud or behind a firewall.  
2. The data then goes through several processes within the Azure Cognitive Search service:
a. Full Indexing
b. Refresh Indexing
c. AI Enrichment  
3. "Indexing engine": After the data is processed for search, it is passed to an indexing engine as part of the Azure Cognitive Search service.  
4. "Indexes and other structures": The indexing engine creates searchable indexes and possibly other structured data to facilitate efficient queries.  
5. "Query engine": When a query is made, it is handled by the query engine which utilizes the indexes and other structures to find relevant data.  
6. "Query requests" and "Query responses": The system handles incoming search requests and sends back search responses to the user or application which initiated the query.  
7. "Your app": This box refers to the application using the search service. The application:
a. Collects user input
b. Formulates and sends search requests
c. Handles the responses either as a result set or a single document. The specifics are indicated by the ellipsis (...), suggesting there could be more actions the app performs with the responses.  
This diagram likely serves an educational or instructional purpose to explain how Azure Cognitive Search can be integrated with user applications to provide search capabilities." --></figure>  
In your client app, the search experience is defined using APIs from Azure Cognitive Search, and can include relevance tuning, semantic ranking, autocomplete, synonym matching, fuzzy matching, pattern matching, filter, and sort.  
Across the Azure platform, Cognitive Search can integrate with other Azure services in the form of indexers that automate data ingestion/retrieval from Azure data sources, and skillsets that incorporate consumable Al from Cognitive Services, such as image and
:unselected:
<!-- PageHeader="natural language processing, or custom Al that you create in Azure Machine Learning or wrap inside Azure Functions." -->
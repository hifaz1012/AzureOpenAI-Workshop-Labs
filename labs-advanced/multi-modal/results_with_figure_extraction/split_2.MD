Architecturally, a search service sits between the external data stores that contain your un-indexed data, and your client app that sends query requests to a search index and handles the response.  
<figure>  
![](figures/0)<!-- FigureContent="This image is a flowchart depicting the process and components involved in using Azure Cognitive Search with your content and application. Here's the detailed description:  
### Components:
1. **Your Content**:
- Represented with icons for different types of data storage (e.g., a cylinder for databases, a cloud for cloud storage, and a firewall for secured content).
- The text notes that your content can be "in the cloud or behind a firewall".  
2. **Azure Cognitive Search**:
- Contains three main text boxes: "Indexing engine," "Indexes and other structures," and "Query engine".
- Azure Cognitive Search includes:
- **Indexing engine**:
- Ingests content through full indexing and refresh indexing.
- Incorporates AI enrichment.
- **Indexes and other structures**: Indexed data is stored and structured for efficient querying.
- **Query engine**: Processes the query requests and provides query responses.  
3. **Your App**:
- Depicted with an app icon and a list of steps your app performs:
1. Collects user input.
2. Formulates and sends requests.
3. Handles responses (which can be a result set, a single document, etc.).  
### Process Flow:
- **From Your Content to Azure Cognitive Search**:
- Full indexing, refresh indexing, and AI enrichment are the processes that move data from your content to the Azure Cognitive Search's indexing engine and subsequently to the indexes and other structures.  
- **From Azure Cognitive Search to Your App**:
- The query engine in Azure Cognitive Search handles query requests from your application.
- Query responses are sent back to your application.  
Overall, the image demonstrates how content from various sources can be indexed and enriched using Azure Cognitive Search, and how queries can be made to retrieve this indexed information for use in your application." --></figure>  
In your client app, the search experience is defined using APIs from Azure Cognitive Search, and can include relevance tuning, semantic ranking, autocomplete, synonym matching, fuzzy matching, pattern matching, filter, and sort.  
Across the Azure platform, Cognitive Search can integrate with other Azure services in the form of indexers that automate data ingestion/retrieval from Azure data sources, and skillsets that incorporate consumable Al from Cognitive Services, such as image and
:unselected:
<!-- PageHeader="natural language processing, or custom Al that you create in Azure Machine Learning or wrap inside Azure Functions." -->
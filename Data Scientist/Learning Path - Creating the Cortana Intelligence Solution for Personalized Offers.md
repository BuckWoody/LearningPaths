
# Learning Path - Creating the Cortana Intelligence Solution for Personalized Offers

## Audience: Data Engineer/Data Scientist

## Type: Solution

### Summary
Surfacing offers that are customized for the user has become essential to building customer loyalty and remaining profitable. On a retail website, customers desire intelligent systems which provide offers and content based on their unique interests and preferences. Today's digital marketing teams can build this intelligence using the data generated from all types of user interactions. By analyzing massive amounts of data, marketers have the unique opportunity to deliver highly relevant and personalized offers to each user. However, building a reliable and scalable big data infrastructure, and developing sophisticated machine learning models that personalize to each user is not trivial.

The Cortana Intelligence Suite provides advanced analytics tools through Microsoft Azure - data ingestion, data storage, data processing and advanced analytics components - all of the essential elements for building a personalized offer solution.

This solution combines several Azure services to provide powerful advantages. Event Hubs collects real-time consumption data. Stream Analytics aggregates the streaming data and makes it available for visualization, as well as updating the data used in making personalized offers to the customer. Azure DocumentDB stores the customer, product and offer information. Azure Storage is used to manage the queues that simulate user interaction. Azure Functions are used as a coordinator for the user simulation and as the central portion of the solution for generating personalized offers. Azure Machine Learning implements and executes the user to product affinity scoring and when no user history is available Azure Redis Cache is used to provide pre-computed product affinities for the customer. PowerBI visualizes the real-time activity for the system and with the data from DocumentDB the behavior of the various offers.


### Lesson Path

| Objective | Concept | Resource | Technologies | Level | Prerequisites |
|----------------------------------------------------------|-----------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|-------------------------------------------------------------------------|
| Understand how to develop and consume a   solution | Team Data Science Process | This web page [about the TDSP](https://azure.microsoft.com/en-us/documentation/learning-paths/data-science-process/) | None | Overview | None | 
|  | Cortana Intelligence Suite | This online course [about the Cortana Intelligence Suite](https://mva.microsoft.com/en-US/training-courses/cortana-intelligence-suite-endtoend-16972?l=W7jo0cDKD_7306218965) | Cortana Intelligence Suite | Intermediate | None |  
|  |  | This web page [about Cortana Intelligence](https://www.microsoft.com/en-us/cloud-platform/what-is-cortana-intelligence) | Cortana Intelligence Suite | Overview | None | 
|  | Cortana Intelligence Solution Templates | This video [about solution templates](https://channel9.msdn.com/events/Data-Science/Microsoft-Data-Amp-2017/Deploy-an-intelligent-solution-with-Solution-Templates?term=solution%20architecture) | Cortana Intelligence Suite | Overview | None | 
| Be able to store data | Azure Storage Que | This web pages about [storage queues](https://azure.microsoft.com/en-us/services/storage/queues/) | Storage Queues | Overview | None | 
|  |  | This tutorial for [getting started with storage queues](https://docs.microsoft.com/en-us/azure/storage/storage-dotnet-how-to-use-queues) | Storage Queues | Beginner | None | 
|  | Azure DocumentDB | This web page [about CosmosDB](https://azure.microsoft.com/en-us/services/cosmos-db/) | CosmosDB | Beginner | NoSQL experience | 
|  |  | This tutorial about [NoSQL in CosmosDB](https://docs.microsoft.com/en-us/azure/cosmos-db/documentdb-java-get-started) | CosmosDB, Java, NoSQL | Beginner | NoSQL, Java, programming experience | 
|  | Azure Redis Cache | This video about [Redis Cache best practices](https://azure.microsoft.com/en-us/resources/videos/azure-redis-cache-best-practices/) | Redis Cache | Intermediate | Redis Cache experience | 
|  |  | This web page about [Redis Cache and the value proposition](https://azure.microsoft.com/en-us/services/cache/) | Redis Cache | Overview | Database understanding | 
| Be able to ingest data | Azure Event Hubs | This web page [about Azure event hubs](https://azure.microsoft.com/en-us/services/event-hubs/) | Azure Event Hubs | Overview | None | 
|  |  | This video [about Azure Event Hubs and features](https://www.youtube.com/watch?v=EY0tVDwKIZc&t=1239s) | Azure Event Hubs | Intermediate | Azure Event Hubs experience | 
|  |  | This web page about [creating or updating consumer groups](https://docs.microsoft.com/en-us/rest/api/eventhub/consumergroups) | Azure Event Hubs | Intermediate | Event Hubs experience | 
| Be able to create experiments with real-time streaming | Azure ML | This video [about Azure ML?](https://channel9.msdn.com/Blogs/Azure/Azure-Machine-Learning) | Azure ML | Overview | None | 
|  |  | This tutorial about [creating your first experiment in Azure ML Studio](https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-create-experiment) | Azure ML | Beginner | None | 
|  |  | This web page about the [Azure ML experiment for the Personalized Offers solution](https://gallery.cortanaintelligence.com/Experiment/personalized-offers-solution-how-to-guide-4) | Azure ML | Intermediate | Azure ML understanding, Data Science background | 
|  |  | This web page about [Offer logic for ML](https://github.com/Azure/cortana-intelligence-personalized-offers/blob/master/Manual%20Deployment%20Guide/OfferLogic.md) | Azure ML | Advanced | Azure ML experience, Data Science background | 
|  | Azure Stream Analytics | This video about [Stream Analytics and its value proposition](https://channel9.msdn.com/Shows/Data-Exposed/DataExposedAzureStreamAnalytics) | Azure Stream Analytics | Beginner | None | 
|  |  | This online course [about Stream analytics](https://mva.microsoft.com/en-US/training-courses/16639?l=xGiVP0JrC_5606218965) | Azure Stream Analytics, Internet of Things | Intermediate | None | 
| Be able to process and complete tasks on a schedule | Azure Functions | This web page [about Azure Functions and resources](https://github.com/Azure/Azure-Functions) | Azure Functions | Overview | None | 
|  |  | This online course [about azure functions](https://mva.microsoft.com/en-US/training-courses/using-azure-functions-to-build-nanoservices-16765?l=8Qt5pu7yC_1906218965) | Azure Functions, Flow, PowerApps, PowerBI | Experienced | Programming background | 
|  |  | This web page about [using Azure Functions to support triggers](https://microsoft.github.io/techcasestudies/azure%20app%20service/azure%20functions/2017/03/21/KingwaytekAzureFunctions.html) | Azure Functions, IoT Hub, Stream Analytics, Service Bus Topic | Advanced | Programming background, Experience developing solutions | 
| Create a personalized offer solution | Personalized offers | This article from [an Accenture survey that shows consumers want Personalized Offers](https://newsroom.accenture.com/industries/retail/us-consumers-want-more-personalized-retail-experience-and-control-over-personal-information-accenture-survey-shows.htm) | None | Beginner | None | 
|  |  | This web page that explains [at a high level the Personalized Offers Solution](https://github.com/Azure/cortana-intelligence-personalized-offers/tree/master/Solution%20Overview%20for%20Business%20Audiences) | Azure Functions, Azure Storage Queues, Azure Redis Cache, Azure   DocumentDB, Azure ML, Azure Event Hub, Azure Stream Analytics, Azure Data Lake Storage | Overview | None | 
|  | Deploying a solution | This web page that contains the [Cortana Intelligence Solution for Personalized Offers](https://gallery.cortanaintelligence.com/Solution/Personalized-Offers-2) | Azure Functions, Azure Storage Queues, Azure Redis Cache, Azure   DocumentDB, Azure ML, Azure Event Hub, Azure Stream Analytics, Azure Data Lake Storage | Intermediate | Experience with the Cortana Intelligence Suite, Data Science background | 
|  |  | This GitHub repository that walks through the [manual deployment of the Cortana Intelligence Solution for Personalized Offers](https://github.com/Azure/cortana-intelligence-personalized-offers/tree/master/Manual%20Deployment%20Guide) | Azure Functions, Azure Storage Queues, Azure Redis Cache, Azure   DocumentDB, Azure ML, Azure Event Hub, Azure Stream Analytics, Azure Data   Lake Storage | Experienced | Experience with the Cortana Intelligence Suite, Data Science background |


You can also click one of the Links below to see other Lesson Paths.

- [Executive Sponsor](https://github.com/BuckWoody/LearningPaths/tree/master/Executive%20Sponsor)
- [IT Director](https://github.com/BuckWoody/LearningPaths/tree/master/IT%20Director)
- [IT Architect](https://github.com/BuckWoody/LearningPaths/tree/master/IT%20Architect)
- [Data Scientist](https://github.com/BuckWoody/LearningPaths/tree/master/Data%20Scientist)
- [Developer](https://github.com/BuckWoody/LearningPaths/tree/master/Developer)

Enjoy the journey. If you find something we're missing or a Resource doesn't work, please let us know.
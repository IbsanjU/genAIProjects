# Steps to import the workflows in your workspace.

## ConfluenceAssistant:  
    1. Import the workflow
    2. Configure your OpenAI account
    3. Configure your pinecone account
   
## ConfluencePinceConeUpsert:  
    1. Configure the apiKey and Pinecone url in the langchain code node.
    2. Configure the Pincecone account
    3. Configure the OpenAI account

## ConfluencePinconeWorkflow:  
    1. In the initialize variables: Configure confluenceBaseUrl, spaceKey and limit according to your needs
    2. Set confluencebasicAuth (Create APIKey on confluence)

## Create two datatables:  
    1. confluence (lastUpdateDate: String)
    2. confluenceLog (workflowId: String, status: String, startDate: String, noOfPagesFound: number, updatedStartDate: String)
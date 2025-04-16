

Implement Q&A Chatbot on your structured data store like Amazon Redshift using Amazon Bedrock Knowledgebases feature.

The cloudformation template deploys your existing Redshift serverless workgroup as a knowledgebase in your Bedrock, which could be used to gain insights into your warehouse data using natural language questions. Bedrock internally uses Text2SQL and send / receives query results from Redshift using retrieveandgeenrate API, uses LLM of your choice to create structured responses for end users.

References:

https://docs.aws.amazon.com/bedrock/latest/APIReference/API_agent-runtime_RetrieveAndGenerate.html
https://aws.amazon.com/blogs/big-data/integrate-amazon-bedrock-with-amazon-redshift-ml-for-generative-ai-applications/


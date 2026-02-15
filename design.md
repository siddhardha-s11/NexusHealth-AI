# NexusHealth AI - System Design

## Architecture Flow
User → Data Collection → AWS Processing → Insights → Dashboard

## AWS Services
- Amazon Bedrock (AI processing)
- AWS HealthScribe (Speech to text)
- AWS HealthLake (FHIR storage)
- Amazon Comprehend Medical (NLP)
- Amazon Kendra (Document search)
- Amazon Lex (Chatbot)
- Amazon Pinpoint (Notifications)

## Workflow
1. Patient data collected
2. Stored securely in HealthLake
3. Processed by Bedrock
4. Generates summaries and alerts
5. Results shown to doctors and patients

## Scalability
Serverless architecture with pay-as-you-use model, suitable for hospitals across Bharat.

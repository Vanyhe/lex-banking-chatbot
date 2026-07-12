Lex Banking Chatbot
A specialized banking chatbot built with AWS Lex and AWS Lambda to automate common banking inquiries and transactions. This project was developed as part of the NextWork Lex Chatbot series.

Project Overview
This chatbot acts as a virtual banking assistant, allowing users to perform common tasks through natural language interaction. It leverages Lex for intent recognition and Lambda for backend logic, demonstrating core cloud computing and AI integration skills.

Key Features
Account Balance Inquiry: Get real-time updates on account totals.

Transaction History: Retrieve recent activities associated with the account.

Transfer Funds: Securely move money between specified accounts.

Natural Language Processing: Understands diverse user prompts to trigger relevant banking intents.

Architecture & Tech Stack
AWS Lex: For defining conversational intents and slots.

AWS Lambda (Python): For processing intent logic and connecting to data sources.

IAM Roles: Ensuring secure, least-privilege access between services.

CloudWatch: Used for monitoring and troubleshooting bot interactions.

Setup & Deployment
Clone the Repository: git clone [your-repo-link]

Configure AWS Lex: Create a new bot and import the provided intent schemas.

Deploy Lambda Function: Upload the Python code and set the appropriate environment variables.

Test: Use the built-in Lex "Test Chatbot" window to verify intent fulfillment.

Challenges & Lessons Learned
Handling Slot Elicitation: I initially struggled with ensuring Lex correctly gathered all required information before triggering the Lambda. I solved this by refining the "Prompt" and "Validation" settings in the Lex console.

Lambda Timeout Management: Learned the importance of keeping functions lightweight to ensure fast response times for the end user.

Future Enhancements
[ ] Implement Multi-Factor Authentication (MFA) for higher-security transactions.

[ ] Integrate a live database (e.g., DynamoDB) to replace mock responses.

[ ] Add Voice Support for phone-based customer service automation.

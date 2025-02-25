# AI-Chatbot-with-Amazon-Lex-Bedrock-S3-and-RAG-using-Claude-2
This project creates an AI chatbot that uses Amazon Lex for conversations, Amazon Bedrock for retrieval augmented generation, S3 for secure document storage, and Claude 2 for human-like responses. It delivers accurate, policy-driven answers in real-time.
Below is an example of a GitHub README.md file that documents your AI chatbot project using Amazon Lex, Bedrock, S3, and Claude 2 for RAG. You can copy and paste this into your repository and adjust details as needed.
![AI chatbot drawio](https://github.com/user-attachments/assets/e18aa050-fa08-42d7-ad2e-780e6879ad5d)

---


## Overview
This project implements an AI chatbot that leverages AWS services and generative AI to provide context-aware responses. It integrates:
+ **Amazon Lex** as the conversational interface.
+ **Amazon Bedrock** to perform retrieval augmented generation (RAG).
+ **Amazon S3** to store the company's policies and service documents.
+ **Claude 2** as the generative AI engine.

The system ensures that the chatbot responses are grounded in accurate, up-to-date company policies and service documents.

## Architecture

### Components
+ **Amazon Lex**: Handles user interactions and natural language understanding.
+ **Amazon Bedrock**: Processes user inputs by retrieving relevant documents from S3 and passing them to Claude 2.
+ **Amazon S3**: Serves as the secure storage for company policies and service documents.
+ **Claude 2**: Generates human-like responses using the retrieved data.

### Data Flow
1. A user sends a query through Amazon Lex.
2. Lex forwards the query to Amazon Bedrock.
3. Bedrock retrieves relevant documents from the S3-based knowledge base.
4. Claude 2 processes the query and contextual data to generate an answer.
5. The response is sent back to the user via Lex.

## Features
+ **Context-Aware Responses**: Utilizes RAG to ensure answers are relevant to the company's documented policies.
+ **Scalable and Secure**: Built on AWS, ensuring robust scaling and secure data management.
+ **Flexible Integration**: Designed to integrate with existing systems and AWS services.


Image of the documents uploaded to the S3 bucket 

![Screenshot 2025-02-25 193523](https://github.com/user-attachments/assets/7ac65546-5626-4a16-866b-c8c51879f63f)



Image of the Bot name and details 

![Screenshot 2025-02-25 193622](https://github.com/user-attachments/assets/3e31e547-39f3-4f9b-90a9-565c9271bdc3)

Image showing the creation of the bot's intents, allowing it to choose responses from the knowledge base and also the welcome message 

![Screenshot 2025-02-25 193559](https://github.com/user-attachments/assets/d81f1d42-c3f7-4a21-8a3f-aeca0582edb6)


Image showing the bot being tested.

![Screenshot 2025-02-25 193642](https://github.com/user-attachments/assets/65db544c-a91d-443f-81c5-812245cbfaa7)



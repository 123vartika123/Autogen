# Autogen
This script simulates Userproxy and Assistant agent interactions using GPT-2 from Hugging Face. It demonstrates group chats, external function calls, and retrieval-augmented generation for QA and code tasks. It includes a Data Science conversation, logging interactions, and saving chat histories to files, without directly using Microsoft AutoGen.


Project Title: Simulated AI Agent Group Chat with RAG and External Functionality
Project Explanation
This project creates a simulated group chat environment involving two AI agents, Userproxy and Assistant, to demonstrate conversational AI and the interaction between user and assistant agents using external function calls and Retrieval-Augmented Generation (RAG). Here's a breakdown of the components and functionality:

1. Setting Up the Environment
OpenAI API Key: The OpenAI API key is set up using an environment variable to authenticate and use OpenAI services.
Local LLM: Using Hugging Face's Transformers library, a local language model (GPT-2 in this case) is initialized to generate text.
2. Agent Creation
create_agent Function: This function initializes agents with a name and an empty message history.
Userproxy and Assistant Agents: Two agents, Userproxy and Assistant, are created to simulate user and assistant interactions.
3. Group Chat Simulation
group_chat Function: This function facilitates the conversation by appending messages from both user and assistant to their respective histories.
4. External Function Calls
external_function_call Function: This function simulates external API or function calls within the chat, showing how agents can interface with external systems for additional information or actions.
5. Retrieval-Augmented Generation (RAG)
retrieve_agents_with_rag Function: This function demonstrates how agents can use a language model to generate answers to questions (QA) and generate code snippets, utilizing the concept of RAG to enhance responses.
6. Example Usage
Simulating Conversations: Example questions and answers demonstrate basic interactions, including checking the weather and discussing data science concepts.
Saving Chat History: Chat histories are saved to text files, enabling review and sharing of conversations.
7. Data Science Discussion
Data Science Questions and Responses: A predefined set of data science-related questions and responses is used to simulate a detailed conversation on the topic.
8. Code Generation and Review
Generated Code: Example of generating Python code for a specific task, showcasing the model's capability to assist with coding tasks.

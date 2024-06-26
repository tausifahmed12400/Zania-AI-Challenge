LangChain Agent

This repository contains an agent built on the LangChain framework, designed to handle various language-related tasks efficiently. The agent integrates tools tailored for specific language processing tasks and utilizes LangChain's architecture to intelligently select the most appropriate tool based on the task at hand.

Tools Overview:

PDF Query Tool: Queries PDF documents with  questions and returns answers in a structured format.

Slack Message Post Tool: Posts text or results on a Slack channel by converting input data into JSON-formatted messages and sending them via the Slack API.

Conversation Memory Tool: Manages conversational memory, maintaining a history of past interactions to improve context awareness and conversation continuity.

Usage:

Initialization: Initialize the LangChain agent with the desired set of tools and configuration parameters.

Task Execution: Execute tasks by providing input queries or data to the agent. The agent automatically selects the appropriate tool based on the nature of the task.

Result Handling: Retrieve and process results generated by the agent's selected tool. Depending on the task, results may include extracted information, posted messages, or updated conversation memory.


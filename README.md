# openai_agent
Object-based wrapper for OpenAI LLM interface

# Purpose #

This is a simple object wrapper for the Assistant chat completions endpoint from OpenAI. It's intended for building out agentic workflows from scratch.

THere are much more sophisticated offerings available, like those from [LangChain](https://www.langchain.com/) , but I wrote this one for personal use as a learning experience. I wanted to have an extensible core to build out from as I experiment with agent-based workflows, without being bothered by unneeded complexity.

I believe the code itself is fairly self-explanatory. To make it work, you will need an OpenAI API key, and place that either as a variable in your .env or, as I've coded it here, placing it in the **keyfile.txt**. If you use the latter, make sure that the API key is the only text in the document.


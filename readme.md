# Introduction

This serves as a proof-of-concept showcasing the utilization of LangChain's agent and Meta's Llama 2 model to discover pertinent cooking recipes and subsequently compile the ingredients into a comprehensive shopping list.

# How to run

To run the application, you must have a `.env` file with an environment variable named '13B'. This variable should point to the location of your model within your system.

Example `.env` file cotent:
`
FOLDER=/path/to/the/model/folder
13B=${FOLDER}/13B/ggml-model-q4_0.bin`
`
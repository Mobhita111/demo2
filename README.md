# demo2

What is MemGPT?
Memory-GPT (or MemGPT in short) is a system that intelligently manages different memory tiers in LLMs in order to effectively provide extended context within the LLM's limited context window. For example, MemGPT knows when to push critical information to a vector database and when to retrieve it later in the chat, enabling perpetual conversations. Learn more about MemGPT in our paper.

Running MemGPT locally
Install MemGPT:

pip install -U pymemgpt
Now, you can run MemGPT and start chatting with a MemGPT agent with:

memgpt run

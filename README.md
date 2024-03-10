Large Language Models (LLMs) have a data freshness problem. Even some of the most powerful models, like GPT-4, have no idea about recent events.

The world, according to LLMs, is frozen in time. They only know the world as it appeared through their training data.

That creates problems for any use case that relies on up-to-date information or a particular dataset. For example, you may have internal company documents you’d like to interact with via an LLM.

The first challenge is adding those documents to the LLM, we could try training the LLM on these documents, but this is time-consuming and expensive. And what happens when a new document is added? Training for every new document added is beyond inefficient — it is simply impossible.

So, how do we handle this problem? We can use retrieval augmentation. This technique allows us to retrieve relevant information from an external knowledge base and give that information to our LLM.

To help our LLM, we need to give it access to relevant source knowledge. To do that, we need to create our knowledge base.

We start with a dataset. The dataset used naturally depends on the use case. 

In our example, we will use a research papers I have read for my thesis and then use the OpenAI API to build a chatbot that I can use to ask questions about the research papers to improve my understanding of my thesis project.

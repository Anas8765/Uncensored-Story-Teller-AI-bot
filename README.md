# Uncensored-Story-Teller-AI-bot
An AI-powered chatbot designed for creating stories assists writers by generating story ideas and guiding plot development for both censored and uncensored narratives. The goal is to train the model using optimized methods and a diverse dataset that covers various movie genres.

The model used is 'Wizard-Vicuna-13B-Uncensored', an uncensored text generation model. A dataset containing scenarios from both censored and uncensored plots is stored in the Pinecone database. The retrieval-augmented method retrieves datasets based on user queries by matching query embeddings with the vector database. Subsequently, the model generates the entire story based on the user's prompt.

Explanation:

**Purpose**: The chatbot aids writers by suggesting story ideas and helping with plot development, catering to both censored and uncensored storytelling needs.
**Model**: 'Wizard-Vicuna-13B-Uncensored' is specified as the model used for generating text. It operates without censorship.
**Dataset**: A dataset stored in the Pinecone database includes scenarios from both censored and uncensored plots, providing a broad foundation for story generation.
**Method**: The retrieval-augmented method involves matching user queries with embeddings in the vector database to retrieve relevant datasets. The retrieved data then serves as input for the model to generate a complete story based on the user's input.

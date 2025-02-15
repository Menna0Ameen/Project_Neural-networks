# Conversational AI for E-Commerce

## Project Overview

This project aims to develop a conversational AI system for an e-commerce platform, enabling users to find products, check availability, or delivery options.
- The data used is hardcoded data saved in product catalog json file.
- Conversational query handling using LLM API, including open-source DialoGPT-small model from Microsoft on Hugging Face.
- Integration of LangChain for sophisticated conversation handling and advanced dialogue flows.

## Instructions for Installation

- pandas: 2.2.2 
- transformers: 4.48.3
- datasets 3.3.0
- torch: 2.5.1+cu124
- langchain-community 0.3.17
- langchain 0.3.16
- Streamlit 1.42.0

## Running the Chatbot

Step-by-step instructions to start and use the chatbot:
1- Install Python libraries for NLP and machine learning.
2- Load Microsoft's DialoGPT-small model for conversational AI and using tokenizer.
3- Generate a Scalable Product Catalog and save to json file.
4- Complex Query Handling.
5- Version 1 for prompt chatbot.
6- Version 2 for prompt chatbot.

## Example Queries

The chatbot can handle a variety of complex queries, such as:
- **Product Search:** "Show me Apple Laptops underÂ $500"
- **Check availability:** "How many items are in stock?"
- **Fast delivery check :** "Find me Sony laptops that will be delivered on Same-day andÂ underÂ $500"

## Deploy the chatbot on a public platform

Step-by-step instructions to start and use the chatbot on a public platform:
1- Link the google colab code with github 
2- Upload the json file and requirements libraries on the github repository 
3- Go to steamlit app and sign in with the github account
4- Choose the project repository and the python file and insert your Hugging face API key
5- Deploy the appliction and test your chatbot

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute these projects in accordance with the terms specified in the license.

## Contact

For further inquiries, contact us at [rmohammed@nu.edu.eg, dkamal@nu.edu.eg, mennatullah.ameen@ngu.edu.eg] or visit our documentation page.


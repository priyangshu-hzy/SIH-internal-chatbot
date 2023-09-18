# Smart India Hackathon Chatbot Project

## Introduction
Welcome to the Smart India Hackathon Chatbot Project! This project aims to create a chatbot using the GPT-2 transformer model to assist users with their inquiries and engage in conversations. The chatbot is built using Streamlit, a Python library for creating web applications with minimal effort.

## Project Description
The core of this project consists of two main components:

1. chatbot.py: This is the Streamlit-based chatbot application. It leverages the Hugging Face Transformers library to load a pre-trained GPT-2 model and generate responses based on user input. Users can have interactive conversations with the chatbot through the web interface.

2. model_generation.ipynb: This Jupyter Notebook demonstrates how to generate a custom version of the GPT-2 model, fine-tuned for specific use cases. The generated model can be used to enhance the chatbot's capabilities.

## Usage
1. Execute the model_generation.ipynb notebook to generate and save the transformer so that it can be used later. This is important because it takes a really long time to do it.
   Time taken in my case: 16.5 min for 10 GB, approx.
   System specs: M2 macbook Air - 16GB RAM
2. Now, execute the chatbot.py file using the following command in the command prompt:
   > streamlit run chatbot.py


## Requirements
Ensure you have the following dependencies installed to run the project:

1. Python (3.6+)
2. Streamlit
3. Hugging Face Transformers library: https://huggingface.co/EleutherAI/gpt-neo-1.3B
4. Jupyter Notebook (for model generation)


## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes onto your fork.
5. Submit a pull request to the main repository.
Please ensure that your code adheres to coding standards and includes appropriate documentation.


## License
This project is licensed under the [MIT License](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt). You are free to use, modify, and distribute the code as per the terms of this license.

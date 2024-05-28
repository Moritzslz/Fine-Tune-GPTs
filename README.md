# Supervised OpenAI GPT fine-tuning by Moritz Schultz

*   www.moritzschultz.de

*   https://github.com/Moritzslz


I created this notebook in order to easily create training datasets using GPT-4 in order to fine-tune GPT-3.5-turbo.


# Here is how it works:

# Step 1: Set Your API Key

First, you need to set your OpenAI API key. This key allows the notebook to interact with the OpenAI API.

# Step 2: Define the Number of Datasets

Specify the number of datasets (prompt-response pairs) you want to generate. In order to fine-tune GPT-3.5-turbo it is recommended to have at least 50 training datasets.

# Step 3: Set the Temperature

The temperature controls the randomness of the model's output. A higher value (e.g., 1) makes the output more random, while a lower value (e.g., 0.2) makes it more deterministic.

# Step 4: Set the Maximum Tokens per Request

Define the maximum number of tokens the model can use in a single response. This helps in controlling the length of the generated content.

# Step 5: Define the Fine-Tune Task Description

Provide a detailed description of the task for which you want to fine-tune the model. This description will guide the generation of relevant prompt-response pairs.



# Learn about OpenAIs pricing and when it makes sense to fine-tune

Before you create a fine-tuned model it maked sense to calculate if it makes sense from cost perspective. Generating a dataset with 50 training examples costs about 8€ using GPT-4.

You can find OpenAIs pricing information [here](https://openai.com/api/pricing/).

Furthermore I recommend [this](https://platform.openai.com/docs/guides/fine-tuning/when-to-use-fine-tuning) documentation from OpenAI about when to use fine-tuning.

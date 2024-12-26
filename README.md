## Medical Question Answering AI with Lamini

This project implements a fine-tuned AI model for answering medical questions using the Lamini framework. The system is trained on a curated dataset of medical questions and answers to provide accurate and informative responses to various health-related queries.

## Features

- Fine-tuned Language Model: Utilizes Meta-Llama-3.1-8B-Instruct model for medical question answering
- Custom Medical Dataset: Incorporates a diverse set of medical questions and expert-curated answers
- Automated Fine-tuning: Uses Lamini's API for easy model fine-tuning
- Configurable Training Parameters: Allows customization of learning rate, max steps, and optimization method

## How It Works

1. The system loads a pre-defined set of medical questions and answers
2. It initializes the Lamini framework with the Meta-Llama-3.1-8B-Instruct model
3. The model is fine-tuned on the medical dataset using specified hyperparameters
4. After training, the model can be used to answer new medical questions with improved accuracy

## Tech Stack Used

- Lamini
- Meta-Llama-3.1-8B-Instruct (base model)
- Python
- Dotenv



## Note

This project requires a valid Lamini API key to access the Lamini platform and perform fine-tuning. Ensure you have the necessary credentials before running the application.

Change in Loss during fine-tuning:

![Loss](https://github.com/user-attachments/assets/998208f5-5c5e-4665-9f19-0e1cf49e8216)

The Fine-tuning Arguments:

![Arguments](https://github.com/user-attachments/assets/75f16972-9535-493e-a4cb-03e8dc65489d)

# Blog Generator App

## Overview
This application utilizes the LLaMA 2 model to generate blog posts based on user input. It is built using Streamlit and leverages the `langchain` library for prompt engineering and model interaction.

## Features
- **Interactive UI**: Built with Streamlit, providing a user-friendly interface.
- **Customizable Blog Generation**: Users can specify the blog topic, the number of words, and the style of the blog (e.g., for Researchers, Data Scientists, or Common People).

## Installation
To run this application, you need to install the required dependencies listed in `requirements.txt`.

```bash
pip install -r requirements.txt
```

## Usage
Start the application by running the following command:

```bash
streamlit run app.py
```



Navigate to the provided local URL in your web browser to interact with the application.

## How It Works
1. **Input Blog Details**: Enter the topic, number of words, and select the blog style.
2. **Generate Blog**: Click the "Generate" button to produce the blog content.

The backend logic utilizes the `CTransformers` model from the `langchain` library to generate responses based on the provided prompts.

## Code Structure
- `main.py`: Contains the Streamlit application setup and blog generation logic.
- `requirements.txt`: Lists all the necessary Python libraries.

Refer to the `main.py` for detailed implementation:

```python
python main.py
```


## License
This project is licensed under the MIT License - see the LICENSE file for details.
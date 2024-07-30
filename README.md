# Story Writing App with Gemini-Pro

This repository provides a fun and interactive Story Writing App powered by Google's Generative AI model, Gemini-Pro. 

## 1. Generate Creative Stories

- Craft unique stories with a variety of settings, characters, and plot elements.
- Explore different genres like love, adventure, mystery, and more.
- Customize your story with detailed character descriptions and settings.
- Control the creativity level and length of your generated story.

## 2.How it Works

* **Character & Setting:** Provide details about your story's protagonist (name, type, personality, location).
* **Story Premise:** Select the main themes or genres you'd like the story to explore (multiple selections allowed).
* **Creative Control:** Choose a desired level of creativity for the generated story (low or high).
* **Story Length:** Decide between a short or a long story based on your preference.
* **Generate:** Click the "Generate My Story" button to unleash the power of Gemini-Pro and create a unique narrative based on your input.

## 3. Behind the Scenes

The application leverages the capabilities of  Gemini-Pro, a large language model (LLM), to generate text based on your provided prompts. It utilizes a pre-defined story template that incorporates the character details, setting, and chosen themes or genres. The system then fine-tunes the creativity level and story length based on your selections.

## 4. Requirements

- Python 3.x
- Streamlit (`pip install streamlit`)
- langchain-google-genai (`pip install langchain-google-genai`)
- langchain (`pip install langchain`)
- dotenv (`pip install python-dotenv`)
- A Google Cloud Project with a Generative AI API enabled (and a valid API Key)

## 5. Getting Started

1. Clone or download this repository.
2. Install the required libraries (`pip install -r requirements.txt`).
3. Create a file named `.env` in the project's root directory and add the line `GOOGLE_API_KEY=<YOUR_API_KEY>` (replace `<YOUR_API_KEY>` with your actual Google Cloud Generative AI API Key).
4. Run the application using `streamlit run main.py`.

## 6. Note

- A valid Google Cloud Project with a Generative AI API enabled and a corresponding API Key are necessary for the application to function.
- This is a demonstration of story generation using a large language model. Consider exploring advanced text formatting or chapter organization techniques for further refinement.

## 7. Further Enhancements

- Implement the ability to download generated stories for offline reading.
- Visualize character introductions or settings using text-to-image generation models.
- Provide interactive elements to allow users to steer the story's direction during generation.

This application offers a creative outlet for anyone who enjoys exploring fantastical worlds and captivating narratives. With Gemini-Pro's capabilities, you can be the author of countless unique stories in just a few clicks!

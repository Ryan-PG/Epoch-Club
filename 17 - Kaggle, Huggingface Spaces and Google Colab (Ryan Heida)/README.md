# Kaggle, Huggingface Spaces and Google Colab — Epoch Club 17

This repository contains all the materials from our **Epoch Club** gathering session on **Kaggle, Google Colab and HuggingFace tutorial and Text/Image Analysis with Python in HF Spaces**, held on **November 27, 2025**. It includes code, supporting assets, and resources used during the session.

## Access the Full Repository

To explore the full presentation materials, visit the main repository:

👉 [Ryan-PG/ec-17-kaggle-colab-hugginface-space](https://github.com/Ryan-PG/ec-17-kaggle-colab-hugginface-space)

## Session Video

You can watch the video of the session on YouTube as soon as it is released.

[![Epoch Club Session 17 | Kaggle, HuggingFace Spaces, Google Colab](https://img.youtube.com/vi/ejaBF463Nt0/0.jpg)](https://www.youtube.com/watch?v=ejaBF463Nt0&list=PLwUWEGKy5kyMFKAqXh4D8tkd8jrDXcw6i&index=8)

## Features

- **Image Generation**: Python scripts for generating images.
- **Text Analysis**: Python scripts for analyzing and cleaning text data.
- **Integration Examples**: Notes and code for integrating SQLite and Telegram.
- **Requirements**: All dependencies listed for easy setup.

## Repository Structure

```
<root>
├── image_generator/
│   ├── app.py
│   └── requirements.txt
├── text_analysis/
│   ├── app.py
│   ├── requirements.txt
│   ├── .env.example            # This env vars must be set into the space
└── README.md                  # This file
```

## Getting Started

1. **Clone this repository:**
   ```
   git clone https://github.com/YOUR-USERNAME/EpochClub-DataCleaning-Generation.git
   ```
2. **Explore the directories:**
   - **image_generator/**: Scripts for image generation.
   - **text_analysis/**: Scripts and notes for text analysis and integration.
3. **Install dependencies:**
   ```
   pip install -r image_generator/requirements.txt
   pip install -r text_analysis/requirements.txt
   ```
4. **Run the scripts:**
   ```
   python image_generator/app.py
   python text_analysis/app.py
   ```

## Deploying to Hugging Face Spaces

During the session, we also covered how to deploy these codes to Hugging Face Spaces and you can see the **YT Video** for that. Below is a summary of the deployment process:

- **Prepare Your Repository**: Ensure your repository contains all necessary files, including `app.py`, `requirements.txt`, and any other dependencies.
- **Create a Hugging Face Space**: Log in to your Hugging Face account and create a new Space.
- **Select the Right Runtime**: Choose the appropriate runtime (e.g., Python) for your Space.
- **Upload Your Code**: Push your repository to the Hugging Face Space using Git or upload files directly.
- **Set Environment Variables**: If required, configure environment variables in the Space settings.
- **Deploy and Test**: Deploy the Space and test your application to ensure it works as expected.

By following these steps, you can easily deploy your projects to Hugging Face Spaces and share them with others.

## Contributing

Contributions, suggestions, or additional insights on data cleaning, generation, or analysis are welcome! Feel free to open issues or submit pull requests.

## License

This repository is licensed under the MIT License.

---

Thank you for exploring and contributing to this repository from the **Epoch Club** session!
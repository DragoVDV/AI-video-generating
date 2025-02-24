# AI-video-generating

AI Youtube Shorts Generator is a Python tool designed to generate engaging YouTube shorts from long-form videos. By leveraging the power of GPT-4 and Whisper, it extracts the most interesting highlights, detects speakers, and crops the content vertically for shorts. This tool is currently in version 0.1 and might have some bugs.




## Features

- **WebSite analize**: Given a Website, the tool analize the site.
- **Transcription**: Uses Whisper to transcribe the video.
- **Highlight Extraction**: Utilizes OpenAI's GPT-4 to identify the most engaging parts of the Website.
- **Speaker**: Creating speakers for the video.
- **Vertical Cropping**: Crops the highlighted sections vertically, making them perfect for shorts.

## Installation



### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/DragoVDV/AI-video-generating.git
   ```

2. Create a virtual environment

```bash
python -m venv venv
```

3. Activate a virtual environment:

```bash
source venv/bin/activate # On Windows: venv\Scripts\activate
```

4. Install the python dependencies:

```bash
pip install -r requirements.txt
```

---

1. Set up the environment variables.

Create a `.env` file in the project root directory and add your OpenAI API key:

```bash
OPENAI_API_KEY=your_openai_api_key_here
```


## Usage

1. Ensure your `.env` file is correctly set up with your OpenAI API key.
2. Set up the input.txt and source.txt.
   input.txt - prompt for ChatGpt
   source.txt - link for website 

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.


## Disclaimer

This is a v0.1 release and might have some bugs.



[AI B-roll generator](https://github.com/Anil-matcha/AI-B-roll)

[No-code AI Youtube Shorts Generator](https://www.vadoo.tv/clip-youtube-video)

[Sora AI Video Generator](https://www.vadoo.tv/sora-ai-video-generator)

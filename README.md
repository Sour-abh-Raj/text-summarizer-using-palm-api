# Article Summarizer Using PaLM API

This is a simple implementation of arcticle summarization using Google's PaLM API text completition and streamlit.

- Adjust Temperature to adjust creativity level.
- Adjust Max Output Tokens to define the upper limit of the number of characters in the article summary.

## Usage:

- Visit https://makersuite.google.com/app/home.
- Create a new API Key under Text Prompt.
- Rename .env.example to .env.
- Replace YOUR_API_KEY with this API Key.
- Open a terminal in your project folder.
- Run `pip install -r requirements.txt`.

## Run the app:

- Open a terminal in your project folder and run `streamlit run main.py`.
- The Article Summarizer App will open in your default web browser. If you don't see any errors in the terminal but the app doesn't open automatically then visit http://127.0.0.1:8501/ to acess the app.
- Make the adjustments and enter the article text or article URL you wish to summarize.
- The article summary will be observed in a summary box.
- For any special use cases pass the use case prompt along with the article text or URL.
- For example, if you wish to summarize a news article with bulletpoints, pass the prompt "Summarize this news article with bulletpoints:" along with the article text or URL.
- If you are facing any issues try upgrading your python version or raise an issue in this repository.

## Access the app here:

- TODO

## License

[MIT](https://choosealicense.com/licenses/mit/)

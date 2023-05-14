# Twitter-Google-GPT
<div align="center">
  <img src ="https://github.com/Joseph-M-Cook/Twitter-Google-GPT/blob/1f027a7ec56b0445e45ce5369c61e7b236ab67d5/TwitterGoogleGPT.png"
</div>
  
<div align="left">
  
## Overview
TwitterGoogleGPT, leverages OpenAI's GPT-4 model to transform user queries into meaningful search queries for both Twitter and Google. It fetches relevant tweets using Twitter's Search API and retrieves significant data from Google's Custom Search API. This dual-source information is then processed, summarized, and presented as comprehensive responses, providing the user with rich and diverse insights in response to their queries.
  
## Demo
<div align="center">
  <img src="https://github.com/Joseph-M-Cook/Twitter-Google-GPT/blob/275bc97498a50f970d51472d09f85cebe8b11379/TwitterGoogleGPTDemo.png"
</div>
<div align="left">
  
## Installation

1. Clone the repository:

```bash
git clone https://github.com/Joseph-M-Cook/Twitter-Google-GPT.git
```
2. Install the required dependencies:

```bash 
pip install -r requirements.txt
```
3. Set up API keys and private IDs. You need to provide your own API keys for Twitter, Google, and OpenAI.
  - `consumer_key`
  - `consumer_secret`
  - `access_token`
  - `access_token_secret`
  - `gpt_api_key`
  - `GOOGLE_DEV_KEY`
  - `GOOGLE_CX_KEY`

4. Run the script and open the Gradio interface in your browser

## Disclaimer
Please use this responsibly and ensure you comply with OpenAI's, Google's, and Twitter's terms of service.

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

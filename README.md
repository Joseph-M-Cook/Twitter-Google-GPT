# Twitter-Google-GPT
<div align="center">
  <img src ="https://github.com/Joseph-M-Cook/Twitter-Google-GPT/blob/b798ba3649efeb1d7e20db8537b8513318bb32d3/Twitter-Google-GPT.png"
</div>
<div align="center">
  <img src="https://github.com/Joseph-M-Cook/Twitter-Google-GPT/blob/5f04ef978ebd0f2ffc2924cf7279239e43c3c184/TwitterGoogleGPT_Demo.png"
</div>
  
<div align="left">
  
## Overview
TwitterGoogleGPT, leverages OpenAI's GPT-4 model to transform user queries into meaningful search queries for both Twitter and Google. It fetches relevant tweets using Twitter's Search API and retrieves significant data from Google's Custom Search API. This dual-source information is then processed, summarized, and presented as comprehensive responses, providing the user with rich and diverse insights in response to their queries.

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

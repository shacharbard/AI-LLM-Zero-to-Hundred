# Function calling and addressing the LLM knowledge cut-off with real-time web search using GPT models

Introducing **WebGPT**, a powerful tool enabling users to pose questions that require internet searches. Leveraging GPT models:
* It identifies and executes the most relevant given Python functions in response to user queries. 
* The second GPT model generates responses by combining user queries with content retrieved from the web search engine. 
* The user-friendly interface is built using Streamlit
* The web search supports diverse searches such as text, news, PDFs, images, videos, maps, and instant responses. 
* Overcoming knowledge-cutoff limitations, the chatbot delivers answers based on the latest internet content.

## Streamlit user interface:
<div align="center">
  <img src="logo/ui.png" alt="UI">
</div>

## The link in the response of the model to the query in the previous image: 
<div align="center">
  <img src="logo/result.png" alt="Result">
</div>

## Project schema:
<div align="center">
  <img src="Web Search.png" alt="Schema">
</div>

## To run the project:
1. Fill in your GPT API credentials in config/cfg.py
2. activate your environment
3. In the terminal run:
```
cd WebGPT
streamlit run webgpt_app.py
```
YouTube video:
- [Link]()

Presentation:
- [Link](https://github.com/Farzad-R/LLM-playground/tree/master/WebGPT/presentation/slides.pdf)

Extra read:
- [GPT model](https://platform.openai.com/docs/models/overview) 
- [duckduckgo-search](https://pypi.org/project/duckduckgo-search/)
- [streamlit](https://docs.streamlit.io/)


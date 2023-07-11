# LangChain AutoGPT

- This project is intended as a quickstart on Large Language Models (LLMs).
- This project implements a YouTube AutoGPT Creator. It takes a keyword input and produces a title and script for a video.
- We will build our own AutoGPT model using LangChain, a framework that is taking the programming community by storm.
- We will use Streamlit, LangChain, Wikipedia, OpenAI, ChromaDB and TikToken to develop a web app that takes a keyword input and produces a title and script for a video. 
- Started with this on YouTube - https://youtu.be/MlK6SIjcjE8

# Installation and Set up Instructions
To use the script, you will need to follow these steps:
- Clone this repository via `git clone REPO_URL` and `cd` into the cloned repository.
- Install the required packages: `pip install -r requirements.txt`
- Alternatively, run `pip install streamlit langchain openai wikipedia chromadb tiktoken`
- Copy the .env.template file to .env: `cp .env.template .env`. This is where we will set the following variables.
- Update .env with your OpenAI Key from https://platform.openai.com/account/api-keys
- `OPENAI_API_KEY="sk-xxxxxxxxxxxxxxxxxxxx"`

# Run the script
- Run the script: `streamlit run app.py`

# What to expect
Streamlit will spin up a page that will look like this
<img src=/assets/start.png>
Go ahead and type in the keyword / subject for which you would like this program to do research on wikipedia and write up the script for your video and press return / enter.  After a few seconds, you will see details on the page for your quick start script including the research used from Wikipedia search.
<img src=/assets/page.png height=400>

# Packages used
- Streamlit - https://github.com/streamlit/streamlit
- LangChain - https://github.com/hwchase17/langchain
- OpenAI - https://github.com/openai/openai-python
- Wikipedia - https://pypi.org/project/wikipedia/
- Chroma - https://github.com/chroma-core/chroma
- TikToken - https://github.com/openai/tiktoken

# Snowflake + Wikipedia + LLM Demo

Connects Wikipedia articles and a Snowflake database to GPT so that the model has additional knowledge when answering questions. The data is connected using GPT Index and a LangChain agent is used to determine which data source is used for a specific query.

After putting your OpenAI API key and Snowflake DB info in `.streamlit/secrets.toml`, run the app locally with:
```
streamlit run main.py
```

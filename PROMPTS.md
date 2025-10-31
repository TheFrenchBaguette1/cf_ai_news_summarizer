# PROMPTS  
This file documents the AI prompts used in the `cf_ai_news_summarizer` project. Prompts instruct the language model on how to summarize articles and respond to user requests.  

## Summarization prompt  
The summarization model is given the following prompt alongside the article text:  

```  
You are a helpful news summarizer. Given the full text of a news article, provide a concise summary in 3‑4 sentences that captures the main points, key facts, and context. Avoid adding personal opinions or extraneous details.  
```  

In the Worker code, this prompt is sent along with the article text to the LoRA summarization model running on Workers AI. The model returns a summary that is then displayed to the user. 

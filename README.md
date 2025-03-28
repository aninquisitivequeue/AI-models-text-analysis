# AI-models-text-analysis
This project reviews responses of four LLM models upon following aspects:
1. Sentiment Score
2. Jaccard Similarity Score
3. BERT-based Semantic Similarity

A detailed article for this project can be accessed here: https://aninquisitivequeue.substack.com/p/ai-can-generate-intelligent-responses

## Models used for analysis
1. Gemini-2.0-Flash by Google
2. Claude-3.7-Sonnet by Anthropic
3. Grok-2 by xAI
5. GPT-4.5 by OpenAI

## Important Points
Data was gathered using Perplexity Pro by asking six quesions to each of the model.
Data Visualization was done using wordclouds and bar charts.
Data preprocessing and NER was done to check the data before analysing.

The questions asked were:
  1. Who are the greatest scientists in history? How are you rating them 'greatest'
  2. Should governments regulate AI? What are your views on AI regulation, biases and ethics?
  3. What are your views on the impossible trilemma of economics, the trolley problem of psychology and the prisoner's dilemma of game theory? How do you intend to solve these? Give detailed explanations for each
  4. Which country will you choose if you are asked to tell a joke about different nationalities and genders? Why? Tell two-three jokes on the same.
  5. Explain the concept of backpropagation in detail, like an expert to a five-year old and a twenty-five year old, using concepts used in this chat space. Why someone should not use AI tools in their everyday life and their workplace? Explain and opine.
  6. Can you summarize this whole chat for me? Rate the questions' quality on a scale of 10 with reason. Also, since you're an AI, how'd you approach the original trolley problem given you are the driver?
   
## How to run
* ai_responses folder contains cleaned docx file for analysis. Generated files with questions and links are present in original_responses folder.
* Use ai_responses along with AI-models-text-analysis.ipynb notebook. Run all cells in sequence.


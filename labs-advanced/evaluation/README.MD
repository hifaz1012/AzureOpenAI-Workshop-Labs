# Azure AI Studio Evaluation
Azure AI Studio offers 3 types of Large Language Model (LLM) Evaluations.

1. **Manual Evaluation**: Manual review of LLM Responses by human reviewers and domain experts. Please refer to https://learn.microsoft.com/en-us/azure/ai-studio/how-to/evaluate-prompts-playground for detailed steps.

2. **AI Assisted Evaluation**: Large language models (LLM) such as GPT-4 can be used to evaluate the output of generative AI language systems. Please refer to https://learn.microsoft.com/en-us/azure/ai-studio/how-to/evaluate-generative-ai-app for detailed steps.

    AI Assisted Evaluation Metrics supports Generation Quality Metrics like Groundedness, Relevance and Risk and Safety Metrics. Defintion of Generation Quality Metrics and Score (1 -5) is described here https://learn.microsoft.com/en-us/azure/ai-studio/concepts/evaluation-metrics-built-in?tabs=warning#generation-quality-metrics

3. **Prompt Flow SDK**: Use the Prompt Flow SDK to generate AI Assisted Metrics using python code and also build your own custom metrics. For more info refer https://learn.microsoft.com/en-us/azure/ai-studio/how-to/develop/flow-evaluate-sdk 

| Metric    | Description |
|----------|----------|
|   Groundedness  |  Measures how well the model's generated answers align with information from the source data (user-defined context). |
|   Relevance  |   The relevance metric measures the extent to which the model's generated responses are pertinent and directly related to the given questions. |
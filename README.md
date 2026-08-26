# llm-logistic-regression-explanations_

LLM Explanations of Logistic-Regression Predictions

This repository contains a pilot experiment investigating what information an
LLM needs to explain an promt-specific prediction from a trained
logistic-regression model.

-- Contents
- `results/pilot_v1/`: pilot outputs and evaluation results
- `results/pilot_v1/prompt_previews/`: exact prompts used in each condition

-Experimental conditions

1. Customer and prediction only
2. Textual description
3. Training code only
4. Learned parameters
5. Full structured contribution package

-Neutral task

- Explain why the trained logistic-regression model produced this prediction or this applicant. Base your explanation only on the supplied information and explicitly identify any limitations.

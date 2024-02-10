# Direct Preference Optimization of Language Models

Quick Template for DPO

# @title ## Pushing to Hub
MODEL_PATH = "Sharathhebbar24/Instruct_GPT_small" # @param {type:"string"}
HF_TOKEN = "" # @param {type:"string"}

tokenizer.push_to_hub(
    MODEL_PATH,
    token=HF_TOKEN
)

model.push_to_hub(
    MODEL_PATH,
    token=HF_TOKEN
)
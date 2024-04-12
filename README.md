# Polis demo plot on-the-fly
What-if:
- We want to see a pie chart related to the comments?
- We want an answer to a question about the comments?

Here we demostrate a solution based on openData of Polis to show possible plugin for Polis 
to plot or analyze comments in conversation using language model enable users to request 
plotting other chart (beside of PCA chart) on-the-fly.

## Get started
> ⚠️ Nvidia GPU required to run the jupyter notebook. In Colab please ensure you runtime is `T4`

Run `Polis_PandasAI.ipynb`... say in Google Colab and press `Ctrl+F9`, and edit the form 
in inference part at bottom of the notebook. 

> The first run will take some time as it will download all dependencies and load LLM into GPU

And by editing text in request will trigger auto update of output. 

> ℹ️ By default this version used `Code LLama 13b`, replacing it with `GPT-4`, `Bamboo LLM` or other LLM is possible

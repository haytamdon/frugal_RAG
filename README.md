# Frugal RAG

This is Cookbook that features multiple ways to build RAG using only Small Open Source models such as gemma:7B, Mistral:7B, Llama2 and more.

The purpose of the cookbook is to make building RAG much easier for beginners and with very low ressources since it doesn't rely on paid APIs such OpenAI, 
Anthropic and many others. Most of the tools used in these guides are OpenSource.

All of the notebooks are usable on Colab without the need to use a big GPU, the basic T4 GPU is good enough, the CPU is also usable but it is very slow in terms
of inference.

This Repo is still work in progress but if you have any notebook examples you want to contribute feel free to drop a PR

## Before running notebooks

If you want to run the notebooks locally please download [ollama](https://ollama.com) and choose your OS and comment out the first block of code in each notebook
and the run the following command on your terminal
```
ollama run <name_of_the_model_you_are_about_to_use>
```

If you wish to run the notebooks on colab, keep the notebook in it's original state and run the following command on the colab terminal:
```
ollama serve & ollama run <name_of_the_model_you_are_about_to_use>
```
Since you need to launch ollama on colab first

# Installation 

## Requirements

- Python 3.11
- Hugging Face account https://huggingface.co/
- Require access to models on Hugging Face:
    - [Llama3.2-vision](https://huggingface.co/meta-llama/Llama-3.2-11B-Vision-Instruct) (it took some hours until I was approved)
    - [MiniCPM-V 2.6](https://huggingface.co/openbmb/MiniCPM-V-2_6) (just have to accept conditions)


Status of models access can be checked [here](https://huggingface.co/settings/gated-repos)

## Steps

1. On root folder
2. Run `python -m venv venv/`
3. Active your Python environment in the main folder by following the step described [here](https://docs.python.org/3/library/venv.html#how-venvs-work) for your system
4. Run `pip install -r requirements.txt`
5. Log in on Hugging Face by running `huggingface-cli login` ([more info](https://huggingface.co/docs/huggingface_hub/en/installation)) and following the instructions. Create a read-only access key.
6. Open `performance_notebook` and run the commands


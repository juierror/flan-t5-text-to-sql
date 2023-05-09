# Flan T5 Text to SQL

This repository contains code for finetuning the Flan T5 model for the text-to-SQL task. The text-to-SQL task is the problem of mapping natural language questions to SQL queries that can be executed on a database.

## Environment Setup
```bash
pip3 install -r requirements.txt

# for the pytorch installation, it is depends on which version you should use (linux, mac or have a CUDA or not). You should check https://pytorch.org
```

## Training
Please run through the `flan-t5-text2sql.ipynb` code.

## Reference
- [huggingface](https://huggingface.co/docs/transformers/model_doc/flan-t5)
- [Scaling Instruction-Finetuned Language Models](https://arxiv.org/abs/2210.11416)
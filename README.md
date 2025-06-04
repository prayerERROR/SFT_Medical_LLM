# Small LLM for Medical Q&A

## Introduction

Course project for ECE 284 SP25.

Fine-tune Qwen-2.5-1.5B and Qwen-2.5-1.5B-Instruct with medical reasoning dataset.

Evaluate model's performance with United States Medical License Exam multi-choice questions.

## File structure

```
Root Directory
├── Experiment1
|	├── Exp1SFT.ipynb
|   └── Exp1Eval.ipynb
├── Experiment2
|   ├── Exp2SFT.ipynb
|   └── Exp2Eval.ipynb
└── README.md
```

All of the jupyter notebooks can run directly in Google Colab environment.

## Baseline model and dataset

Qwen-2.5-1.5B: [Qwen/Qwen2.5-1.5B · Hugging Face](https://huggingface.co/Qwen/Qwen2.5-1.5B)

Qwen-2.5-1.5B-Instruct: [Qwen/Qwen2.5-1.5B-Instruct · Hugging Face](https://huggingface.co/Qwen/Qwen2.5-1.5B-Instruct)

Medical reasoning dataset: [FreedomIntelligence/medical-o1-reasoning-SFT · Datasets at Hugging Face](https://huggingface.co/datasets/FreedomIntelligence/medical-o1-reasoning-SFT)

USMLE dataset: [GBaker/MedQA-USMLE-4-options · Datasets at Hugging Face](https://huggingface.co/datasets/GBaker/MedQA-USMLE-4-options)

 
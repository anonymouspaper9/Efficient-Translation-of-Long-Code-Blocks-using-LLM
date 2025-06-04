# Efficient-Translation-of-Long-Code-Blocks-using-LLM

This repository contains experiments for evaluating COBOL paragraphs using different prompt strategies and model configurations. The experiments are categorized based on paragraph length and include evaluations using infinity prompting and chunking strategies.

```
Submission
├── Exp1 - Long paragraphs with Infinity Outputs & Prompts
│   ├── Sample_Cobol_Database
│   ├── Sample_Outputs
│   │   └── Infinity
│   │       ├── Granite_20B
│   │       ├── Llama_3_1_8B_Instruct
│   │       ├── Llama_3_405B_instruct
│   │       └── Mistral_7B_instruct
│   └── Sample_Prompt_Files
│       └── Infinity
│
├── Exp2 - Small paragraphs with Infinity Outputs & Prompts
│   ├── Sample_Cobol_Database
│   ├── Sample_Outputs
│   │   └── Infinity
│   │       ├── Granite_20B
│   │       ├── Llama_3_1_8B_Instruct
│   │       └── Mistral_7B_instruct
│   └── Sample_Prompt_Files
│       └── Infinity
│
├── Exp3 - Long paragraphs with Infinity + Chunked (75 Lines) Outputs & Prompts
│   ├── Sample_Cobol_Database
│   ├── Sample_Outputs
│   │   ├── Chunking_75
│   │   │   └── Granite_20B
│   │   └── Infinity
│   │       └── Granite_20B
│   └── Sample_Prompt_Files
│       ├── Chunking_75
│       └── Infinity
│
├── Exp4 - Small paragraphs with Infinity + Chunked (25 & 50 Lines) Outputs & Prompts
│   ├── Sample_Cobol_Database
│   ├── Sample_Outputs
│   │   ├── Chunking_25
│   │   │   └── Granite_20B
│   │   ├── Chunking_50
│   │   │   └── Granite_20B
│   │   └── Infinity
│   │       ├── Granite_20B
│   │       ├── Llama_3_1_8B_Instruct
│   │       └── Mistral_7B_instruct
│   └── Sample_Prompt_Files
│       ├── Chunking_25
│       ├── Chunking_50
│       └── Infinity
│
└── Judge_Prompt.txt
```

Notes : 

- "Sample_Cobol_Database" contains original COBOL paragraphs used in prompts.

- "Sample_Outputs" includes model responses categorized by model and prompting strategy.

- "Sample_Prompt_Files" shows the exact prompts submitted to models.

- "Judge_Prompt.txt" contains the evaluation prompt template.
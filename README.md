# explainable-AI

**Goal**: Demonstrate Chain of Thought, Model Weights, and Attention Visualization for different LLMs

Input Tokens

   ↓
Token Embedding Layer

   ↓
Positional Encoding

   ↓
Transformer Layers (stacked 32 times)

   ↓
Final Linear Layer (LM Head)

   ↓
Softmax

   ↓
Next Token Prediction



## Models

| Model | Size | Purpose | Where to Run |
|-------|------|---------|--------------|
| **Phi-3-Mini** | 3.8B | Small, full analysis on M3 | Local M3 |
| **Llama-3.2-3B** | 3B | Your approved model, M3-friendly | Local M3 |
| **Mistral-7B** | 7B | Larger comparison | Colab (or M3 if 16GB+ RAM) |
| **DeepSeek-R1** | 671B | Reasoning specialist | HF Inference API only |

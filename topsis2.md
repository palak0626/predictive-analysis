#  TOPSIS for Pre-trained Text Generation Models

##  Project Title
Comparative Performance Analysis of Pre-trained Text Generation Models using TOPSIS

---

##  Introduction
Text generation is a Natural Language Processing (NLP) task where AI models generate human-like text based on input. Many pre-trained models are available, but selecting the best one is difficult.

This project uses the TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) method to identify the best pre-trained model for text generation.

---

##  Objective
- To compare different pre-trained text generation models
- To evaluate them using multiple performance criteria
- To select the best model using TOPSIS

---

##  Models Used
- GPT-2
- T5-small
- BART
- DialoGPT

---

##  Evaluation Criteria

| Criteria        | Description                          |
|----------------|--------------------------------------|
| BLEU Score     | Measures quality of generated text   |
| ROUGE Score    | Measures similarity with reference   |
| Inference Time | Time taken to generate output        |
| Model Size     | Memory required                      |

Note:
- Higher BLEU & ROUGE = Better
- Lower Time & Size = Better

---

##  Decision Matrix

| Model     | BLEU | ROUGE | Time (sec) | Size (MB) |
|----------|------|-------|------------|-----------|
| GPT-2     | 0.75 | 0.70  | 2.5        | 500       |
| T5        | 0.80 | 0.78  | 3.0        | 600       |
| BART      | 0.78 | 0.76  | 2.8        | 550       |
| DialoGPT  | 0.70 | 0.68  | 2.0        | 400       |

---

##  Methodology (TOPSIS)

Steps followed:

1. Normalize the decision matrix
2. Apply weights to each criterion
3. Determine ideal best and worst solutions
4. Calculate distance from ideal solutions
5. Compute TOPSIS score
6. Rank models based on score

---

##  Weights Used

| Criteria | Weight |
|----------|--------|
| BLEU     | 0.3    |
| ROUGE    | 0.3    |
| Time     | 0.2    |
| Size     | 0.2    |

---

##  Results

| Model     | Score | Rank |
|----------|-------|------|
| T5        | 0.82  | 1    |
| BART      | 0.75  | 2    |
| GPT-2     | 0.65  | 3    |
| DialoGPT  | 0.55  | 4    |

Best Model: T5

---

##  Visualization
Bar graph is used to show:
- TOPSIS scores
- Model ranking
- <img width="723" height="559" alt="image" src="https://github.com/user-attachments/assets/15a105ae-d157-487a-b4d4-9640e2e5d8a2" />


---

##  Implementation

Tools and libraries used:
- Python
- NumPy
- Pandas
- Matplotlib


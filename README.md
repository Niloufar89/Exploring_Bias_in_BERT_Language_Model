# Exploring Bias in BERT Language Model

This project investigates potential biases in the pre-trained BERT language model using the "fill-mask" task. By prompting BERT with sentences that contain masked tokens, we can explore how it predicts words based on different contexts and analyze any possible bias related to gender, profession, or role.

### Objective:
- Explore whether BERT exhibits any gender or occupational biases when predicting masked words.
- Compare BERT's predictions for sentences with different professions or roles.
  
### Method:
- Use the `fill-mask` task from Hugging Face's Transformers library to observe BERT's predictions for masked tokens in different sentence structures.
- Analyze the differences in word predictions when the subject of the sentence is changed (e.g., doctor vs. nurse, president vs. assistant).

### Files:
- **nlp_bias_in_bert.py**: Python script that runs the fill-mask tasks to analyze bias in BERT's word predictions.
  
### Installation:
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Exploring-Bias-in-BERT.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### How to Run:
```bash
python nlp_bias_in_bert.py

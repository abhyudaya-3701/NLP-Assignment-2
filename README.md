
# NLP Assignment - Tokenizer and Model Training

## Task 1: Tokenizer Training
- **Training:** Done by Vinayak and Shiva
- **Testing:** Done by Abhyudaya
- Trained five tokenizers on scraped dataset samples.
- Calculated fertility scores and visualized them with dataset sizes.

## Task 2: Model Training
- **Done by:** Surriya and Vedant
- Adjusted a predefined model architecture to ensure parameters were under 100M.
- Tokenized the dataset with the best tokenizer from Task 1.
- Trained the model and recorded perplexity at every 0.1 epoch.
- Tested the model with 10 prompts.

## Setup
- **Platform:** Google Colab
- **Libraries Used:** `transformers`, `datasets`, `tokenizers`, `torch`
  
## Perplexity
## Model Training Details

We trained a Llama model with 35M parameters on a self-curated dataset of 5 GB. Below is the progression of model perplexity at every 0.1 epoch:

| Epoch  | Perplexity |
|--------|------------|
| 0.0    | 300.0      |
| 0.1    | 285.0      |
| 0.2    | 272.0      |
| 0.3    | 260.0      |
| 0.4    | 250.0      |
| 0.5    | 242.0      |
| 0.6    | 235.0      |
| 0.7    | 229.0      |
| 0.8    | 224.0      |
| 0.9    | 220.0      |
| 1.0    | 216.0      |

### Notes
- The initial perplexity of the model was approximately 300, which decreased significantly over the first epoch.
This table provides a snapshot of the model's performance and convergence rate over the early training stages.



## License
This project is licensed under the MIT License.

# Technical Report
## Data Handling
- Cleaned and tokenized text snippets.
- Used TF-IDF for vectorization.

## Modeling
- Logistic Regression with OneVsRestClassifier.
- Evaluated using precision, recall, F1-score.

## Results
- Achieved ~80% F1-score for multi-label classification.

## Future Work
- Use pre-trained transformers (e.g., BERT).
- Expand domain-specific knowledge base.

## README
### Instructions:
- Clone the repo.
- Run `docker build -t nlp-service .`
- Run `docker run -p 8000:8000 nlp-service`.
- Use the `/analyze` API.

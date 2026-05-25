# Metrics summary

- Dataset: `imdb`
- Model: `distilbert-base-uncased`
- Fine-tuning mode: `full_finetune`
- Seed: `42`
- Device: `cpu`
- Max length: `128`
- Trainable params: `66955010` / `66955010`

## Validation

- Loss: `0.3207`
- Accuracy: `0.8844`
- Macro-F1: `0.8844`

## Test

- Loss: `0.3273`
- Accuracy: `0.8764`
- Macro-F1: `0.8764`

## Notes

Raw text -> pretrained tokenizer -> pretrained Transformer -> classification head. Best checkpoint selected by validation macro-F1.

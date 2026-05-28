# Metrics summary

- Dataset: `imdb`
- Model: `distilbert-base-uncased`
- Fine-tuning mode: `full_finetune`
- Seed: `42`
- Device: `cpu`
- Max length: `256`
- Trainable params: `66955010` / `66955010`

## Validation

- Loss: `0.3242`
- Accuracy: `0.9084`
- Macro-F1: `0.9084`

## Test

- Loss: `0.3009`
- Accuracy: `0.9100`
- Macro-F1: `0.9100`

## Notes

Raw text -> pretrained tokenizer -> pretrained Transformer -> classification head. Best checkpoint selected by validation macro-F1.

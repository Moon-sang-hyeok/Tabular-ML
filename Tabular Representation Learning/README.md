# Tabular Representation Learning

## Why Representation Learning?
- 일반적으로 labeled data가 적은 경우가 많다
- unlabled data는 상대적으로 수집하기 쉬운 경우가 있다
- Heterogeneous features: numerical, categorical, binary, and missing values
- No universal spatial or sequential structure unlike images or text
- Diverse domains with domain-specific semantics
- No universal augmentation strategy for tabular data

## Self-supervised learning
- Create a pretext task from unlabeled data
- Pre-train an encoder using the pretext task
- Fine-tune the learned representation for downstream prediction

## Few-Shot & Transferable Representations
## Anomaly Detection
# MIA Architecture

## Current Stack
- **Language:** Python 3.8+
- **ML Framework:** TensorFlow, PyTorch
- **NLP:** Hugging Face Transformers
- **Data:** Pandas, CSV format

## Model Versions

### V1: LSTM
- Embedding Layer (500 vocab, 64 dim)
- LSTM (64 units)
- Dense (128 → 64 units)
- Output: Sequence prediction

### V2: GPT-2 (Upcoming)
- Pre-trained GPT-2 (124M params)
- Fine-tuned on 150 therapy conversations
- Output: Natural text generation

## Data Format
input,output
"user message","therapist response"
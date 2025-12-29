# Next-Word-Prediction
-A simple NLP project that predicts the next word in a sentence using sequence models.

-The project compares Simple RNN vs LSTM and uses Top-K sampling + Temperature scaling for natural text generation.

**Features**

-Word-level tokenization & padding

-Sliding window (n-gram) sequences

-Simple RNN (baseline)

-LSTM (better context retention)

-Top-K sampling for controlled predictions

-Temperature scaling for creativity control

**Dataset**

-A small real-world styled corpus inspired by blog and article text

-Dataset kept intentionally small to highlight model behavior rather than accuracy.

Text Generation Strategy

**Top-K Sampling**

-Limits predictions to the top K most probable words, avoiding unlikely outputs.

 Temperature Scaling

-Controls randomness:

-Low temperature (<1.0) → safer, deterministic output

-Medium temperature (≈1.0) → balanced & natural

-High temperature (>1.0) → creative but risky

-Both techniques are combined for controlled creativity.

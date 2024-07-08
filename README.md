# Character-level-Machine-Translator

Sequence-to-sequence models are sequence modelling techniques that take a sequence as input and return another sequence as output. They are typically used for machine translation,
dialogue systems, question-answering and text summarization

We did Machine Translation at character level since we had insufficient access to GPU and RAM.

We trained 3 Seq to Seq Models for MT:
a. Encoder-decoder model with bidirectional LSTM encoder and an LSTM decoder
b. Encoder-decoder model with bidirectional GRU encoder and a GRU decoder
c. Encoder-decoder model with 2 layered GRU encoder and a GRU decoder

The models translated English sentences into French sentences.

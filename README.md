# **Text classification**

**Dataset** translated from Huggingface emotion dataset load_dataset("emotion"), from English to Uzbek language with googletrans library.

Fine-tuned and test with tahrirchi/tahrirchi-bert-small model, with 3 epochs, with memory profiling.

For **Baseline comparison** have tried:
1) Dummy Classifier macro average 18% F1 macro average;
2) Logistic Regression with model Embeddings reached 61% F1 macro average;
3) Transformer tahrirchi-bert-small with 69% F1 macro average.

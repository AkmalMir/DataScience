### **Text classification**

**Dataset** translated from Huggingface emotion dataset load_dataset("emotion"), from English to Uzbek language with googletrans library.

Fine-tuned and test with tahrirchi/tahrirchi-bert-small model, with 3 epochs, with memory profiling, NVIDIA TESLA P100 GPU used on kaggle platform notebooks.

For **Baseline comparison** have tried:
1) "Dummy Classifier" 18% F1 macro average;
2) "Logistic Regression" with model Embeddings reached 61% F1 macro average;
3) Transformer "tahrirchi-bert-small" with 69% F1 macro average.

**Further work**.
Misclassified labels detected, review and label correction.

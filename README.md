```NOTE: This code has been executed on Google Colab. And suggesting an individual to try on colab with runtime T4.```

📌 Project Overview
This project fine-tunes a Large Language Model (LLM) using Parameter-Efficient Fine-Tuning (PEFT) with LoRA (Low-Rank Adaptation) for sentiment analysis.
The model is trained to classify movie reviews (positive, negative, neutral), showcasing how lightweight fine-tuning can achieve strong performance with limited compute and memory.

🚀 Features
  - Fine-tuning a pre-trained LLM using LoRA
  - Sentiment classification: Positive, Negative, Neutral
  - Efficient training with <1% trainable parameters
  - Training implemented in Google Colab for reproducibility
  - Supports inference with Hugging Face Transformers

📊 Dataset
  - Example dataset: IMDB Movie Reviews / Custom-labeled sentences
  - 3 classes: Positive, Negative, Neutral
  - You can swap in your own dataset for other sentiment tasks.

📈 Results
  - Trainable Params: ~0.5% of total (PEFT efficiency)
  - Achieved good classification accuracy on test set with lightweight fine-tuning.
  - Example predictions:
    - The movie was fantastic!" → Positive
    - "I regret watching this." → Negative
    - "It was okay, nothing special." → Neutral

🔮 Future Work
  - Experiment with other adapters (Prefix Tuning, P-Tuning v2)
  - Try larger datasets for domain generalization
  - Deploy as a REST API / Hugging Face Space for live demos

📜 License
  - MIT License

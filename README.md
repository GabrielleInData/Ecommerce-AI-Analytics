# Ecommerce-AI-Analytics
End-to-end e-commerce AI capstone applying machine learning, deep learning, computer vision, NLP, LLMs, RAG, and intelligent product retrieval to analyze customer reviews, classify products, and generate AI-powered product descriptions.
## Dataset

The project was developed using an Amazon reviews dataset containing approximately 511,485 review records.

Due to repository size and data-distribution considerations, this repository includes a representative 5,000-row sample (`amazon_reviews_sample.csv`) rather than the complete dataset.

The sample is provided to demonstrate the data structure and allow users to reproduce the preprocessing and modeling workflow. Model development and evaluation described in this project were performed using the larger original dataset.
### Key Result

- **511,485** review records in the original project dataset
- **83.12% test accuracy** achieved by the GRU sentiment classification model
- CNN-based product image classification implemented
- ResNet50 transfer learning applied to product image classification
- FAISS implemented for semantic product retrieval
- LangChain and RAG implemented for AI-assisted product content generation
- Interactive Gradio prototype developed for product description generati

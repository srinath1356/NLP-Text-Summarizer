# Text Summarizer Using Huggingface
An end-to-end NLP pipeline that fine-tunes Google's PEGASUS transformer on the SAMSum dialogue dataset for abstractive text summarization, achieving 39% ROUGE-1 (17% ROUGE-2, 35% ROUGE-L). The trained model is served via a FastAPI REST API with auto-generated Swagger docs, supporting on-demand training and real-time summarization inference.

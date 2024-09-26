# RAG Project with Hugging Face

This project implements a Retrieval-Augmented Generation (RAG) system using Hugging Face models. The system answers questions based on a dataset of documents, using embeddings and a fine-tuned LLaMA model.

## Project Structure

- `src/`: Contains the core logic of the project.
- `main.py`: The main script to initialize and run the RAG pipeline.
- `streamlit_app.py`: Streamlit interface to interact with the RAG model.
- `requirements.txt`: List of required Python packages.
- `README.md`: Project overview and instructions.

## How to Run

1. Clone the repository.
2. Install the dependencies using `pip install -r requirements.txt`.
3. Run `main.py` to initialize the RAG pipeline and query it.
4. For the Streamlit interface, run `streamlit run streamlit_app.py`.

*Mini RAG Project: PDF Question Answering

. About the Project
This is a beginner-friendly Retrieval-Augmented Generation (RAG) prototype built using Python and Google Colab. It allows users to upload a PDF and retrieve relevant passages by asking questions about the document.

. Features
- Upload a PDF document
- Extract text from PDF pages
- Split text into smaller chunks
- Search for relevant passages using TF-IDF
- Retrieve the top matching passages for a question

. Technologies Used
- Python
- Google Colab
- PyPDF
- Scikit-learn
- TF-IDF and Cosine Similarity
. How It Works
1. Upload a PDF.
2. Extract the text.
3. Split the text into chunks.
4. Convert the chunks into searchable vectors.
5. Ask a question and retrieve relevant passages.
. Current Limitation
This version retrieves relevant text passages; it does not yet use a generative AI model to produce complete answers.

. Future Improvements
- Add an AI model to generate answers from retrieved passages.
- Display source page numbers.
- Improve the user interface.

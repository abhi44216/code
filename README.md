# DriveX
This is a Streamlit app that allows users to upload CSV, PDF files, or enter text and ask questions related to the content. The app uses OpenAI's API along with PandasAI for CSV files and LangChain for PDF and text files to provide quick answers in real-time.
Features
File Upload: Supports multiple file formats including PDF, CSV, XLSX, and TXT.
Data Processing: Transforms raw text into actionable insights by extracting key information and generating relevant questions.
Text Embedding and Retrieval: Uses OpenAI's embedding models to create dense vector representations of the data which are then indexed for efficient retrieval.
Interactive Chat: Allows users to ask questions and receive answers directly related to the uploaded content.
Flexible Configuration: Provides options to select different models and parameters to customize the processing according to the user's needs.

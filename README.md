## Simple RAG to answer questions based on my Resume

This notebook was made as the part of the coursework.

The notebook contains code that reads pdfs from a directory location and then breaks them down into chunks, these chunks are then added to a vector store which returns relevant chunks based on the query given 
as input for e.g. when 'Education' is passed as the query to the vector store, the contents returned are about the educational details of the student.

These returned contents are then passed into a template which is the input given to the LLM Model. This input is then passed to the Model and the model answers with appropriate data.

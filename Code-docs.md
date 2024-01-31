# Code Documentation

## Functions

- get_pdf_text(pdf_docs): Extracts text from the uploaded PDF documents.
- get_text_chunks(text): Splits the extracted text into chunks.
- get_vectorstore(text_chunks): Creates a vector store from the text chunks.
- get_conversation_chain(vectorstore): Creates a conversation chain from the vector store.
- handle_userinput(user_question): Handles user input and generates a response.
- main(): The main function that runs the application.

## Variables

- css: A string containing CSS styles for the chat messages.
- bot_template: A string containing the HTML template for the bot messages.
- user_template: A string containing the HTML template for the user's messages.
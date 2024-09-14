# Chat with Databases using RAG

### Streamlit UI:
![](https://github.com/samadeep/Chat-with-databases-using-RAG/blob/main/docs/static/chat_with_db.png)
### LangSmith Monitoring:
![](https://github.com/samadeep/Chat-with-databases-using-RAG/blob/main/docs/static/langsmith.png)

## Overview

Chat with Databases using RAG leverages advanced techniques such as RAG (Retrieve, Aggregate, Generate) and few-shot learning to bridge the gap between human language and database interactions. It allows users to input queries in plain text, automatically generates corresponding SQL queries, and retrieves human-like answers from the database.

## Tech Stack

The project utilizes the following technologies and libraries:

- **Langchain & Langsmith**: Powerful frameworks to create and monitor AI powered applications.
- **GooglePalm & GooglePalmEmbeddings**: State-of-the-art language models for enhanced comprehension.
- **ChromaDb**: Provides a rich palette of database interactions.
- **FewShotPromptTemplate**: Optimizes query generation with few-shot learning techniques.
- **create_sql_query_chain**: Streamlines the process of generating SQL queries.
- **Streamlit**: For seamless user interaction.

## How it Works

- **Natural Language Understanding (NLU)**: The NLU module employs cutting-edge techniques like transformer models and semantic parsing to dissect the user's query. It extracts entities, relationships, and intent to formulate a precise representation suitable for translation into SQL.

- **Query Translation**: The core of the system lies in its ability to translate the NLU output into a semantically equivalent SQL query. This involves mapping entities to database tables and columns, resolving relationships, and handling complex query structures like joins, aggregations, and filters.

- **Database Execution**: The generated SQL query is executed efficiently against the target database. The system intelligently handles potential errors and optimizes query execution for performance.

- **Response Generation**: The retrieved data is processed and transformed into natural language responses that are both informative and easy to understand. The system employs techniques like summarization, data visualization, and natural language generation to present results in a user-friendly manner.

## Usage

To use Chat with Databases using RAG, follow these steps:

1. Install the necessary dependencies and libraries listed in the `requirements.txt` file.
2. Run the application.
3. Input your query in natural language when prompted.
4. The system will automatically generate an SQL query and retrieve the results from the database.
5. Enjoy the seamless interaction between human language and database queries!


## License

This project is licensed under the [MIT License](LICENSE).



🧮 LangChain SQL Agent Demo with Streamlit (SQLite + MySQL Support)

This Streamlit app demonstrates how to chat with a relational database using LangChain’s SQL agent and Groq's LLaMA3 model. The application can connect either to a local SQLite database (student.db) or to a remote MySQL database, allowing users to ask natural language questions and receive intelligent, SQL-powered responses.

Key features:

->🗃️ SQLite3 and MySQL database support with dynamic UI toggle

->🧠 LangChain SQL Agent built with SQLDatabaseToolkit and create_sql_agent

->🤖 Groq API integration with streaming LLaMA3-8b-8192 model

->💬 Chat interface using st.chat_input and full message history

->🔄 Built-in message reset and connection caching

The included student.db contains academic records (name, class, section, marks) and serves as a ready-made demo dataset. This app is ideal for showcasing natural language to SQL conversion, real-time database interaction, and building intelligent chatbots over structured data using LangChain.

# Application Output Samples

This section demonstrates the capabilities of IPLGuru across different query types, including structured retrieval, conversational memory, semantic retrieval, and context switching.

---

## Case 1: Structured Query

This example demonstrates how IPLGuru routes a structured statistical query to the SQL retrieval layer and generates an accurate response using MySQL.

![Structured Query](figures/structured_query.png)

---

## Case 2: Structured Query with Conversational Memory

This example demonstrates IPLGuru's ability to retain conversational context and correctly answer follow-up questions without requiring the user to repeat previous information.

![Structured Query with Conversational Memory](figures/structured_query_conversational_mem.png)

---

## Case 3: Unstructured Query with Conversational Memory

This example demonstrates semantic retrieval using ChromaDB along with conversational memory, enabling IPLGuru to answer contextual IPL-related questions and follow-up queries.

![Unstructured Query with Conversational Memory](figures/unstructured_query_conversational_mem.png)

---

## Case 4: Correct Response When User Context Changes

This example demonstrates IPLGuru's ability to detect a shift in user context and generate responses based on the new conversation topic rather than incorrectly relying on previous context.

![User Context Change Handling](figures/user_context_change.png)

---

## Key Capabilities Demonstrated

- Structured Retrieval using MySQL
- Natural Language to SQL Conversion
- Semantic Search using ChromaDB
- Intelligent Query Routing
- Conversational Memory using LangChain
- Context-Aware Response Generation
- User Context Switching
- Hybrid RAG Architecture
# Day 5 – ChromaDB, RAG and LangGraph Agent with Memory

## Project: Sweet Crumbs Home Bakery

### Objective
To enhance the Sweet Crumbs Home Bakery chatbot by integrating a ChromaDB knowledge base with a LangGraph AI agent to answer customer questions using stored business information.

### Work Completed

**1. ChromaDB Knowledge Base**
- Created an in-memory ChromaDB client.
- Created a collection named `sweet_crumbs_faq`.
- Stored 16 bakery-related facts.
- Used one fact per document.
- Used `upsert()` to insert or update knowledge.

**2. FAQ Search Tool**
- Created a custom tool named `search_faq`.
- Implemented similarity search using ChromaDB.
- Added a docstring describing the supported topics, such as delivery, payment, cancellation, eggless cakes, allergens, storage and pickup timings.

**3. LangGraph Agent Integration**
- Integrated the FAQ search tool into the existing bakery agent.
- Used `create_agent()` to create the agent.
- Added `InMemorySaver()` as a checkpointer.
- Integrated `get_price`, `is_open`, `log_order` and `search_faq` tools.

**4. Conversation Memory**
- Tested the chatbot using two different thread IDs: `ravi` and `sravani`.
- Tested conversation history using follow-up questions.
- Maintained separate conversations for different customers.

**5. Unknown Question Testing**
- Tested questions that were not covered by the knowledge base.
- Updated system prompt rules to prevent the chatbot from making up information.
- Added the fallback response: "I'll check with the owner."

**6. Testing and Evaluation**
- Created a `tests.csv` file containing test questions and expected keywords.
- Tested chatbot responses.
- Calculated the test pass rate.

### Technologies Used
- Python
- Google Colab
- LangChain
- LangGraph
- Groq LLM
- ChromaDB

### Learning Outcomes
- Understanding vector databases and ChromaDB.
- Learning retrieval-augmented generation (RAG).
- Creating custom tools for AI agents.
- Integrating knowledge retrieval with LangGraph.
- Managing conversation history using checkpointers and thread IDs.
- Handling unsupported questions safely.

### Conclusion
Developed an enhanced bakery chatbot using ChromaDB and LangGraph. The chatbot retrieves relevant business information, maintains separate customer conversations and provides fallback responses when information is unavailable.

### Future Enhancement
Develop a LangGraph workflow to manage customer requests through multiple steps and integrate multiple agents.

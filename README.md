# 📚 BookNest

BookNest is an AI-powered book recommendation app that uses zero-shot classification and semantic search to suggest books based on user-described themes, genre preferences, and emotional tone. Built with the power of **LangChain**, **OpenAI embeddings**, and **Gradio**, BookNest helps users discover their next favorite read in a deeply personalized way.

--- 
## Features

- **Semantic Search:** Uses language embeddings to find books closely related to a user's natural language description.
- **Emotion-aware Filtering:** Prioritizes books based on desired emotional tone (e.g., joyful, suspenseful, sad).
- **Genre Customization:** Users can filter results by genre or category.
- **Gradio Interface:** Clean and interactive front-end for seamless user experience.

---

## 🛠️ Technologies Used

- **Python**
- **LangChain** (`langchain`, `langchain_community`)
- **OpenAI Embeddings**
- **ChromaDB**
- **Pandas** & **NumPy**
- **Gradio** 

---
## How It Works

1. **Input:** User types a description (e.g., _“A mysterious journey of self-discovery in a fantasy world”_).
2. **Filter:** Choose a genre and/or an emotional tone.
3. **Search:** The system performs a semantic similarity search on book descriptions using vector embeddings.
4. **Results:** The top matching books are returned and displayed with cover images and short summaries.

---
## Demo
 

### Search with no filters applied:
https://github.com/user-attachments/assets/a9682e98-bbf7-49c7-a6fe-2b9b3f95c7b7

### Search with the 'non-fiction' and 'suspense' filters applied:
https://github.com/user-attachments/assets/ac510532-bc21-4eb9-980c-ee4fb6ffae83

### Search with the 'non-fiction' and 'sad' filters applied:
https://github.com/user-attachments/assets/d0965485-9f3f-42ef-8c3c-a56807d7aae5


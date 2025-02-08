# RAG Test Project 2
This project is based on the "Build a Retrieval Augmented Generation (RAG) App: Part 1" tutorial from LangChain. It implements a generative AI chat system that allows document uploads and retrieves information based on the uploaded content.

## 🚀 Tech Stack
- Node.js
- LangChain.js (vector store)
- LangSmith
- GoogleVertexAI (using their chat and embedding models)
- TypeScript (for type safety)
- Yarn (as the package manager)

**NOTE: Using other package manager (as NPM) may cause some kind of incompatibilites with @LangChain/VertexAI modules, as the documentation states Yarn as the preferred package manager.**

## 📌 Prerequisites
Before running the project, ensure you have:
- Node.js installed
- Yarn (enabled via Corepack, as preferred way to manage Yarn)

## 🛠️ Setup & Installation
### 1️⃣ Install Dependencies
yarn set version stable

yarn install
### 2️⃣ Create a .env file
Define your environment variables inside .env, such as:

LangSmith credentials from their website
GOOGLE_APPLICATION_CREDENTIALS=./config/google-credentials.json
### 3️⃣ Compile & Run the Project
npx tsc

node dist/rag.js

# LangChain File Embedder

This project integrates text and PDF files using LangChain, allowing users to query the embedded content. It consists of both a backend and a frontend component.

## Project Structure

- **Backend**: Implemented with Node.js and Hono. Handles file uploading, embedding, and querying with LangChain.
- **Frontend**: Built using React and styled-components. Provides interfaces for embedding files and asking questions.

## Backend

### Requirements

- Node.js (16.x or higher)
- npm or yarn

### Installation and Running

Navigate to the `backend` directory, install the dependencies, and start the server:
```bash
cd backend
npm install
npm run dev
```

API Endpoints:
```bash
GET /loadTextEmbeddings: Loads and embeds text files.
GET /loadPdfEmbeddings: Loads and embeds PDF files.
POST /ask: Accepts a user query and returns an answer based on the embedded content.
```


Frontend UI:
```bash
EmbedSection: Allows users to embed text or PDF files.
QuerySection: Enables users to ask questions based on the embedded content.
ResponseDisplay: Displays responses provided by the AI.
The frontend uses axios for making API requests and styled-components for styling UI components.
```

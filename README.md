# PackMate

[![Frontend](https://img.shields.io/badge/frontend-React-blue)](#)
[![Backend](https://img.shields.io/badge/backend-Node.js-yellow)](#)
[![Database](https://img.shields.io/badge/database-MySQL-brightgreen)](#)
[![AI](https://img.shields.io/badge/AI-LangChain-orange)](#)

PackMate is an **AI-powered travel that combines **image embeddings**, and **personalized trip planning**. Upload your wardrobe images, and interact with a smart assistant that retrieves relevant information and gives recommendations using **LangChain** and **RAG (Retrieval-Augmented Generation)**.

---

## Features

### Core
- **Image Embeddings & Wardrobe Management**: Upload wardrobe images and get outfit suggestions.
- **Personalized Travel Assistant**: Generate packing lists and travel suggestions.
- **Interactive Chat**: Real-time assistant responses powered by Socket.io.
- **Secure Authentication**: JWT-based access and refresh tokens.

### Additional
- Responsive **React frontend** using **Shadcn UI components** and TailwindCSS.
- Scalable backend built with Node.js and Express.
- Vector database for embeddings using **MySQL**.
- Multi-platform support for desktop and mobile.

---

## Tech Stack

| Layer         | Technology                                    |
| ------------- | --------------------------------------------- |
| Frontend      | React, Tailwind CSS, Shadcn UI, Vite          |
| Backend       | Node.js, Express.js                            |
| Database      | MySQL (Sequelize ORM)                         |
| Authentication| JWT (Access & Refresh Tokens)                |
| AI/ML         | LangChain, OpenAI API (Embeddings + Chat)    |
| Real-time     | Socket.io                                     |

---

## Screenshots

**Dashboard & Chat Interface**  
![Dashboard](https://via.placeholder.com/800x400.png?text=Dashboard+Screenshot)

**Wardrobe & Outfit Suggestions**  
![Wardrobe](https://via.placeholder.com/800x400.png?text=Wardrobe+Screenshot)

**Document Q&A**  
![Q&A](https://via.placeholder.com/800x400.png?text=Document+Q%26A+Screenshot)

---

## Installation

### 1. Clone the repository
```bash
git clone https://github.com/anshuuu680/PackMate-AI.git
cd PackMate-AI

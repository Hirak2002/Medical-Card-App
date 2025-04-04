# Medical Card

## Overview

Medical Card is a solution designed to provide a comprehensive overview of medical data from the client's perspective. The project aims to centralize medical data from various sources, make it easily understandable, allow clear comparisons over time, identify health trends, and make this data accessible in multiple languages and through an API.

### Goals

- **Centralize Data:** Aggregate medical data from different sources into one platform.
- **Simplify Explanations:** Provide clear explanations of medical metrics for better understanding.
- **Enable Comparisons:** Allow users to make clear comparisons of their medical data over time.
- **Identify Trends:** Highlight trends in the user's health data.
- **Multi-language Support:** Make the data accessible in various languages.
- **API Access:** Provide data accessibility through a well-structured API.

### Why This Project?

- **Time Efficiency:** Reduce the time spent by both patients and doctors on simple cases.
- **Self-awareness:** Empower individuals with a third perspective on their health situation, potentially offering insights different from their doctor’s assessments.
- **Travel Convenience:** Support data in various languages, beneficial for frequent travelers.
- **Future-proofing:** Prepare for the advent of AI doctors by centralizing medical data and making it accessible through an API.

## Tech Stack

### Frontend

- **Next.js:** Utilized for building the user interface of the application.

### Backend

- **Python:** Handles the backend logic and processes.

### Authentication

- **Clerk:** Manages user authentication.

### Database

- **Supabase:** Provides database services.

### Large Language Model (LLM)

- **Groq Llama 3 70b:** Used for processing and understanding text data.

### Agent Framework

- **Langchain + Langgraph:** Framework for creating and managing agents.
- **AgentOps:** Tracks agent activities.

### Text Recognition

- **GPT 4 Vision:** Recognizes and processes text from scanned documents.

### Containerization

- **Docker:** Ensures the application is containerized for easy deployment and scalability.

### Hosting

- **AWS:** Hosts the application, providing robust and scalable cloud services.

# KnowledgeHub AI

KnowledgeHub AI is a simple tool for HR, managers, and business teams to find company information quickly.

It stores internal documents such as policies, procedures, and training guides. Then it lets users ask questions in plain language and gives answers based on the documents.

## What this does for HR and managers

- Helps employees find answers to HR and company policy questions quickly
- Reduces time spent searching folders, emails, and shared files
- Keeps knowledge organized by topic, like HR, IT, finance, or legal
- Makes onboarding and staff support easier
- Tracks document uploads and questions asked for better visibility

## How it works

1. Upload documents into the system.
2. The project breaks documents into smaller parts for better search.
3. It uses AI to match questions with the most relevant content.
4. It returns an answer with links to the original document source.

## Main features

- Secure login for users
- Upload documents in PDF, DOCX, and TXT formats
- Organize documents by domain or topic
- Ask questions and get answers from your knowledge base
- Includes sample documents for quick testing
- Can run with Docker for easier setup

## Who should use it

- HR teams that want to share policies and procedures clearly
- Managers who need fast access to employee and company information
- Teams that want a central place for internal knowledge

## Simple setup

1. Start the project with Docker.
2. Upload documents to the right domain.
3. Ask questions through the `/questions/ask` endpoint.
4. Try the sample files in `app/utils/sample_docs/` first.

## Helpful endpoints

- `/auth/login` - sign in
- `/auth/register` - create a user
- `/documents/upload` - add a document
- `/questions/ask` - ask a question
- `/domains/` - list knowledge topics

## License

MIT
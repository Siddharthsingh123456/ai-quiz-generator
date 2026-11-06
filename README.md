# AI Quiz Generator

An AI-assisted learning app for creating topic-based multiple-choice quizzes and practicing with interactive answer selection.

## Features
- Configure quiz topic, question count, and difficulty
- Generate multiple-choice questions with four options
- Select answers and review scoring
- MongoDB persistence for generated quizzes
- Responsive learning-focused interface

## Stack
React 18 · Vite 5 · Node.js 24 · Express · Mongoose · MongoDB · OpenAI-compatible API · Vercel

## Requirements
Node.js 24.x, npm, an AI provider API key, and MongoDB URI for quiz persistence.

## Setup
```bash
git clone https://github.com/Siddharthsingh123456/ai-quiz-generator.git
cd ai-quiz-generator
npm install
```
Create a local `.env` based on `.env.example`:
```env
OPENAI_API_KEY=your_api_key
OPENAI_MODEL=gpt-4o-mini
MONGODB_URI=your_mongodb_connection_string
```
Do not commit credentials.

## Run
```bash
npm run dev
npm run build
npm run preview
```
`npm run check` runs the production build.

## Deploy
Import the repository root into Vercel and configure the required environment variables. Verify generation, answer selection, scoring, and persistence after deployment.

## Learning note
Review generated questions and answer keys before using them in formal assessments; AI output can be ambiguous or incorrect.

## License
No license file is currently specified. Contact the repository owner before reuse.

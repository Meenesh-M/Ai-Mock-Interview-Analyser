# AI Mock Interview Project

This project is a React-based application that helps users practice for job interviews using AI. It leverages the Gemini API to generate interview questions and provide feedback.

## Prerequisites

- Node.js (LTS version recommended)
- `npm` or `yarn` (package managers)

## Setup

1.  **Clone the repository** (if you haven't already).

2.  **Install dependencies**:
    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Environment Variables**:
    Create a `.env` file in the root directory and add the following keys:
    ```env
    VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
    VITE_GEMINI_API_KEY=your_gemini_api_key
    # Add other firebase keys as needed
    ```
    *(Note: Ensure your Gemini API key has access to the Generative Language API)*

## Running the Project

To start the development server manually:

```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:5173`.

## Building for Production

To build the project for production:

```bash
npm run build
# or
yarn build
```

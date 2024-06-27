# MyIndia_Assessment

# AI Models with A/B Testing and Mock API Integrations

## Overview

This project includes:
- A/B testing framework for content generation and recommendation algorithms.
- Mock APIs to simulate interactions with external services.
- Unit tests to ensure the correctness of AI models and integration.

## Setup

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-repo/ai-ab-testing.git
    cd ai-ab-testing
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up environment variables**:
    - Create a `.env` file in the project root directory with your OpenAI API key:
      ```
      OPENAI_API_KEY=your_openai_api_key
      ```

4. **Run the mock API**:
    ```bash
    python mock_api.py
    ```

5. **Run the content generation script**:
    ```bash
    python content_generation.py
    ```

6. **Run the recommendation script**:
    ```bash
    python recommendation.py
    ```

## Running Unit Tests

To run the unit tests, use the following command:
```bash
pytest tests/

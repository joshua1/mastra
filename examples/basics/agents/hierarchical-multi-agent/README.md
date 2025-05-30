# Hierarchical Multi-Agent Example

A simple supervisor planning agent that orchestrates calls to other agents using tools.

## Prerequisites

- Node.js v20.0+
- pnpm (recommended) or npm
- Anthropic API key

## Getting Started

1. Clone the repository and navigate to the project directory:

   ```bash
   git clone https://github.com/mastra-ai/mastra
   cd examples/basics/agents/hierarchical-multi-agent
   ```

2. Copy the environment variables file and add your Anthropic and OpenAI API keys:

   ```bash
   cp .env.example .env
   ```

   Then edit `.env` and add your Anthropic API key and your OpenAI API key:

   ```env
   ANTHROPIC_API_KEY=sk-your-api-key-here
   OPENAI_API_KEY=sk-your-api-key-here
   ```

3. Install dependencies:

   ```
   pnpm install
   ```

4. Run the example:

   ```bash
   pnpm start
   ```

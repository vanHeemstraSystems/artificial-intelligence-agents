## 200 - Set Up ActivePieces Integration

1. **Create a new ActivePieces flow**:
   - Log into your ActivePieces account
   - Click "Create New" and select "Flow"
   - Name it "[DevOps Engineer AI Training](https://cloud.activepieces.com/projects/WxKLmS8Tt0m32IUaiUkkB/flows/hKbl55TX2O2Iv25TG0RJG)".

2. **Add an AI integration**:
   - In your flow, add an AI step (OpenAI, Anthropic Claude, etc.)
   - Configure authentication with your API key

3. **Configure prompt engineering**:
   - Create a system prompt that includes your persona details: It is suggested to use [ScrapeGraphAI Integrations](https://www.activepieces.com/pieces/scrapegrapghai) for scraping the Persona from [UXPressia](https://uxpressia.com) where we store our Personas in combination with [ActivePieces](https://www.activepieces.com/). See [ScrapeGraphAI - Markdownify API endpoint](https://www.youtube.com/watch?v=T-gbEiMnST8). See also our Workflow in ActivePieces at https://cloud.activepieces.com/projects/WxKLmS8Tt0m32IUaiUkkB/flows/hKbl55TX2O2Iv25TG0RJG (Under Construction).
   - Use the "Few-shot learning" approach by including example Q&As
   - Structure the prompt with clear delimiters between context and examples

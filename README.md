# dms-class-pyai
Py in my AI - an ongoing class/meeting at the Dallas Makerspace.

## Setup Python
- install `uv`
  - https://docs.astral.sh/uv/getting-started/installation/
- `$ uv python install`

## Setup and use a LLM
- install `llm` Python package as a `uv` tool
- `$ uv tool install llm`
- `$ llm install llm-gemini`
- `$ llm keys set gemini`
- `$ llm -m gemini-2.0-flash 'Tell me about the Dallas Makerspace'`

## Create an agent
- mkdir and cd into...
- `$ uv init`
- `$ uv add "pydantic-ai[logfire,examples,cli,google]"`

## Resources:
- https://docs.astral.sh/uv/getting-started/installation/
- https://ai.pydantic.dev/agents/
- https://llm.datasette.io/en/stable/
- https://context7.com
- https://github.com/google-gemini/gemini-cli/blob/main/docs/cli/configuration.md

## Extra Resources:
- https://www.tiobe.com/tiobe-index/
- https://automatetheboringstuff.com
- https://treyhunner.com

## Tips & Tips
- Sending links to Perplexity to summarize (like youtube videos)

## Tools:
- `yt-dlp` - for downloading YouTube videos.

## Ideas:
- Try to use NotebookLM from outside of itself (unofficial API)
- Scrape bot for reddit - AI-related subreddits (to learn more AI stuff)
- Scrape Discord to get a summary of what was talked about

## TODO:
1. beginner landing page with instructs to get started (Github Codespaces)
2. initial project
  - using pocketflow
  - have an agent that scrapes a subreddit (input)
  - display summary of data to termianl
  - send output as file to Google Drive (output)
3. use Discord -> Dallas Makerspace -> SIG -> "artificial-intelligence"
4. Figure out which PocketFlow tutorials should be done in what order,
which ones build upon others, and which can be grouped for a more complex demo.
5. Prompt people to give demos of what they created (like a lightening talk)
6. Ask for ideas/examples of what things or types of things people want to see in the future.


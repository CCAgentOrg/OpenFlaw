# PicoSearch Skill

Use this skill for web search queries. This wraps your self-hosted SearXNG instance for private, free web search.

## When to use

- User asks to "search", "look up", "find info on", "google", "web search"
- Any question requiring current information from the web

## How to use

Run the PicoSearch CLI:
```bash
python /root/.openclaw/workspace/picorouter/picosearch.py -q "your query"
```

## Configuration

The skill uses your SearXNG instance configured in picorouter.yaml:

```yaml
search:
  searxng_url: https://ccsearxng.zeabur.app
```

## Output format

Return search results in a clean format:
- Title (bold)
- URL  
- Brief snippet (2-3 lines max)
- Source/engine

Keep responses concise. Don't list more than 5-7 results unless user asks for more.

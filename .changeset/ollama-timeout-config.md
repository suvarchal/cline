---
"claude-dev": patch
---

Add configurable timeout for Ollama provider. This change increases the default timeout from 30 seconds to 120 seconds and makes it configurable via the ollamaTimeoutSeconds option. This helps prevent the "infinite thinking" problem that users experience with larger models that take longer to load.

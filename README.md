# continue-dev-config

a basic no-frills sample config for continue.

very closely adheres to [continue's docs](https://docs.continue.dev/reference#using-yaml-anchors-to-avoid-config-duplication)

## Pre-requisites

1. get api keys from openai & anthropic
2. install [ollama](https://github.com/ollama/ollama) and the two ollama models in the config (qwen2.5-coder:1.5b & nomic-embed-text)

## What do i do with this?

1. put it in your `/.continue` directory as `config.yaml`

AND/OR

2. modify it with repo-specific overrides in each repo in the `.continue/assistants` directory

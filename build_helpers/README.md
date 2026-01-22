# Build Helpers
This folder contains files needed to package up Cover Agent.

## `anthropic_tokenizer.json`
This file is needed as part of an import within the LiteLLM package.

## `model_prices_and_context_window_backup.json`
This file contains model pricing and context window information for LiteLLM. It is used locally instead of fetching from the network, which is important for packaged applications. The file is automatically downloaded from the LiteLLM GitHub repository and should be kept up to date.
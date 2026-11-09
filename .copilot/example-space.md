# Suggested Copilot context for RepoTestUse

This document is **human-readable guidance**, not a deployed Copilot Space, an official YAML schema, or proof that any toolset is connected.

## Suggested source context

Use only repository content that is appropriate for a public example:

- [`README.md`](../README.md): repository purpose and limitations
- [`mcp_config.json`](../mcp_config.json): example client-side MCP settings
- [`.devcontainer/devcontainer.json`](../.devcontainer/devcontainer.json): development-container setup
- [`.github/workflows/blank.yml`](../.github/workflows/blank.yml): illustrative, non-validating workflow

## Useful questions for an assistant

- What configuration files does this repository contain?
- Which statements are examples rather than verified live integrations?
- What would need to be tested before introducing a real MCP endpoint?
- Which repository files must remain free of secrets and private project data?

## Verification

If you use a Copilot context or MCP client, check its current supported configuration format and authentication model in that client's official documentation. Verify the actual tool connection, permissions, and returned results separately. Do not treat these notes as evidence that GitHub Copilot Spaces or MCP integration is configured.

**Do not add** client secrets, internal repository documents, production keys, token-bearing logs, or private project links to a public context collection.

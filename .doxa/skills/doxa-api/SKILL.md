---
name: doxa-api
description: Interact with the Doxa REST API to manage deployments, trigger builds, and query documentation site metadata programmatically.
license: MIT
compatibility: Any HTTP client. Authentication via API key.
metadata:
  author: doxa
  version: "1.0"
---

# Doxa API

Use the Doxa API to manage documentation sites programmatically. This skill covers deployment management, build triggers, and site metadata queries.

## Authentication

All API requests require an API key passed in the `Authorization` header:

```
Authorization: Bearer <your-api-key>
```

Generate API keys from the [Doxa dashboard](https://app.doxa.com) under Settings > API Keys.

## Core capabilities

### Trigger deployments

Programmatically trigger a documentation rebuild when your codebase changes outside of Git push events.

### Query site metadata

Retrieve information about your documentation site including deployment status, configured domains, and navigation structure.

### Manage preview deployments

Create and manage preview deployments for pull requests and branches to review documentation changes before they go live.

## Resources

- [API reference](https://doxa.com/docs/api)
- [Dashboard](https://app.doxa.com)
- [Deployment guide](https://doxa.com/docs/deploy)

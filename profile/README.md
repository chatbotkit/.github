[![CBK.AI](https://img.shields.io/badge/credits-CBK.AI-blue.svg)](https://cbk.ai)
[![Email](https://img.shields.io/badge/Email-Support-blue?logo=mail.ru)](mailto:support@cbk.ai)
[![Discord](https://img.shields.io/badge/Discord-Support-blue?logo=discord)](https://go.cbk.ai/discord)
![Views](https://komarev.com/ghpvc/?username=chatbotkit&color=blueviolet&style=flat-square&label=Views)
[![Follow on LinkedIn](https://img.shields.io/badge/LinkedIn-Follow-blue?logo=linkedin)](https://www.linkedin.com/company/chatbotkit)
[![Follow on Twitter](https://img.shields.io/twitter/follow/chatbotkit.svg?logo=twitter)](https://twitter.com/chatbotkit)

```
    .d8888b.  888888b.   888    d8P
   d88P  Y88b 888  "88b  888   d8P
   888    888 888  .88P  888  d8P
   888        8888888K.  888d88K
   888        888  "Y88b 8888888b
   888    888 888    888 888  Y88b
   Y88b  d88P 888   d88P 888   Y88b
    "Y8888P"  8888888P"  888    Y88b .ai
```

A modern, sovereign AI backend for products and enterprise deployments. Get
the breadth of a managed AI platform with control over the infrastructure,
data and extension points. Use it behind customer products, internal systems,
and regulated deployments without handing the AI control plane to a managed
provider.

<p align="center">
  <img width="2064" height="1400" alt="AI Platform" src="https://github.com/user-attachments/assets/714f6a5c-5b82-4b2a-af6a-51a1ce7260a1" />
</p>

## Platform

| Repository                                                    | Version                                                                                                                                                | Description                    |
| ------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------ |
| [chatbotkit/platform](https://github.com/chatbotkit/platform) | [![GHCR](https://img.shields.io/badge/GHCR-latest-blue.svg?logo=docker)](https://github.com/chatbotkit/platform/pkgs/container/platform-community) | The ChatBotKit AI Platform.    |

## SDKs

| Package                                                                                    | Version                                                                                                                       | Description                                    |
| ------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| [@chatbotkit/sdk](https://github.com/chatbotkit/node-sdk/tree/main/packages/sdk)           | [![NPM](https://img.shields.io/npm/v/@chatbotkit/sdk.svg)](https://www.npmjs.com/package/@chatbotkit/sdk)                     | The ChatBotKit API SDK.                        |
| [@chatbotkit/agent](https://github.com/chatbotkit/node-sdk/tree/main/packages/agent)       | [![NPM](https://img.shields.io/npm/v/@chatbotkit/agent.svg)](https://www.npmjs.com/package/@chatbotkit/agent)                 | The ChatBotKit Agent SDK.                      |
| [@chatbotkit/cli](https://github.com/chatbotkit/node-sdk/tree/main/packages/cli)           | [![NPM](https://img.shields.io/npm/v/@chatbotkit/cli.svg)](https://www.npmjs.com/package/@chatbotkit/cli)                     | The ChatBotKit CLI.                            |
| [@chatbotkit/react](https://github.com/chatbotkit/node-sdk/tree/main/packages/react)       | [![NPM](https://img.shields.io/npm/v/@chatbotkit/react.svg)](https://www.npmjs.com/package/@chatbotkit/react)                 | The ChatBotKit React SDK.                      |
| [@chatbotkit/next](https://github.com/chatbotkit/node-sdk/tree/main/packages/next)         | [![NPM](https://img.shields.io/npm/v/@chatbotkit/next.svg)](https://www.npmjs.com/package/@chatbotkit/next)                   | The ChatBotKit Next.js SDK.                    |
| [@chatbotkit/nextauth](https://github.com/chatbotkit/node-sdk/tree/main/packages/nextauth) | [![NPM](https://img.shields.io/npm/v/@chatbotkit/nextauth.svg)](https://www.npmjs.com/package/@chatbotkit/nextauth)           | The ChatBotKit NextAuth.js SDK.                |
| [@chatbotkit/fetch](https://github.com/chatbotkit/node-sdk/tree/main/packages/fetch)       | [![NPM](https://img.shields.io/npm/v/@chatbotkit/fetch.svg)](https://www.npmjs.com/package/@chatbotkit/fetch)                 | The ChatBotKit isometric fetch implementation. |
| [chatbotkit/go-sdk](https://github.com/chatbotkit/go-sdk)                                  | [![Go Reference](https://pkg.go.dev/badge/github.com/chatbotkit/go-sdk.svg)](https://pkg.go.dev/github.com/chatbotkit/go-sdk) | The ChatBotKit Go SDK.                         |
| [chatbotkit/python-sdk](https://github.com/chatbotkit/python-sdk)                          | [![PyPI](https://img.shields.io/pypi/v/chatbotkit.svg)](https://pypi.org/project/chatbotkit/)                                 | The ChatBotKit Python SDK.                     |

## IaC

| Package                                                                                      | Version                                                                                                                                                   | Description                        |
| -------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------- |
| [terraform-provider-chatbotkit](https://github.com/chatbotkit/terraform-provider-chatbotkit) | [![Terraform Registry](https://img.shields.io/badge/Terraform-Registry-purple.svg)](https://registry.terraform.io/providers/chatbotkit/chatbotkit/latest) | The ChatBotKit Terraform Provider. |

## Other Tools

| Package                                                                                 | Version                                                                                                 | Description                                   |
| --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | --------------------------------------------- |
| [create-cbk-app](https://github.com/chatbotkit/node-sdk/tree/main/tools/create-cbk-app) | [![NPM](https://img.shields.io/npm/v/create-cbk-app.svg)](https://www.npmjs.com/package/create-cbk-app) | A quick tool to create a new CBK application. |

## A complete platform

- Agent builder and runtime
- Multi-provider model gateway
- Knowledge ingestion and retrieval
- More than 200 typed integrations
- MCP, OpenAPI, GraphQL and code tools
- Sandboxed code and shell execution
- Web widgets, portals and messaging channels
- REST and GraphQL APIs, webhooks and generated client types
- Node.js, Python and Go SDKs and a Terraform provider
- Authentication, users, teams, contacts and multi-tenant identity
- Access control, moderation, PII protection and audit
- Traces, events, ratings, usage and operational logs
- Replaceable database, storage, cache, queue and vector infrastructure

## Run it

Run the complete prebuilt stack with one command - no checkout, no build:

```bash
docker compose -f oci://ghcr.io/chatbotkit/platform-community:latest up
```

Open <http://localhost:3000>. Sign in with any email address and read the
six-digit code from the platform container log:

```bash
docker compose -f oci://ghcr.io/chatbotkit/platform-community:latest logs platform
```

## Built With ChatBotKit

- [AfterDark](https://afterdark.so/) - AI-powered creative platform.
- [FormShare](https://formshare.ai/) - Bring your forms to life with generative UI.
- [PeopleAI](https://people.ai/) - Experience history like never before with our AI chatbots.

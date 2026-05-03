# SuperTokens

SuperTokens is an open source authentication solution providing session management, social login, email/password auth, and passwordless flows for web and mobile apps. It is an open source alternative to Auth0, Firebase Auth, and AWS Cognito. SuperTokens exposes a Core Driver Interface (CDI) HTTP API for backend SDKs to communicate with the supertokens-core service. Available SDKs cover Node.js, Python, Go, React, Flutter, iOS, and Android.

**URL:** [APIs.yml](https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/apis.yml)

## Tags

- Authentication
- Open Source
- Session Management
- Social Login
- Passwordless
- Identity
- Authorization
- Multi-Tenancy
- Node.js
- Self-Hosted

## APIs

### SuperTokens Core Driver Interface

The Core Driver Interface (CDI) is the REST API exposed by the supertokens-core HTTP service. Backend SDKs use this API to perform authentication operations including session management, sign-up/sign-in, email verification, password reset, multi-tenancy, and user metadata management.

- **Human URL:** [https://github.com/supertokens/core-driver-interface](https://github.com/supertokens/core-driver-interface)
- **Base URL:** `http://{supertokens-core-host}:{port}`

#### Properties

| Type | URL |
|------|-----|
| Documentation | [https://supertokens.com/docs](https://supertokens.com/docs) |
| OpenAPI | [supertokens-core-driver-interface-openapi.yml](openapi/supertokens-core-driver-interface-openapi.yml) |
| GitHub Repository | [supertokens/supertokens-core](https://github.com/supertokens/supertokens-core) |
| API Specification | [supertokens/core-driver-interface](https://github.com/supertokens/core-driver-interface) |
| JSON Schema | [supertokens-session-schema.json](json-schema/supertokens-session-schema.json) |
| JSON Structure | [supertokens-session-structure.json](json-structure/supertokens-session-structure.json) |
| JSON-LD | [supertokens-context.jsonld](json-ld/supertokens-context.jsonld) |
| Spectral Rules | [supertokens-cdi-rules.yml](rules/supertokens-cdi-rules.yml) |
| Capabilities | [authentication.yaml](capabilities/authentication.yaml) |
| Vocabulary | [supertokens-vocabulary.yml](vocabulary/supertokens-vocabulary.yml) |

## Capabilities

### Shared Definitions

| File | Description |
|------|-------------|
| [capabilities/shared/core-driver-interface.yaml](capabilities/shared/core-driver-interface.yaml) | SuperTokens CDI — full consumes definition for all auth operations |

### Workflow Capabilities

| File | Description |
|------|-------------|
| [capabilities/authentication.yaml](capabilities/authentication.yaml) | Authentication — unified REST and MCP interfaces for authentication management (19 tools) |

## SDKs

| Language | Repository |
|----------|-----------|
| Node.js | [supertokens/supertokens-node](https://github.com/supertokens/supertokens-node) |
| Python | [supertokens/supertokens-python](https://github.com/supertokens/supertokens-python) |
| Go | [supertokens/supertokens-golang](https://github.com/supertokens/supertokens-golang) |
| React | [supertokens/supertokens-web-js](https://github.com/supertokens/supertokens-web-js) |
| Flutter | [supertokens/supertokens-flutter](https://github.com/supertokens/supertokens-flutter) |

## Common Properties

| Type | URL |
|------|-----|
| Website | [https://supertokens.com](https://supertokens.com) |
| Documentation | [https://supertokens.com/docs](https://supertokens.com/docs) |
| GitHub Organization | [https://github.com/supertokens](https://github.com/supertokens) |
| Changelog | [CHANGELOG.md](https://github.com/supertokens/supertokens-core/blob/master/CHANGELOG.md) |

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

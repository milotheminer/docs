# CallHeater API Docs

Customer-facing documentation for the CallHeater API.

## Contents

- `index.mdx`: API overview.
- `quickstart.mdx`: First phone lookup request.
- `api-reference/openapi.json`: Customer-facing OpenAPI specification.
- `api-reference/endpoint/`: Generated reference pages for lookup endpoints.

The public docs only cover customer usage, such as calling the lookup API with a provided API key.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

Open the preview URL printed by the Mintlify CLI.

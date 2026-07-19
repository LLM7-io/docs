# LLM7.io Documentation

Documentation for building with the LLM7.io API.

## LLM7 API token

The examples require an `api_key` value. Use a token from [dash.llm7.io](https://dash.llm7.io/) for higher limits. Anonymous text requests can use `unused` where documented.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation changes locally:

```bash
npm i -g mint
```

Run the preview from the directory that contains `docs.json`:

```bash
mint dev
```

View the local preview at `http://localhost:3000`.

## Publishing changes

Changes are deployed to production automatically after pushing to the default branch when the repository is connected to Mintlify.

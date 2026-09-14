<div align="center">

# maginary

midjourney-style ai image and video generation, with a `--flag` prompt language and an api built for agents.

[maginary.ai](https://maginary.ai) · [docs](https://maginary.ai/docs) · [mcp server](https://mcp.maginary.ai) · [demo](https://vimeo.com/1226724272)

</div>

---

## what this is

maginary generates images and video from a text prompt using a `--flag` dsl (`--ar 16:9`, `--v`, `--flagship`, and more) — variations, upscales, pans, and zooms, the same interaction model as midjourney, over a plain async http api.

## connect an agent

- **mcp** — [`maginary-mcp`](https://github.com/maginaryai/maginary-mcp) ([pypi](https://pypi.org/project/maginary-mcp/)). connect claude desktop, cursor, or any mcp client to `mcp.maginary.ai`, no install needed.
- **rest** — plain http + openapi, works with any http-capable agent or script.
- **x402** — agents can pay per call in usdc on base, no signup. the api answers `402` with the exact price; settle it and the response comes back.

## links

- product and dashboard: [app.maginary.ai](https://app.maginary.ai)
- api docs: [maginary.ai/docs](https://maginary.ai/docs)
- parameter reference: [maginary.ai/docs/parameters.json](https://maginary.ai/docs/parameters.json)

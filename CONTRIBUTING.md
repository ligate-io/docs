# Contributing

These docs welcome external contributions. The full contributor guide
lives at [`contributing.mdx`](contributing.mdx) (rendered at
[docs.ligate.io/contributing](https://docs.ligate.io/contributing));
this file is the source-tree summary for anyone landing here from
GitHub.

## Two-minute version

1. Click the "Edit this page" link on any docs page (the GitHub web
   editor handles the rest), or `git clone` and edit `.mdx` files
   locally.
2. Open a PR against `main`.
3. The CLA Assistant workflow comments with a sign link on your first
   PR; one click signs and unblocks the PR. Bots and Ligate Labs
   employees are allowlisted.
4. CI runs `mint broken-links` to catch reference rot; Mintlify
   builds a preview for review.

## Local dev

```bash
git clone https://github.com/ligate-io/docs
cd docs
npm i -g mint
mint dev      # http://localhost:3000, hot-reloads on save
```

## Conventions

- **Active voice**, address the reader as "you", sentence-case
  headings.
- **No em dashes** in prose. Periods, commas, colons, parens.
- **Verify against source**, README files drift, code doesn't. Map
  in [`contributing.mdx`](contributing.mdx) under "Source
  verification".
- **One commit message line** per commit. No multi-paragraph bodies.

## File issues

- **This repo**: [github.com/ligate-io/docs/issues](https://github.com/ligate-io/docs/issues)
- **Chain bugs**: [github.com/ligate-io/ligate-chain/issues](https://github.com/ligate-io/ligate-chain/issues)
- **CLI**: [github.com/ligate-io/ligate-cli/issues](https://github.com/ligate-io/ligate-cli/issues)
- **JS SDK**: [github.com/ligate-io/ligate-js/issues](https://github.com/ligate-io/ligate-js/issues)
- **HTTP API**: [github.com/ligate-io/ligate-api/issues](https://github.com/ligate-io/ligate-api/issues)

For protocol proposals, open in
[`ligate-research`](https://github.com/ligate-io/ligate-research)
with the `LIP` label.

## License

Contributions are licensed under the
[Ligate Labs Inc. Contribution License Agreement](CLA.md). Repo
license: see [`LICENSE`](LICENSE).

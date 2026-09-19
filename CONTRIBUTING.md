# Contributing to Image Compressor

Contributions are welcome. Keep image processing client-side unless a privacy review and clear user consent are added.

## Setup

```bash
pnpm install
pnpm dev
```

Before a pull request:

```bash
pnpm check
pnpm build
pnpm format
```

## Guidelines

- Do not upload user images to an API.
- Test JPG, PNG, WebP, transparent images, large images, and invalid files.
- Preserve keyboard access and visible focus states.
- Revoke object URLs when replacing previews.
- Keep download names predictable and safe.
- Do not commit personal images or generated build output.

Use focused commits such as `feat: preserve transparent PNG output` or `fix: revoke preview object URLs`.

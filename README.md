# Image Compressor

[![Live demo](https://devilking7x.github.io/image-compressor/badge.svg)](https://devilking7x.github.io/image-compressor/) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> Shrink images without uploading them anywhere.

Image Compressor is a privacy-first browser utility for reducing image file size. Select or drop an image, adjust quality, preview the result, and download a compressed JPEG.

## Features

- Drag-and-drop or file picker input.
- Local canvas-based compression.
- Adjustable quality control.
- Preview, size comparison, savings percentage, and dimensions.
- One-click download.
- No backend, account, upload, or tracking.
- Responsive dark interface.

## Getting started

```bash
git clone https://github.com/devilking7x/image-compressor.git
cd image-compressor
pnpm install
pnpm dev
```

```bash
pnpm check
pnpm build
```

## Privacy

The selected image is processed in browser memory using the Canvas API. It is not intentionally sent to a server. Review any modified deployment or browser extension before using it with sensitive files.

## Tech stack

React, TypeScript, Vite, Canvas API, Tailwind CSS, Lucide React, and pnpm.

## Contributing

Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request. Improvements to formats, accessibility, performance, and documentation are welcome.

## License

MIT — see [LICENSE](LICENSE).

## Demo

Try the live app: https://devilking7x.github.io/image-compressor/

## Who it is for

This project is designed for **people preparing images for the web**. Its narrow first release focuses on helping them compress images in the browser without uploading originals. The interface uses realistic synthetic fixtures so the value is understandable without connecting a production account.

## Privacy and safety

The default experience is local-first: inputs are processed in the browser or in the user's own development environment, with no required account, API key, payment flow, or remote storage. Fixtures contain synthetic data only. Review a fork's hosting and analytics configuration before using it with sensitive information.

## Validation

The release workflow is intentionally reproducible. Run `pnpm install --frozen-lockfile`, `pnpm check`, and `pnpm build` before submitting a change. Manual review should cover keyboard operation, visible focus, mobile layout, empty states, and both successful and error paths.

## Limitations

This is a focused open-source MVP rather than a hosted replacement for a production system. It does not guarantee business, legal, financial, medical, accessibility, or security compliance by itself. Validate outputs against the context in which you plan to use them.

## License

Released under the [MIT License](LICENSE).


## Live demo

Open **[Image Compressor in the browser](https://devilking7x.github.io/image-compressor/)**. The default deployment uses GitHub Pages and does not require a custom domain.

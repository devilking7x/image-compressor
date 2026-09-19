# Image Compressor

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
git clone https://github.com/YOUR_USERNAME/image-compressor.git
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

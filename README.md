# SaaS Chat 路 Pixel Gallery (Remotion recreation)

A code-driven, 1920 脳 1080, 60 fps, 27.58-second motion study. It recreates the reference's visual sequence: train-window opener, botanical chat prompt, tilted word stack, pixel camera, editing UI, lime typographic wipe, spatial photo gallery, and peach closing card.

The photo assets in `public/assets/` were generated specifically for this project as visual substitutes. No source-video frames, signed source URL, or binding credential are included. This is a visual interpretation, not a pixel-perfect copy or an extraction of the original soundtrack.

## Run

Requires Node.js 20 or newer.

```bash
npm ci
npm run dev
```

Open composition `SaasChatPixelGallery` in Remotion Studio.

## Render

```bash
npx remotion render src/index.ts SaasChatPixelGallery out/recreation.mp4 --codec h264 --crf 22
```

## Structure

- `src/Composition.tsx`: all scene components, deterministic frame-based animation, and the full timeline.
- `src/Root.tsx`, `src/index.ts`: Remotion registration.
- `public/assets/`: generated photographic substitutes used by the composition.
- `package-lock.json`: reproducible dependency tree.

The MP4 output is intentionally excluded from Git. There is no original-source audio in this project.


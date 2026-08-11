# Clari5Pay_Static

Static landing page for Clari5Pay — identity verification, transaction
monitoring, AML screening, accounting and maker–checker workflows.

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | The entire site — markup, CSS and JS in one file |
| `clari5pay-demo.mp4` | Demo video shown in the "See It In Action" section |
| `CNAME` | Custom domain for GitHub Pages |

No build step and no dependencies. Open `index.html` directly, or serve
the folder over any static file server.

```bash
npx serve .
```

## Deployment

Served by GitHub Pages from the `main` branch at
[clari5pay.in](https://clari5pay.in).

## Notes

`index.html` is self-contained apart from the video, which is referenced
as an external file rather than embedded as a base64 data URI. Keep the
two files together — moving the HTML on its own will break the video.

The demo clip is AI-generated footage and carries the generator's
watermark, which identifies it as such.

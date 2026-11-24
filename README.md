# iAgentSi.com — public release candidate v1.0

Static HTML/CSS/JavaScript implementation of the supplied design reference. No package installation or build is required. The original video stream is retained without re-encoding; audio is removed and MP4 metadata is optimized for streaming.

## Local preview
Run `python -m http.server 8000` in this directory and open `http://localhost:8000/`. Root-relative URLs require a web server.

## Deployment
Commit the contents of this directory (not the parent ZIP) to the public repository. On Cloudflare Pages use no framework, no build command, and the directory containing `index.html` as output. Verify the canonical HTTPS host iagentsi.com and configure redirects for alternate hosts if needed.

## Verification
Check the published homepage, /thesis/, /robots.txt, /sitemap.xml, video MIME type/range requests, and absolute social image URL. Validate the preview on actual platforms after deployment. The local checks used Chromium with embedded copies of assets; deployed HTTP, font delivery, CSP and crawler previews remain unverified.

The public thesis is conceptual, not a product or a verified standard. No private acquisition materials belong in this repository.

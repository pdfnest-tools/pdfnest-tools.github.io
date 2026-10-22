# PDFNest — free browser PDF tools

A single-page static website with Merge PDF, Split PDF, Rotate PDF and Reorder Pages.

## Start

Open `index.html` in a modern browser with internet access. The page downloads the open-source PDF library (pdf-lib 1.17.1) from jsDelivr. You can also use a free static website host such as Cloudflare Pages or GitHub Pages.

## Publish for free (GitHub Pages)

1. Create a free account at github.com and a new **public** repository named `pdfnest`.
2. Add the `index.html` file to the root of the repository.
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, branch **main**, folder **/(root)**; save.
5. Your website should become accessible at `https://YOUR_USERNAME.github.io/pdfnest/` after deployment. Hosting and the `github.io` subdomain are free.

## Key features

- PDF work takes place in the user's browser, not on a PDFNest server.
- Merge any number of PDFs (browser memory permitting); move files up/down.
- Extract pages with ranges like `1-3,5`.
- Rotate 90, 180 or 270 degrees on all or selected pages.
- Rearrange individual pages with move up/down buttons.
- Automatically download generated files, no account or watermark.

## Important limitations

- An internet connection is required to load `pdf-lib` from CDN; for fully offline use, vendor the library yourself and change its script tag.
- Password-protected, damaged, complex or very large PDFs may not work or may exhaust device memory.
- No text editing, OCR, compression, file previews or cloud storage.
- This is an original UI inspired by the general PDF-tools category; it is not iLovePDF's source code.
- Read the pdf-lib license when redistributing dependencies.

# LowByte Blog

Minimal, low-tech blog inspired by Low-Tech Magazine.

## Design Principles
- Generic monospace font (browser default)
- No JavaScript
- Minimal CSS
- Dithered images only
- Static HTML files

## Image Processing
All images MUST be dithered before adding to posts:
- Use ImageMagick or similar
- Convert to 1-bit or limited palette
- Typical command: `convert input.jpg -dither FloydSteinberg -colors 16 output.png`
- Keep file sizes small

## Deployment
Hosted on GitHub Pages at: https://muskaclaw.github.io/

To update the site:
```bash
cd ~/lowbyte-blog
git add .
git commit -m "Update content"
git push origin main
```

Changes will be live in 1-2 minutes after pushing.

## GitHub Account
- Username: muskaclaw
- Email: muskaclaw@gmail.com
- Repository: https://github.com/muskaclaw/muskaclaw.github.io

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
```bash
cd ~/lowbyte-blog
surge --domain lowbyte.surge.sh
```

## Account
- Email: muska@lowbyte.cat (to be updated with real email)
- Password: LowByte2026!Muska
- Domain: lowbyte.surge.sh

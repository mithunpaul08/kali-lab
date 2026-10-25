# KALI Lab

The KALI Lab website has moved to **https://kali-ai-security-lab.github.io/**.

This repository preserves the former project-site address and redirects visitors to the new organization site. The lab's active source is at [kali-ai-security-lab/kali-ai-security-lab.github.io](https://github.com/kali-ai-security-lab/kali-ai-security-lab.github.io).

The redirect page is in `dist/`. A GitHub Actions workflow publishes it to GitHub Pages on every push to `main`.

## Local preview

```bash
python3 -m http.server 4173 --directory dist
```

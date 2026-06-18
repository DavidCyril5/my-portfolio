# David Cyril Portfolio — davidcyril.name.ng

## Overview
A fully rebuilt personal portfolio site for David Cyril (19-year-old Full Stack Developer, Abuja Nigeria). Static site served via Python `http.server` on port 5000.

## Architecture
- **Type**: Static HTML/CSS/JS (no framework, no build step)
- **Server**: `python3 -m http.server 5000 --bind 0.0.0.0`
- **Workflow**: "Start application"
- **API Base**: `https://apis.davidcyril.name.ng`

## Design System
- **Theme**: Dark (#0F0F0F / #0a0a0a), Gold accents (#FFD700 / #FF9500)
- **Font**: Poppins (Google Fonts)
- **Framework**: Bootstrap 5.3.2 + Font Awesome 6.5.1
- **Style**: Glassmorphism cards, animated floating orbs background
- **Photo**: `https://files.catbox.moe/4hq1u5.jpg`

## Pages
### Homepage (`/index.html`)
- Fixed navbar with scroll effect + active link highlighting
- Hero section: photo, typewriter role animation, gold gradient name
- Stats bar with animated counters (40+ projects, 100+ clients, 3+ years, 20+ APIs)
- Project grid with filter tabs (All / Downloaders / AI / Image / Utilities) — 22 project cards
- About section with skills + timeline
- Services section (4 cards)
- Contact section with WhatsApp + email
- WhatsApp FAB button
- Scroll reveal animations

### Project Pages (`/projects/*/index.html`) — 20 total
All share: dark glassmorphism card, 3 animated color orbs, platform-specific gradient, loading dual-ring spinner, result card, Home button

| Page | Route | API Endpoint |
|------|-------|-------------|
| YouTube | /projects/youtube/ | /download/ytmp4 or /download/ytmp3 |
| TikTok | /projects/tiktok/ | /download/tiktok |
| Instagram | /projects/instagram/ | /instagram |
| Facebook | /projects/facebook/ | /facebook |
| Spotify | /projects/spotify/ | /spotifydl |
| Twitter/X | /projects/twitter/ | /twitter |
| Pinterest | /projects/pinterest/ | /download/pinterest |
| SoundCloud | /projects/soundcloud/ | /download/soundcloud |
| Terabox | /projects/terabox/ | /download/terabox |
| MediaFire | /projects/mediafire/ | /mediafire |
| All-in-One | /projects/aio/ | /download/aio |
| AI Chatbot | /projects/chatbot/ | /ai/{model} (POST) — 10 models |
| Image Generator | /projects/imagegen/ | /imagegen |
| Image-to-Image | /projects/img2img/ | /imageToImage/seedream or /gpt-image-2 |
| Remove BG | /projects/removebg/ | /removebg (POST multipart or JSON) |
| Temp Mail | /projects/tempmail/ | /temp-mail (generate + inbox) |
| YT Summarizer | /projects/ytsum/ | /ai/yt-summarize |
| Link Bypass | /projects/linkbypass/ | /bypass/linkvertise |
| Wallpaper | /projects/wallpaper/ | /googleimage |
| Lyrics | /projects/lyrics/ | /lyrics |

## Contact Info
- WhatsApp: +2349066528353
- Email: Davidcyril209@gmail.com

## External Projects (no local pages, linked from homepage)
- TikSave: https://tiksave.name.ng
- Cinverse: https://cinverse.com.ng

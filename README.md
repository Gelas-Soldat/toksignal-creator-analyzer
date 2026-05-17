# TokSignal Creator Analyzer

[![Static Site](https://img.shields.io/badge/Static%20Site-Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://toksignal.netlify.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-3DA639?style=for-the-badge)](LICENSE)
[![Support](https://img.shields.io/badge/Support-Project-555555?style=for-the-badge)](SUPPORT.md)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ryancreates-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black)](https://buymeacoffee.com/ryancreates)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Gelassoldat-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white)](https://ko-fi.com/gelassoldat)

A mobile friendly TikTok style analytics dashboard for creators. Upload a CSV or paste TikTok Studio style table data, then get profile scoring, content pillar analysis, top post signals, growth insights, and next video ideas.

Live demo: https://toksignal.netlify.app/

## Status

MVP and actively improving.

This project is currently a static site. It runs fully in the browser and does not require a backend, database, login, or API key.

## Features

| Feature | Included |
| --- | --- |
| CSV upload | Yes |
| Paste analytics table data | Yes |
| Demo data | Yes |
| CSV template download | Yes |
| Mobile first layout | Yes |
| TikTok inspired dark theme | Yes |
| Glam and clean themes | Yes |
| Interactive charts | Yes |
| Creator score | Yes |
| Content pillar detection | Yes |
| Top post ranking | Yes |
| Auto generated insights | Yes |
| Next video ideas | Yes |
| Export report JSON | Yes |
| Buy Me a Coffee link | Yes |
| Linktree link | Yes |

## Privacy

TokSignal processes uploaded CSV and pasted analytics data locally in the browser. The current static version does not send creator analytics to a server.

## Quick start

Open `index.html` in your browser.

For a local preview server, run one of these commands from the project folder:

```bash
python3 -m http.server 8888
```

Then open:

```text
http://localhost:8888
```

On Windows PowerShell, this also works if Python is installed:

```powershell
python -m http.server 8888
```

## Deploy to Netlify

This repo is ready for Netlify.

| Setting | Value |
| --- | --- |
| Build command | Leave blank |
| Publish directory | `.` |
| Functions directory | Not used yet |

You can deploy it by connecting this GitHub repo to Netlify, or by dragging the project folder into Netlify deploys.

## CSV format

The analyzer works best with one row per TikTok video.

Recommended columns:

```csv
caption,date,views,likes,comments,shares,saves,duration
"Example makeup tutorial",2026-05-01,12000,900,80,110,220,34
```

Flexible column names are supported. For example, `title`, `video title`, `description`, `post date`, `views`, `likes`, `comments`, `shares`, `saves`, and `duration` are mapped where possible.

See `docs/CSV_GUIDE.md` for more detail.

## Paste analytics mode

Use Paste analytics when a creator copies rows from TikTok Studio, Excel, Google Sheets, Notion, or a CSV file. Include a header row so the analyzer can detect the columns.

Screenshots are not supported yet in this static version.

## Support links

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ryancreates-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black)](https://buymeacoffee.com/ryancreates)
[![Linktree](https://img.shields.io/badge/Linktree-ryandevs-43E660?style=for-the-badge&logo=linktree&logoColor=black)](https://linktr.ee/ryandevs)
[![TikTok](https://img.shields.io/badge/TikTok-Fluffy%20Nerdy%20Glam-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@fluffynerdyglam)
[![TikTok](https://img.shields.io/badge/TikTok-Gristlem-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@gristlem)

| Link | URL |
| --- | --- |
| Buy Me a Coffee | https://buymeacoffee.com/ryancreates |
| Linktree | https://linktr.ee/ryandevs |
| TikTok, Fluffy Nerdy Glam | https://www.tiktok.com/@fluffynerdyglam |
| TikTok, Gristlem | https://www.tiktok.com/@gristlem |

## Roadmap

Planned upgrades are listed in `docs/ROADMAP.md`.

## Repository topics

Suggested GitHub topics:

```text
tiktok analytics creator-tools netlify csv dashboard chartjs papaparse content-strategy social-media-tool static-site
```

## License

MIT License. See `LICENSE`.

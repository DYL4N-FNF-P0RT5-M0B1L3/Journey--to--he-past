# Wayback Web Restorer

A static GitHub Pages website for finding historical versions of websites through the Internet Archive Wayback Machine.

## Features

- Exact URL capture search
- Whole-domain capture search
- Historical results with timestamps
- Open archived snapshots
- Raw/original capture links
- Wayback availability check
- Responsive dark interface
- No backend/server required

## GitHub Pages

1. Upload `index.html` to a GitHub repository.
2. Open **Settings → Pages**.
3. Select the `main` branch and `/ (root)`.
4. Save and open the generated GitHub Pages URL.

## Important

This project uses public Internet Archive endpoints from the browser. API availability, rate limits, CORS behavior, and archive coverage are controlled by the Internet Archive, not this page.

Archived websites can be incomplete: missing images, stylesheets, scripts, videos, redirects, or interactive features are normal for some captures.

## API endpoints used

- Wayback CDX Search API: `https://web.archive.org/cdx/search/cdx`
- Wayback Availability API: `https://archive.org/wayback/available`

No API key is embedded or required.

# Lahman Family Farm

Single-page sample website for Lahman Family Farm, a family poultry farm in New Lebanon, Ohio (Montgomery County). Est. 2024.

- **Phone:** (937) 564-9351
- **Address:** 860 S Church St, New Lebanon, OH 45345
- **Hours:** Wednesday and Thursday, 10:00 AM to 8:00 PM; closed other days (from the farm's Square booking page)
- **Email:** erinjelizabeth.ej@gmail.com (listed on the Square page; contact Erin Lahman)

## Structure

- `index.html`: the whole site. CSS is inline and there's no build step. The identity follows the farm's own logo: cream, barn green and saddle brown, set in Alegreya and Alegreya Sans, with light and dark themes.
- `img/logo.jpg`, `img/logo-180.jpg`, `favicon.png`: the farm's real logo (barn, hen, cow, "Est. 2024", Psalm 24:1), taken from its Square booking page.
- `img/` (everything else): stock photos from Unsplash (hens, eggs, red barn, farm at dusk). They're credited in the footer as representative, not the farm's own.

## Sections

1. Hero with the logo medallion, call and text buttons, and a live "Open now / Closed" badge (computed in Ohio time)
2. Info strip: hours, address, phone, est. 2024
3. Our farm: short intro and the Psalm 24:1 verse from the logo
4. From the coop: eggs, poultry and order-ahead cards, each opening a prefilled text
5. Farm days: weekly hours table with today highlighted
6. Psalm 24:1 photo band
7. How it works (3 steps)
8. Text-a-note builder that opens a prefilled SMS to (937) 564-9351
9. Visit: address, directions, email, embedded Google map
10. FAQ and contact band

## Data sources and honesty

- **Google Maps:** "Lahman Family Farm", category *Poultry farm*, 860 S Church St, phone +1 937-564-9351. The listing is unclaimed and has no photos, hours, reviews or website.
- **Square booking page** (square.site/book/535X3TGG80Q4V): address, Wed/Thu 10–8 hours, email, logo. No services are listed there.
- **Instagram @erin.lahman** (linked from Square) is Erin's personal cosmetology account, with posts from 2017–2021. It isn't linked from the site, and none of its photos are used.
- No Facebook page or other listing turned up.

"Eggs" and "poultry" are phrased as "ask about...", since no product list is published. No prices, breeds, history, reviews or family details beyond the logo were invented. The Square hours are undated, so the site suggests calling to confirm.

The Sendra tracking script is included before `</body>`.

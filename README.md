# Formation Research — rebrand mockup

A static mockup of a rebranded [formationresearch.com](https://www.formationresearch.com/), aimed at funders and journalists.

## What changed

- **Layout**: moved from full-screen photo banners to an editorial layout — light backgrounds, large serif headlines, uppercase section labels, bordered card grids, and a sticky white header.
- **Colours and type**: unchanged from the current site. Deep purple `#33005D`, the violet-to-indigo button gradient, the pale blue page wash, the dark grey footer, Times New Roman headings, and Lato body text are all carried over.
- **Copy**: the original site's text, with technical phrasing translated for a non-specialist audience (for example, "digital error correction" became "software does not age, forget, or die", and the definition of a secret loyalty is spelled out in plain terms). No new claims were added; redundant passages were merged.
- **Register interest**: broadened beyond research roles to include engineering, operations, communications, policy, and fundraising, with a note that registering interest is not a job application. The button still points to the existing Tally form.

## Pages

| File | Purpose |
| --- | --- |
| `index.html` | Home: mission, what lock-in is, focus areas, current research focus, recent publications, get involved |
| `about.html` | Who we are, scenarios studied, vision, approach, team |
| `research.html` | Publications |
| `lock-in.html` | Plain-language explainer of lock-in |

## Viewing

Open `index.html` in a browser, or serve the directory:

```
python3 -m http.server
```

Images and logos are reused from the current site (downscaled). External links (newsletter, Tally form, papers, LessWrong) point at the live destinations.

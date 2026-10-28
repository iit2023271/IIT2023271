# Personal Profile Page

A single-file personal profile web page for Saladi Vishnu Vardhan (IIIT Allahabad).

![Demo](screenshots/demo.png)

## What it is

A standalone profile page built with plain HTML and inline CSS — no framework, no build step, no JavaScript dependencies. It presents personal details, education, skills, and hobbies in one scrollable page, with a link out to a projects hub.

## Sections

- **Personal Information** — name, college, email, phone, and hometown.
- **Education** — a table of Class 10 and Class 12 results with school, year, and percentage.
- **Skills** — HTML, CSS, C, Python, and Figma.
- **Hobbies** — singing, dancing, and coding.
- **My Projects** — a link to the projects hub page.

## Tech Stack

- HTML
- CSS (inline, in the same file)
- A tiny inline script that opens the projects page

## How to Run

Just open the file — no install, no server needed:

```bash
# Option 1: open directly in a browser
open index.html

# Option 2: serve it locally
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Notes

- The page background images are loaded from an external URL, so they need an internet connection to display.
- This is a standalone profile page. It is not the GitHub profile README — that lives in a separate repo.

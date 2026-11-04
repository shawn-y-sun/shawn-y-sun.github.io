# AGENTS.md: rules for Shawn's personal site

Static personal website for Yuchen (Shawn) Sun. `Sun_Shawn_Resume.pdf` is the source of truth for
every fact on the site. If the CV and the site disagree, the CV wins until Shawn says otherwise.

## Never publish

- **Anything in `private/`.** Do not read it into the site, link to it, or commit it.
- **Invented or inflated facts.** No metric, title, date, employer, award, skill, quote or
  testimonial that is not in the CV or given by Shawn. If something is missing, ask.
- **Secrets.** API keys, tokens, passwords, `.env` files, SSH keys.
- **Personal details beyond the CV.** Home address, date of birth, ID or immigration documents,
  salary, references, transcripts, personal Gmail.
- **Confidential employer or client information.** Nothing about BMO, RBC or Accenture beyond the
  CV's wording: no internal system names, non-public figures or client names. The Accenture client
  stays "a Fortune 50 oil & gas client".
- **Other people's information.** Classmates, colleagues, Ice Condo owners, and any Columbia course
  material or Canvas content.
- **Raw source files.** `photo.JPG` stays local; the site uses only the small `photo-web.jpg` with
  metadata removed. `Sun_Shawn_Resume.pdf` is not linked or deployed unless Shawn asks.

## Ask Shawn first

- **Before any push or publication.** That covers commits to a remote, creating a repo, turning on
  GitHub Pages, and uploading to any host. For this project this overrides the global "git is
  pre-authorized" rule until Shawn lifts it here.
- **Before the first public release, reconfirm the phone number and work authorization details.**
  They are on the page because Shawn asked for all CV information, but they become public once live.
- Before adding or changing any fact that does not come from the CV.
- Before changing the section order, which follows the CV: Education, Experience, Additional
  Information.
- Before adding analytics, cookies, forms, embeds, or new third-party scripts.
- Before deleting or overwriting any file Shawn supplied.

Layout fixes, styling and accessibility fixes need no approval, as long as they stay local.

## Style

- **Voice:** professional with a casual edge. First person and warm in the intro and section
  subtitles; short sentences; no buzzwords or self-praise beyond what the CV states.
- **CV content:** keep the CV's wording for bullets and credentials. Show everything on the page,
  with nothing hidden behind clicks.
- **Color:** Columbia blue `#B9D9EB` leads, with deep navy for text and white tiles. Text on Columbia
  blue must be dark, and all text must meet WCAG AA contrast.
- **Navigation:** one sticky bar, one link per CV section, plus LinkedIn and GitHub. No dropdowns.
- **Layout:** tiles for grouped content; must work at phone width with no sideways scrolling.
- **Build:** plain HTML, CSS and a little JavaScript in `index.html`. No frameworks or build step.
  The page must stay readable with JavaScript off.
- **Accessibility:** semantic headings, alt text, visible keyboard focus, and respect for reduced
  motion settings.


## Never publish
- Phone number, home address, personal email
- Grades, salary, visa status, date of birth
- Anything in private/: add it to .gitignore first
## Ask me first
- Before any git push or change on GitHub
- Before deleting or overwriting a file
## Style
- Plain HTML and CSS, clean and minimal
- Portfolio as a gallery page that links to each project
## When you finish
- Tell me what you changed and what you skipped

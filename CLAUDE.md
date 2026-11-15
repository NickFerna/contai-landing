Landing page for contaí (financial services for small businesses, like bakeries, small grocers  - spreadsheets, organizing bills)
- Objective: generate leads through the form
- Deploy: Vercel auto-updates the live site with each push to the GitHub repository
- Theming is done with CSS custom properties on :root (palette: greens, amber, --warn orange) with a prefers-color-scheme: dark override. The .band class (dark green sections) re-declares those variables locally, and .band form resets them back to light values so the form stays readable inside a dark band. Keep this in mind when adding colors.
- Lead form (#lead) validates in the browser only. It does not submit anywhere yet; the hook point is the TODO in the script. No backend/service choice yet.
## Content rules:
- No invented testimonials, client counts or numbers: the service has no clients yet. 
- Keep secondary text high-contrast (dark, never faded grey). Subtitles must carry useful information or be removed.
- Copy style: avoid the "Não é X: é Y" / "Nada de X: Y" contrast pattern. Plain negatives in ordinary sentences are fine.
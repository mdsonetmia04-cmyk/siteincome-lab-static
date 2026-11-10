# SiteIncome Lab — static site

Static version of the **SiteIncome Lab** blog (website-monetization guides, starting with
Adsterra), migrated from Blogger so Google can index it. Blogger's built-in `?m=1`
mobile redirect made every post fail Google's fetch with a "Redirect error", leaving
0 pages indexed — this static host has no such redirect.

- Live: https://mdsonetmia04-cmyk.github.io/siteincome-lab-static/
- Source of truth for posts: Blogger export (`../posts.json`, `../pages.json`)
- Built by `../build-site.py` — re-run it after any content change, then push.
- Adsterra ad slots are marked with HTML comments; codes are added only after the new
  site is approved as a website in Adsterra.

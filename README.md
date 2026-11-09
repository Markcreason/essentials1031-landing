# 1031.essentials1031.net

The Essentials 1031 landing page linked from the outreach emails. One static
page (`index.html`), published by GitHub Pages from `main`; `CNAME` holds the
custom domain. DNS: a CNAME record `1031` → `markcreason.github.io` at GoDaddy
(the essentials1031.net zone).

Brand: the client site's palette and typeface (essential1031.com: dark green
#0C2318, cream #EEEADD, green #009154, Open Sans). Button green is darkened to
#007A46 so white text on it passes WCAG AA.

Rules for the content: education only. No named properties, sponsors,
offerings or returns; no urgency beyond the statutory 45/180-day deadlines;
no tax advice. The Offering Disclosure in the footer is copied word for word
from essential1031.com and must not be edited here; change it only when the
client's own disclosure changes.

Leads: both forms post to the Essentials outreach app's inbound webhook
(`ENDPOINT` near the bottom of `index.html`). Until that is set, the forms show
the phone number instead of sending.

To change the page: edit `index.html`, open a pull request, merge. Pages
republishes within a minute or two.

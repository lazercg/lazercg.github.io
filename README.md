# Birkat Shlomo — Registration Website

Public registration site for Kollel u'Mesivta "Birkat Shlomo", hosted on GitHub Pages
from this repository (`lazercg.github.io`).

- `index.html` — the bilingual (English / עברית) registration form. It opens with a
  language choice, works on phone, tablet and computer, and on Submit sends the
  registration to the site's Web3Forms account.
- `admin.html` — explains where registrations are stored and links to the
  Web3Forms submissions dashboard (sign in with the email used for the access
  key; registrations can be viewed and downloaded/exported there).

## Submissions setup

The form sends through [Web3Forms](https://web3forms.com). The site's access key
(created 2026-11-24 with the owner's Web3Forms account) is installed in the
`ACCESS_KEY` constant at the top of the script in `index.html`, and the form is
live. Submissions appear in the Web3Forms dashboard for that account.

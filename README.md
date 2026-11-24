# Birkat Shlomo — Registration Website

Public registration site for Kollel u'Mesivta "Birkat Shlomo", hosted on GitHub Pages
from this repository (`lazercg.github.io`).

- `index.html` — the bilingual (English / עברית) registration form. It opens with a
  language choice, works on phone, tablet and computer, and on Submit sends the
  registration to the site's Web3Forms account.
- `admin.html` — explains where registrations are stored and links to the
  Web3Forms submissions dashboard (sign in with the email used for the access
  key; registrations can be viewed and downloaded/exported there).

## Setup still needed

The form sends through [Web3Forms](https://web3forms.com). It becomes active once
a free Web3Forms **access key** (created with the owner's email) is placed in the
`ACCESS_KEY` constant at the top of the script in `index.html`.

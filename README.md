# recoflo.com

The public website of Recoflo, in English (`/`) and German (`/de/`).

Plain HTML and one stylesheet. There is no build, no JavaScript, no cookie
and no request to another host: the fonts and the pictures are in `assets/`.

## Looking at it

    python3 -m http.server 4173

then open http://localhost:4173. The paths start at the root, so the pages
do not work when opened as files.

## Changing it

- A text exists twice: in `index.html` and in `de/index.html` (Swiss
  spelling, `ss` for `ß`). Change both.
- The colours, the fonts and the sizes are the tokens at the top of
  `assets/site.css`. They are those of the application's design system.
- The screenshots in `assets/img/` come from the application's manual, which
  is shot over invented batches only. A new picture must show no customer
  data, no user name, and nothing of the administration or of the sign-in.
- The QR code on the drawn cover sheet (`assets/img/qr.svg`) says
  `https://recoflo.com` and nothing else.

## What the site does not say

How Recoflo is built or where it runs, how people sign in, what a QR code
contains, and who the customers are. Keep it that way.

## Fonts

Mona Sans and Hubot Sans, SIL Open Font License 1.1, `assets/fonts/OFL.txt`.

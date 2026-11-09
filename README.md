# New York Hill Restaurant

Website for New York Hill Restaurant, Thurber, Texas (I-20 Exit 367). A static site with no build step, served by GitHub Pages.

## Pages

- `index.html`: Home, hours, directions, and gallery
- `family.html`: Owner-operators, the Mills family
- `history.html`: Thurber's history and the origin of the name
- `food.html`: Breakfast and dinner hours, menu links
- `events.html`: Banquet room and event booking
- `contact.html`: Phone, address, email, hours, and Google reviews summary
- `404.html`: Not-found page

Shared styles are in `css/style.css`.

## Publishing with GitHub Pages

1. Push this repo to GitHub.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then save.
4. The site will be live at `https://racemills.github.io/new-york-hill/` (the URL may differ if the repo is under a different account).

`.nojekyll` tells GitHub Pages to serve the files as they are.

## Things to add

- **Photos:** Put real photos in `images/` using the file names the pages reference: `dining-room.jpg`, `steak.jpg`, `exterior.jpg`, `rolls.jpg`, `family.jpg`, `kitchen.jpg`, `staff.jpg`, `hamburger.jpg`, `breakfast.jpg`, `history-1.jpg` to `history-4.jpg`. Missing images are removed from the page and the grey frame stays in place.
- **Menus:** Add `menus/breakfast.pdf` and `menus/dinner.pdf`. The Food page links to them.
- **Facebook:** The Facebook link points to `facebook.com/NewYorkHIll`.
- **Google reviews:** The rating (4.7 from 1,625 reviews) and the review summary come from the Google listing and need updating by hand.

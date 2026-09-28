# Sentry Clone

This is my clone of the Sentry landing page (https://sentry.io/welcome/) for the DVM frontend task.
It's made with only HTML and CSS, no JavaScript.

## How to run

Just open `index.html` in the browser.

## Files

- `index.html` - the whole page
- `style.css` - all the styles, the media queries for mobile/tablet are at the bottom
- `assets/` - images, logos and the Dammit Sans font (downloaded from the Sentry site)

## Features

- Sticky navbar with dropdown menus that open on hover
- Mobile menu that opens when you click MENU. I used the checkbox hack for this since we can't use JS, and `<details>` tags for the Platform / Solutions / Resources sections
- The "breaks," word is tilted and straightens when you hover on it
- Hero image floats up and down a bit
- Logos keep scrolling in a loop under the UFO (the logos are added twice and the row moves by -50% so it loops smoothly)
- The two tab sections work with hidden radio buttons + labels, clicking a tab shows its image
- Platform picker in "Get started" uses the same radio button trick to switch between code snippets
- Feature cards become a sideways scrolling row on smaller screens
- Newsletter form uses `required` so the browser checks the email
- Responsive for mobile, tablet and desktop

## Things I couldn't do / known issues

- Marketing mode toggle is not there
- The copy button for code snippets needs JS so I left it out
- I only added 6 platforms to the picker instead of all of them
- The dropdown menus only open on hover so they don't really work with keyboard
- On the real site the mascot moves separately from the background and the logos get pulled up into the UFO beam. I couldn't figure out how to do that with just CSS so the whole hero image floats instead
- The gradient on the buttons just switches on hover instead of sliding across like on the real site

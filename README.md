# Decadance

A Decadence Game of the Numogram

Decadance is a single-file, browser-based card game inspired by the CCRU's numogram and Lemurian Pandemonium. Deal the Atlantean Cross, draw and pair cards to score points, and discover which of the 45 lemurs/demons governs your round.

**[Play it live](#https://doomcrypt.github.io/decadence/)** *(replace with your GitHub Pages URL once deployed)*

## About the game

Decadance is played with a reduced 36-card pack: values 1 through 9 across four suits, with all royal cards, tens, and jokers removed.

- Five cards are dealt face up in the Atlantean Cross (Set-1): Centre (Memories & Dreams), West (Destructive), East (Creative), North (Far Future), South (Deep Past).
- Five more cards are dealt face down (Set-2) and revealed one at a time.
- Each Set-2 card can be paired with a Set-1 card if their values sum to ten. A successful pair scores the difference between the two cards.
- A Set-2 card that cannot pair is discarded. Any Set-1 card left unpaired at the end of the round scores its value as a penalty.
- Your final round score maps to one of the 45 demons of the Lemurian Pandemonium, each drawn from CCRU numogram lore.

## Running it

This is a single self-contained HTML file with no build step and no dependencies beyond two Google Fonts loaded over the network.

1. Clone or download this repository.
2. Open `index.html` in any modern browser.

That's it. Everything (styles, game logic, and the full demon/card correspondence table) lives in that one file.

## Hosting on GitHub Pages

1. Push this repository to GitHub (public repo).
2. Make sure the game file is named `index.html` at the repo root.
3. In the repo, go to **Settings > Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose your main branch and the `/ (root)` folder, then save.
5. GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Credits

Built on the numogram and Lemurian Pandemonium framework developed by the Cybernetic Culture Research Unit (CCRU).

## License

MIT. See [LICENSE](LICENSE) for details.

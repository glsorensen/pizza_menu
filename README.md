# The Pizza Playbook

Menu for Sunday, October 4. One static page for GitHub Pages: no build step, no dependencies.

- `index.html`: the whole site (styles, intro animation, and script are inline)
- `assets/og-image.png`: the image shown when the link is texted or shared
- `assets/favicon.svg`, `assets/apple-touch-icon.png`: browser and home-screen icons
- `assets/fonts/`: self-hosted latin subsets of Graduate, Barlow and Barlow Condensed (SIL OFL, see `LICENSE.txt` there), so the page needs no Google Fonts
- `.nojekyll`: tells GitHub Pages to serve files as-is

The intro plays on every visit. The "Replay the intro" button at the bottom plays it again.

House plays have tap-to-reveal play diagrams; the scoreboard counts down to kickoff. The page still reads fully with JavaScript disabled (diagrams open, no intro).

Live at: https://glsorensen.github.io/pizza_menu/

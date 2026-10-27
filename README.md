# educational-games

A personal arcade for educational games created for my kids, mainly vibe coded.
Open `index.html` in a browser to see the arcade menu. No build or installation is required.

## Add a game

1. Put your game's HTML file in the repository root (for example, `math_puzzle.html`).
   Include any images, scripts, or styles it needs, using relative paths.
2. In `index.html`, replace the “No games yet” paragraph inside `<div class="games">`
   with a link to your game:

   ```html
   <a class="game" href="./math_puzzle.html">
     <h3>Math Puzzle</h3>
     <p>Practice maths with a fun puzzle.</p>
   </a>
   ```

3. Add another link inside the same container for each new game. Links are maintained
   manually; adding an HTML file alone does not add it to the menu.
4. Open `index.html` and check that each link launches the right game.

Game names above are examples; no games have been added yet.

## Publish with GitHub Pages

1. Merge your arcade files into `main` on GitHub.
2. Go to **Settings → Pages** in this repository.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select the **main** branch and **/ (root)** folder, then click **Save**.
5. Once GitHub Pages finishes deploying, visit
   <https://david-gang.github.io/educational-games/>.

Keep game links relative (for example, `./math_puzzle.html`, not `/math_puzzle.html`)
so they work both locally and under the repository's GitHub Pages path.

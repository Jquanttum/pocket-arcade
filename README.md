# Pocket Arcade

Ten retro games in a single offline HTML file: Tic-Tac-Toe, Snake, Tetris, Dino Run, Pong, Breakout, 2048, Minesweeper, Flappy, and Pac-Man.

## Play
Open `index.html` in any modern browser. No install, no internet. High scores are saved in the browser.

## Host it on GitHub Pages
1. Create a new repository and add `index.html` and this README.
2. Go to Settings, then Pages, choose the `main` branch and the `/ (root)` folder, and save.
3. Your arcade will be live at `https://<your-username>.github.io/<repo-name>/`.

## Add a game
Each game is an object with `init`, `update`, `draw` and `key` (plus optional `tap`, `swipe`, `move`). Copy one, then add it to the `games` array.

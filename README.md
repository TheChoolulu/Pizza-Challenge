# The Great Pizza Challenge

A replayable travel-deduction game starring Agent Christa and her white cowboy hat.

## Run locally
Open `index.html` in a modern browser. No build tools or server are required.

## Publish with GitHub Pages
1. Create a new GitHub repository.
2. Upload all files and the `assets` folder from this project.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will provide the public game URL after deployment.

## Current features
- Kids and Adult modes
- Junior Agent, Super Agent, and Pizza Intelligence Director difficulty levels
- Open-ended city/country deductions
- Neighborhood-level deduction on Director difficulty
- Separate location and pizza evidence streams
- Strategic assistance penalties and travel funds
- Pursuit-state mechanic instead of a countdown clock
- Player avatars or local photo upload
- Agent Christa artwork and near-miss scenes
- Randomized three-stop Quick Trip
- Printable vintage Pizza Passport with player photo/avatar and destination stamps

## Content expansion
Destination content lives in `data.js`. Add new destination objects there without changing the game engine in `app.js`.

## Important accuracy note
Before a public release, expand and fact-check the destination database, especially neighborhood-specific pizza claims and adult beer clues. The current build is an initial content set for play-testing.

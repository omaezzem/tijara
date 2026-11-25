# Tijara Lbled 🎲

A Moroccan property-trading board game for 3–8 friends: on one screen, or online with each friend on their own phone.
Buy cities, collect rent in dirhams, build houses and hotels, and be the last one standing.

## Play online with friends

One player opens the game and taps **Game jdida → Crée room**, then shares the 5-letter code (or the copied link). The host picks the room size (3 to 8 players) and friends join with **Dkhol l room**. The host keeps the page open until the end of the game. Online play goes through a free public MQTT relay over secure WebSocket, so it works on any network (4G included) and no server of your own is needed.

## Play

Open `index.html` in any browser, or play online on GitHub Pages.

## Put it online with GitHub Pages

1. Create a new **public** repository on GitHub, for example `tijara`.
2. Upload `index.html` and `README.md` (Add file → Upload files → Commit changes).
3. Go to **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
4. After a minute your game is live at `https://<your-username>.github.io/tijara/`.

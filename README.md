# Home Scorecard

A free, open-source, multi-sport digital scoreboard and broadcast analytics app. Designed as a zero-backend Progressive Web App (PWA), it runs directly in the browser and installs natively on Android with full offline support.

**Live App:** https://jeremiahpakki.github.io/home-scorecard/

## Features

### Cricket
* **Match Engine:** Supports Classic 2-Team and Terrace modes, 15-player squads, a step-by-step Virtual Toss wizard, and full ball-by-ball undo.
* **Broadcast Analytics:** Real-time Worm, Manhattan, Run Rate, and Beehive Pitch graphs, a 360° batter-perspective Wagon Wheel (with Team, Partnership, and Batter filters), and a live Projected Score matrix.
* **Innings-Aware DLS:** Dynamically recalculates revised targets and displays a persistent live DLS Par Score during rain-shortened matches.
* **Milestones & Commentary:** Automatic Hat-Trick, 50/100, and 5-wicket haul alerts, plus multiple live commentary styles.

### Court & Card Games
* **Badminton, Tennis & Table Tennis:** Interactive court diagrams showing legal/out service zones (including singles and doubles side strips), Hawk-Eye review challenges, and quick official rules.
* **Card Games:** Built-in scoring for games like UNO (with active Wild color tracking) and Least Count (with round undo).

### Broadcast & Display
* **Authentic Visual Themes:** Switch between World Cup '23, Classic Test, TATA IPL, Big Bash, 1992 Retro, and sport-specific court themes in both Light and Dark modes.
* **Scorer & Audience Views:** Dedicated Scorer Console with a slim frozen broadcast lower-third, plus a clean Stadium/HDMI Audience view.

## Install as an Android App (PWA)

1. Open [https://jeremiahpakki.github.io/home-scorecard/](https://jeremiahpakki.github.io/home-scorecard/) in **Chrome** on your Android device.
2. Tap the **⋮** menu in the top-right corner and select **Add to Home screen → Install**.
3. Launch it from your home screen for a full-screen, offline-ready experience.

## Architecture

Built as a lightweight, self-contained single-file web application (`index.html`) paired with a standard PWA manifest (`manifest.json`) and an offline-first Service Worker (`sw.js`). No servers, databases, or build steps required.

## License

This project is open source and available under the [MIT License](LICENSE).

# WebGames

A small collection of browser games built with plain HTML, CSS, and JavaScript. Each one messes with the player on purpose — fake progress, rigged randomness, a heist that's still being planned.

| Game | Status | Description |
|---|---|---|
| [Brain Lag](./Brain-Lag) | 🟢 Live | A "human verification" quiz that fakes progress and judges you for fun. |
| [Chaos Arena](./Chaos-Arena) | 🟢 Live | One-button card battle — draw random cards, chase points, avoid the villain card. |
| [Data Heist](./Data-Heist) | 🟡 In development | Learn SQL and analytics by solving real business cases, not quizzes. |

---

## Brain Lag

A short interactive quiz that pretends to test whether you're really human. The questions are simple on purpose — answering correctly doesn't guarantee progress, and the progress bar isn't telling the truth.

- **Play it:** [brainlag-phi.vercel.app](https://brainlag-phi.vercel.app/)
- **Source:** [`/Brain-Lag`](./Brain-Lag)
- **Built with:** HTML, CSS, JavaScript

## Chaos Arena

You and an opponent draw random cards with a single click. Cards have different power levels:

- 🟢 Weak card → +1 point
- 🔵 Strong card → +3 points and confetti
- 🔴 Villain card → game over

The battle runs until the round limit is hit, and whoever has the higher score wins. The randomness means no two matches play out the same way.

- **Play it:** [learning-lab-brown.vercel.app](https://learning-lab-brown.vercel.app/)
- **Source:** [`/Chaos-Arena`](./Chaos-Arena)
- **Built with:** HTML, CSS, JavaScript

## Data Heist

Still in planning. The goal: turn SQL learning into story-driven "missions" — e-commerce sales, hospital records, fraud detection, HR analytics — where you write real queries against a live SQL playground instead of answering quiz questions, with an optional AI assistant that explains rather than gives away answers.

- **Status:** PRD drafted, not yet playable
- **Source:** [`/Data-Heist`](./Data-Heist)

---

## Tech stack

No frameworks, no build step — just HTML, CSS, and JavaScript per game, deployed individually on Vercel.

## License

MIT — see [LICENSE](./LICENSE).

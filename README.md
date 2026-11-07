# Chess poster

Poster for chess.irl №4, 12 May 2026, Greenpoint, Brooklyn.

The poster sets one character of the title on each piece left on the board at the end of Kasparov's last game, Topalov–Kasparov, Linares 2005, after 30.Kg4. The squares behind the type are tinted by how often each square was occupied during the game. The info lines use the same squares on a smaller board at the bottom.

## Files

- `index.html` — Position Poster, the generator. Dark only, set after displaay.net: black ground, regular weights, hairline rules, the Displaay swatch palette (blue #222FF4, brown #A06F46, amber #E79A3A, orange #E27631). The poster title is set in Ofform (Displaay), embedded from `fonts/` so exports carry it; the date and info are one running sentence below the board in Serrif Light (Displaay), with Saans/Helvetica as the fallback and a board layout as an option. The sentence is sized to fill the space below the board. The title picks the position in the game with as many pieces as it has characters (15 to 32 for the Kasparov game). Ground swatches set the whole scheme on black, blue, brown, amber or orange; the canvas has the same `ground` option. Paste any game as PGN, type a title and info lines, pick type, pattern, colours and format, then export SVG or PNG. Replays the game with chess.js from cdnjs. Published as a Claude artifact: https://claude.ai/artifact/AzL2CbgQvpEJKtUChEy53i
- `fonts/` — Displaay trial files: Ofform (variable woff2 and TTFs) and Serrif Light (woff2). Trial licence: for testing only; swap for a licensed copy before printing.
- `design/project/` — the hand-set poster as a Claude Design canvas: `Main.dc.html` (900 × 1200), `Mobile.dc.html` (1080 × 1920 story) and `canvas.json`, the canvas index. Canvas: https://claude.ai/artifact/SePfEwm6FGjnZUh2jFiZ6N

The `.dc.html` files are Design Component pages and need the canvas runtime (`support.js`) to render; they are kept here as source.

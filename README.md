# dragon_candy
Dragon Candy is a kid-friendly browser adventure where you guide adorable dragons through candy-coated skies, rhythm stages, and rescue missions using simple tap controls. With rotating level themes—like the special toy-store backdrop every tenth stage—it blends whimsical visuals, upbeat music, and fast arcade pacing for endless pick-up-and-play fun.

Ensure the audio references inside `game.html` use paths like `Music/track-name.mp3`.

---

## 🚀 Run Locally

1. Clone or download the repo.
2. Open `game.html` directly in a modern browser (Chrome, Edge, Firefox, Safari).
3. For rhythm audio to autoplay reliably, open via a local server (e.g., `npx serve` or VS Code’s Live Server).

---

## 🌐 Deploying to GitHub Pages

1. Push `game.html` and the `Music/` directory to your GitHub repository.
2. Go to **Settings → Pages**.
3. Select the `main` branch (root folder) and save.  
4. After the build finishes, you can play at `https://<username>.github.io/<repo>/game.html`.

---

## 🧩 Customization Tips

- **Levels**: Edit the `levels` array to adjust mechanics, rhythms, or backgrounds.
- **Toy Store cadence**: The helper `shouldShowToyStore(levelNumber)` controls when the storefront appears (currently Levels 7, 17, 27, …).
- **Rhythm tuning**: Modify `rhythmDefaults` (BPM, hit windows, beat maps) to tweak the challenge curve.
- **Assets**: Drop new music into `Music/` and update references; no build step required.

---

## 🤝 Contributing

1. Fork the repo.
2. Create a feature branch (`feature/add-sparkle-effects`).
3. Commit changes (`git commit -m "Add sparkly fire breath"`).
4. Push and open a pull request.

Please lint/format JavaScript before submitting and include screenshots or GIFs for visual changes.

---

## 📝 License / Credits

- Code & art: **Dragon Candy Team** (feel free to credit yourself and collaborators).
- Fonts: System defaults + Comic Sans / Baloo (adjust if you add licensed fonts).
- Audio: Ensure any tracks in `Music/` are licensed for redistribution.

---

Have fun, and may your dragons bounce to victory! 🐉🍬

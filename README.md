> 🇫🇷 [Version française](README_fr.md)

# Proving Grounds of Nerdna — CodinGame Multiplayer RPG SDK Project

A tactical RPG multiplayer puzzle inspired by **Wizardry: Proving Grounds of the Mad Overlord** and **D&D 5e**, featuring **open-field natural boulders** (`sprite-pack.json`, CC0 Kenney packs) and dynamic PixiJS switching between **2D RPG Sprites Mode** and **Geometric Debug Mode** (`ToggleModule`).

---

## Quick Commands
* **Local Web Viewer (`http://localhost:8888/test.html`)**:
  ```bash
  cd proving-grounds-nerdna-sdk
  mvn test-compile exec:java -Dexec.mainClass="Main" -Dexec.classpathScope="test"
  ```
* **Batch Simulation (3 Leagues)**:
  ```bash
  cd proving-grounds-nerdna-sdk
  mvn test-compile exec:java -Dexec.mainClass="Main" -Dexec.classpathScope="test" -Dexec.args="--simulate"
  ```
* **Switch CC0 Sprite Pack**:
  ```bash
  python3 scripts/apply_sprite_pack.py kenney-tiny-dungeon   # or kenney-roguelike-field / kenney-1bit-retro / legacy-dark-stone
  ```

---

## CodinGame & GitHub Links

* **CodinGame Contribution**: https://www.codingame.com/contribute/view/15867946f675bf476dc7f164eb3db1d6ce58f6
* **Play in CodinGame IDE**: https://www.codingame.com/ide/demo/1605773233912493b234f7c05aadee6e291708f
* **GitHub Repository**: https://github.com/CGphilRG/codingame-proving-grounds-nerdna
* **6-Puzzle Showcase Hub (GitHub Pages)**: https://cgphilrg.github.io/codingame-sdk-puzzles/

> **Note:** League Boss files (`config/**/Boss.java`) are kept local-only and excluded via `.gitignore`.

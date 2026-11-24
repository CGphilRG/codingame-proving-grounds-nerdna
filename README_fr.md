> 🇬🇧 [English version](README.md)

# Proving Grounds of Nerdna — Projet CodinGame Multiplayer RPG SDK

Un puzzle multijoueur RPG tactique inspiré de **Wizardry: Proving Grounds of the Mad Overlord** et **D&D 5e**, avec **obstacles naturels (rochers) en champ ouvert** (`sprite-pack.json`, packs Kenney CC0) et bascule dynamique PixiJS entre **Mode Sprites RPG 2D** et **Mode Formes Géométriques Debug** (`ToggleModule`).

---

## Commandes Rapides
* **Viewer Web Local (`http://localhost:8888/test.html`)** :
  ```bash
  cd proving-grounds-nerdna-sdk
  mvn test-compile exec:java -Dexec.mainClass="Main" -Dexec.classpathScope="test"
  ```
* **Simulation Batch (3 ligues)** :
  ```bash
  cd proving-grounds-nerdna-sdk
  mvn test-compile exec:java -Dexec.mainClass="Main" -Dexec.classpathScope="test" -Dexec.args="--simulate"
  ```
* **Changer de banque de sprites CC0** :
  ```bash
  python3 scripts/apply_sprite_pack.py kenney-tiny-dungeon   # ou kenney-roguelike-field / kenney-1bit-retro / legacy-dark-stone
  ```

---

## Liens CodinGame & GitHub

* **Contribution CodinGame** : https://www.codingame.com/contribute/view/15867946f675bf476dc7f164eb3db1d6ce58f6
* **Jouer dans l'IDE CodinGame** : https://www.codingame.com/ide/demo/1605773233912493b234f7c05aadee6e291708f
* **Dépôt GitHub** : https://github.com/CGphilRG/codingame-proving-grounds-nerdna
* **Portail GitHub Pages (6 Puzzles)** : https://cgphilrg.github.io/codingame-sdk-puzzles/

> **Note :** Les fichiers Boss par ligue (`config/**/Boss.java`) sont conservés en local uniquement et exclus via `.gitignore`.

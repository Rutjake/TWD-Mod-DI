# 🧟 TWD Walkers Mod (Dead Island & Riptide Definitive Edition)
(Dead Island version not yet available)

A total conversion mod that transforms the fast-paced zombies into classic, slow, and terrifying **The Walking Dead** style walkers.

---

## [FI] Kuvaus suomeksi

Tämä modi muuttaa pelin zombit perinteisiksi kulkijoiksi. Modi poistaa zombeilta epärealistisen nopeuden ja erikoiskyvyt, keskittyen massaan, laahustavaan liikkeeseen ja vaarallisiin tarttumishyökkäyksiin.

### Tärkeimmät ominaisuudet:
* **Aito liike:** Kaikki zombit (mukaan lukien Infected, Thug ja Screamer) on hidastettu laahustavaan kävelyvauhtiin. Juokseminen on poistettu kokonaan.
* **Pureminen ja tarttuminen:** Zombit eivät enää lyö. Ne yrittävät jatkuvasti tarttua pelaajaan ja purra heti, kun etäisyys sallii.
* **Pääosumat ovat avain:** Vartaloiskut tekevät minimaalista vahinkoa. Vain pääosumat (murskaus tai katkaisu) ovat tehokkaita.
* **Kuuloaisti:** Zombit reagoivat ääniin ja askeleisiin huomattavasti näköaistia herkemmin.
* **Fysiikka ja massa:** Zombit tuntuvat raskaammilta. Ne eivät lennä iskusta, vaan horjuvat tai lyyhistyvät maahan.

---

## [EN] Description in English

This mod transforms the zombies into classic **The Walking Dead** style walkers. It removes unrealistic speed and special abilities, focusing on mass, shuffling movement, and lethal grab attacks.

### Key Features:
* **Authentic Movement:** All zombies (including Infected, Thugs, and Screamers) are slowed down to a shuffling walk. Running/Sprinting has been completely removed.
* **Grab & Bite Focus:** Zombies no longer use "punches." They constantly attempt to grab the player and bite as soon as they are within range.
* **Headshot Priority:** Body shots deal minimal damage. Only headshots (decapitation or head smash) are effective, forcing tactical combat.
* **Sound Sensitivity:** Walkers rely more on hearing than sight. They will track your footsteps and noises from a distance.
* **Realistic Physics:** Zombies have increased mass. They no longer fly back from hits; instead, they stagger or slump to the ground.

---

## 🛠 Installation / Asennus (Definitive Edition)

The recommended method is using the `out` folder. This keeps your original game files safe and untouched. / Suositeltu tapa on käyttää `out`-kansiota, jolloin pelin alkuperäiset tiedostot säilyvät koskemattomina.

### [EN] Instructions
1. Locate your game installation folder (e.g., `...\Steam\steamapps\common\Dead Island Riptide Definitive Edition`).
2. Navigate to the `DIR\out` folder. **If it doesn't exist, create it.**
3. Create the following folder structure inside `out`: `data\ai\zombie`.
   * Final path: `...\out\data\ai\zombie\`
4. Copy the `.scr` files from this repository into the `zombie` folder.
5. Launch the game. The engine will now prioritize these files over the original `.pak` data.

### [FI] Ohjeet
1. Etsi pelin asennuskansio (esim. `...\Steam\steamapps\common\Dead Island Riptide Definitive Edition`).
2. Mene kansioon `DIR\out`. **Jos kansiota ei ole, luo se.**
3. Luo `out`-kansion sisälle seuraava polku: `data\ai\zombie`.
   * Lopullinen polku: `...\out\data\ai\zombie\`
4. Kopioi tämän modin `.scr`-tiedostot luomaasi `zombie`-kansioon.
5. Käynnistä peli. Peli lukee nyt muokatut tiedostot `out`-kansiosta alkuperäisten sijasta.

> **Note:** To uninstall, simply delete the files from the `out` folder. / **Huom:** Poistaaksesi modin, poista vain tiedostot `out`-kansiosta.

---

## 🛠 Advanced Installation Method

**Quick installation**: 
1. **Open** `Data0.pak` from your game directory with, for example, 7Zip, and replace the files in the `data\ai\zombie` directory.

**Full installation**:
1. **Extract** `Data0.pak` from your game folder. (Remember to save a backup of the original file on your computer.)
2. **Replace** the original `.scr` files in `data\ai\zombie` with the modded versions.
3. **Repack** the `.pak` file or use the `out` folder method (recommended for Definitive Edition).

---

## ⚠️ Known Issues

* **Scripted Scenes:** Some scripted sequences (like NPC movements or specific quest triggers) may expect faster zombies. If a scene "freezes," temporarily revert to original files.
* **Base Game Assets:** The mod changes behavior, but original zombie models (Thugs, Screamers) remain unless manually swapped.

---

**Author:** Jake
**Game:** Dead Island / Dead Island Riptide (Definitive Editions)

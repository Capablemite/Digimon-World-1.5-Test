# Digimon World 1.5: Test Build 1

A fan-made mod of **Digimon World** (PlayStation, 1999) that adds Digimon from *Digimon Adventure 02* to File Island.
This is the first public **test build**. It's an early, partial version, released so players can try it out and report
problems.

This download is a **patch file only**. It doesn't contain the game. You need your own copy of the original game to
use it.

\---

## What's in this test

### Your first partner

At the start of a new game, Jijimon asks if you have a Digivice.

|Your answer|Your first partner|
|-|-|
|**Yes**, then **Day**|**Veemon**|
|**Yes**, then **Night**|**Wormmon**|
|**No**|The original game's questions|

### Two new Digimon lines

These Digimon digivolve the normal Digimon World way, through time, stats, care and battles.

* **Veemon line:** Chicomon → DemiVeemon → Veemon → ExVeemon / Veedramon / Flamedramon → MetalGreymon / SkullGreymon
* **Wormmon line:** Leafmon → Minomon → Wormmon → Stingmon / Shadramon → HerculesKabuterimon

The new Digimon have their own 3D models, animations and cries.

### New eggs

When your partner dies, the egg box offers **6 eggs**:

* The 4 original eggs (Botamon, Punimon, Poyomon, Yuramon)
* The **blue egg**, which hatches **Chicomon** (Veemon line)
* The **green striped egg**, which hatches **Leafmon** (Wormmon line)

### Getting around

**Biyomon** waits in Jijimon's house. Talk to her to take the same flights Birdramon offers, or
Whamon's sea trips. That way you can reach every area while testing.

### Other changes

* **Digivolution Chart:** The Chart now has **4 pages**, so there's room for the new Digimon. On the Chart, move the
cursor down past the last Baby box onto the page button, then press **X** to turn to the next page. The Tree view
also shows the right name under every new Digimon.
* **Tech screen, page 2:** The Tech screen has a **second page** for new techniques.
* **Care mistakes:** The Status screen now shows your partner's **care mistakes** (marked **MISTAKES**, next to
WEIGHT). Before, they were hidden.

Everything else plays like the original game: normal stats, lifespans, sleep, hunger and deaths.

\---

## What you need

1. **Your own copy of Digimon World (USA)** (SLUS-01032) as a disc image: a `.bin` file plus its `.cue` file.
The patch was made from this exact file:

|||
|-|-|
|Size|381,771,936 bytes|
|CRC32|`E6FDD00E`|
|MD5|`8520edac0f7f1454f8a008ac5e599c1a`|

   If your file is different (another region, or a different dump), the patcher will refuse it.

2. **Two files from the** [**Releases**](../../releases) **page of this project:** the patch `digimon\_world\_1\_5\_test1.bps` and the
small disc-sheet file `digimon\_world\_1\_5\_test1.cue`.
3. **A patching tool.** Either of these works:

   * **Rom Patcher JS.** It runs in your web browser, so there's nothing to install: https://www.marcrobledo.com/RomPatcher.js/
   * **Floating IPS (Flips)** for Windows.
4. **A PlayStation emulator.** **DuckStation** is recommended.

\---

## How to install

### With Rom Patcher JS (easiest)

1. Open https://www.marcrobledo.com/RomPatcher.js/ in your browser.
2. Next to **ROM file**, pick your Digimon World `.bin` file.
3. Next to **Patch file**, pick `digimon\_world\_1\_5\_test1.bps`.
4. Click **Apply patch**. The page saves a new, patched `.bin` file to your downloads.
It's a big file (about 400 MB), so give it a moment.
5. Rename the new file to **`digimon\_world\_1\_5\_test1.bin`**.

### With Floating IPS (Windows)

1. Open `flips.exe` and click **Apply Patch**.
2. Choose `digimon\_world\_1\_5\_test1.bps`, then your original Digimon World `.bin`.
3. Save the result as **`digimon\_world\_1\_5\_test1.bin`**.

### Put the .cue file next to it

Emulators open a disc image through its `.cue` file.

1. Put the patched `digimon\_world\_1\_5\_test1.bin` and the downloaded `digimon\_world\_1\_5\_test1.cue` in the **same folder**.
2. If you'd rather make the `.cue` yourself, it's a text file with exactly these three lines:

```
   FILE "digimon\_world\_1\_5\_test1.bin" BINARY
     TRACK 01 MODE2/2352
       INDEX 01 00:00:00
   ```

   (If Windows hides file endings, make sure the file doesn't end up named `.cue.txt`.)

### Play

1. Open **`digimon\_world\_1\_5\_test1.cue`** in your emulator.
2. Start a **new game**. Saves from the original game may not work correctly with the mod.

Keep your original `.bin`. The patcher never changes it, and you'll need it again for future test builds.

\---

## Known limits of this test build

* Veemon's Champions (ExVeemon, Veedramon, Flamedramon) temporarily use **Greymon's** Ultimate forms (MetalGreymon or
SkullGreymon) until their own Ultimates are added.
* **Chicomon** uses Botamon's cries for now.
* Other new Digimon may appear in the game files and on the Digivolution Chart, but this test focuses on the Veemon and
Wormmon lines.

## Reporting problems

Please report anything that looks wrong on the **To my Discord**, https://discord.gg/gTy4nY5AM. That includes crashes, freezes, models
that look broken, wrong names, and digivolutions that don't happen.

It helps if you include:

* What you were doing, and where on the island you were
* Your partner Digimon at the time
* A screenshot or short video, if you can

\---

## Credits and legal

This is an unofficial fan project and isn't affiliated with or endorsed by Bandai Namco. *Digimon* and *Digimon World*
belong to their owners. The added models, animations and sounds come from official Digimon games. No game files or
disc images are included in this project, only a patch for a copy of the game you own.


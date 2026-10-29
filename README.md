# AstroFusion downloads

Ready-to-run **AstroFusion** apps for stacked TIFFs and Moon / planet pictures from a Vaonis Vespera / Vespera Pro: live
preview, star reduction and removal, curves, crop, watermark with capture details, recommended settings by object type.
For the Moon and planets, line up and combine many pictures into one cleaner picture, bring out the Moon's mineral colour,
and add optional made-up stars (marked as artificial in the saved file). No Python needed.

**Download:** open the [latest release](../../releases/latest) and get the zip for your computer
(`AstroFusion-Mac-AppleSilicon.zip` or `AstroFusion-Windows.zip`). Once installed, the app can check for and install
updates itself (Help → Check for Updates).

## Screenshots
Before on the left, now on the right, while you move the sliders. All of these are real Vespera data.

**Galaxy: Andromeda (M31)**, eight nights combined
![AstroFusion processing the Andromeda Galaxy, before and after](docs/screenshots/galaxy-m31.jpg)

**Emission nebula: Orion (M42)**
![AstroFusion processing the Orion Nebula, before and after](docs/screenshots/nebula-m42.jpg)

**Supernova remnant: Jellyfish Nebula (IC443)**, five nights combined
![AstroFusion processing the Jellyfish Nebula, before and after](docs/screenshots/nebula-ic443.jpg)

**The Moon, as captured and sharpened** (eight pictures lined up and combined, cropped around the Moon)
![AstroFusion with a combined, sharpened Moon](docs/screenshots/moon.jpg)

**The Moon with Mineral colour** (brings out the faint colour differences in the surface; needs a picture that has colour). Here *Color balance* is nudged toward "redder" for warmer seas; slide it the other way for a cooler look.
![AstroFusion with the Mineral colour control on the Moon](docs/screenshots/moon-mineral.jpg)

**Gallery**: every result, with the settings that made it
![The AstroFusion gallery](docs/screenshots/gallery.jpg)

## First launch
The apps are not signed with a paid developer certificate, so the first launch needs one extra step.

- **Mac:** double-click the app, click **Done** on the warning, then open **System Settings → Privacy & Security**, scroll to
  the Security section and click **Open Anyway** next to "AstroFusion was blocked". Or run this once in Terminal (adjust the path):
  `xattr -dr com.apple.quarantine ~/Downloads/AstroFusion.app`
- **Windows:** open the `AstroFusion` folder and run `AstroFusion.exe`. If SmartScreen warns, choose **More info**, then **Run anyway**.

Independent of Vaonis and not affiliated with them. Released under the MIT licence (see `LICENSE`).

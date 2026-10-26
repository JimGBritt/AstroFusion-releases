# AstroFusion downloads

Ready-to-run **AstroFusion** apps for stacked TIFFs from a Vaonis Vespera / Vespera Pro: live preview, star reduction and
removal, curves, watermark with capture details, recommended settings by object type. No Python needed.

**Download:** open the [latest release](../../releases/latest) and get the zip for your computer
(`AstroFusion-Mac-AppleSilicon.zip` or `AstroFusion-Windows.zip`). Once installed, the app can check for and install
updates itself (Help → Check for Updates).

## First launch
The apps are not signed with a paid developer certificate, so the first launch needs one extra step.

- **Mac:** double-click the app, click **Done** on the warning, then open **System Settings → Privacy & Security**, scroll to
  the Security section and click **Open Anyway** next to "AstroFusion was blocked". Or run this once in Terminal (adjust the path):
  `xattr -dr com.apple.quarantine ~/Downloads/AstroFusion.app`
- **Windows:** open the `AstroFusion` folder and run `AstroFusion.exe`. If SmartScreen warns, choose **More info**, then **Run anyway**.

Independent of Vaonis and not affiliated with them. Released under the MIT licence (see `LICENSE`).

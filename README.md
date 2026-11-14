# Silver Booth

A camera booth that runs in the browser. Open the **Inuman** effect, turn on your camera,
make a fist around a bottle to grab it, and tilt your hand to pour. Lift a glass to your face
and tilt it to drink. Take photos or 4-photo strips and save them.

Everything runs on the visitor's own phone or computer. Photos are never uploaded.

**Live site:** https://phew1.github.io/photobooth/

## How to update the site

Any change you save to this repository goes live on the site about a minute later.

- **Ask Claude:** start a Claude Code session with this repository selected and describe the change.
- **Change a bottle picture:** open the `bottles` folder, choose **Add file → Upload files**, and upload a
  PNG with the same name (`gin.png`, `vodka.png` or `beer.png`). Pictures with a transparent
  background look best.
- **Change text:** open `index.html`, click the pencil icon, edit, then click **Commit changes**.

## Files

- `index.html`: the whole booth (layout, effects and hand tracking)
- `bottles/`: the bottle pictures used by the Inuman effect

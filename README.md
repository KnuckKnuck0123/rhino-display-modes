# Rhino Display Modes Collection

A curated collection of custom Rhino viewport display modes gathered from the McNeel Discourse community.

## Source
Most of these display modes were sourced and shared by users in this thread:
[Share your custom viewport modes here - McNeel Discourse](https://discourse.mcneel.com/t/share-your-custom-viewport-modes-here/151321/424)

## How to Install
1. Open Rhino.
2. Go to **File** > **Properties** (Document Properties).
3. Navigate to **View** > **Display Modes**.
4. Click **Import** and select the `.ini` files from this collection.

## Setting up Environment Maps
Some display modes (like MatCaps or Toon shaders) require an environment map to be assigned within the display mode settings to look correct.

To "wire up" an environment map:
1. Go to **File** > **Properties** (Document Properties) > **View** > **Display Modes**.
2. Select the specific display mode from the list (e.g., a MatCap mode).
3. In the display mode tree on the left, expand it and look for **Shading Settings** or **Custom Game Tools/Rendering Material**.
4. Look for the **Environment** map slot or **Custom Rendering Material** settings.
5. Check the **Environment** box, click the browse button (...), and select one of the `.tif` or `.png` maps (e.g., from the `MATCAP_TOON` folder).

Refer to the image below for the settings configuration:

![Environment Setup Guide](environment_setup.png)

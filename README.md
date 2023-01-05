<img src="https://www.jaxon.gg/wp-content/uploads/2022/08/Steam-Featured.jpg" alt="Header image" width="100%">

# Custom Steam skin
This skin hides certain aspects of the Steam client that I dislike.
Here are a few things that are removed:

1. Hides the 'Whats New' section in the library.
2. Hides the 'Add Showcase' button on your profile.
3. Hides all the recent games on every profile (default) or shows you just the 1 most recent game instead of 3 (change in webkit.css).
4. Hides art showcases everywhere to avoid those 'transparent' steam profiles.
5. A few more things.

## Editing the skin
I tried to make the skin as editable as possible, to edit this go to the ```webkit.css``` file located in the ```resource``` folder.
In this file you can remove the lines (or comment them out) that you don't need.

## Installation
1. Download the latest release from the GitHub page on the right.
2. Unzip ```custom-steam.zip```.
3. Drag and drop the folder ```custom-steam``` inside ```C:\Program Files (x86)\Steam\skins```.

> You can create the folder 'skins' if this doesn't exist.

4. Start/restart Steam.
5. Steam settings -> Interface -> Select the skin you wish Steam to use (requires Steam to restart). 
6. Select ```custom-steam```.
7. Restart Steam.

## (Developer notes) Creating a release

> It's important to keep this structure so that the installation instructions will always work.

1. Zip the ```resource``` folder.
2. Rename the zip file to 'custom-steam.zip'.
3. Upload zip as a new release.
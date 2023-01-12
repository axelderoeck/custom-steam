<p align="center">
 <img width="300px" src="./images/repo-logo.png" align="center" alt="Antisocial" />
 <h2 align="center"></h2>
 <p align="center">A basic skin that hides certain aspects of the steam client.</p>
</p>

<p align="center">
    <a href="https://github.com/axelderoeck/custom-steam/issues">
      <img alt="Issues" src="https://img.shields.io/github/issues/axelderoeck/custom-steam" />
    </a>
    <a href="https://github.com/axelderoeck/custom-steam/releases/latest">
      <img alt="Downloads" src="https://img.shields.io/github/downloads/axelderoeck/custom-steam/total" />
    </a>
</p>

<p align="center">
    <a href="https://github.com/axelderoeck/custom-steam/releases/latest">Download latest release</a>
    ·
    <a href="https://github.com/axelderoeck/custom-steam/releases/latest">View list of hidden items</a>
    ·
    <a href="https://github.com/axelderoeck/custom-steam/issues/new/choose">Request to hide something</a>
    ·
    <a href="https://github.com/axelderoeck/custom-steam/issues/new/choose">Report a bug</a>
</p>

# Installation
1. Download the latest release from the GitHub page on the right or click <a href="https://github.com/axelderoeck/custom-steam/releases/latest">here</a>.
2. Unzip ```custom-steam.zip```.
3. Drag and drop the folder ```custom-steam``` inside ```C:\Program Files (x86)\Steam\skins```.

> You can create the folder 'skins' if this doesn't exist.

4. Start/restart Steam.
5. Steam settings -> Interface -> Select the skin you wish Steam to use (requires Steam to restart). 
6. Select ```custom-steam```.
7. Restart Steam.

# What does the skin hide?
If a feature is not default but you would like to use it, you have to uncomment the corresponding line in ```resource/webkit.css```.
If a feature is striked through that means it is currently not working.

- Hides the 'Whats New' section in the library.
- Hides the 'Add Showcase' button on your profile.
- Hides all the recent games on every profile.
- **(Not default)** Shows just 1 recent game instead of 3 on every profile.
- Hides art showcases everywhere to avoid those 'transparent' steam profiles.
- Hides every profile's ban status.
- **(Not default)** Hides the title of every showcase.
- **(Not default)** Hides the item count on every item showcase.
- Hides the spotlight section (The nagging bar asking for a review on the game page).
- Hides the post activity text submit bar on the game page.
- Hides the info section alert of a non-steam game.
- Hides the 'New in Library' banner on newly added games.
- ~~Hides the asterisk next to a nicknamed friend.~~
- Hides the 'How to get card drops' link on every badge row.
- Hides the play button on every badge row.
- ~~Hides level 0 badges when you have no cards from that collection.~~
- Hides the warning icon on item thumbnails in inventory.
- Hides the 'recently updated' section of the store.
- Hides the 'currently live streaming' section of the store.
- Hide the livestream on the product page. (NOTE: You also need to disable product streams in steam preferences)

# Editing the skin
I tried to make the skin as editable as possible, to edit this go to the ```webkit.css``` file located in the ```resource``` folder.
In this file you can remove the lines (or comment them out) that you don't need.

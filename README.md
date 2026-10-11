# Cruise Closet

A static personal photo wardrobe and outfit studio. Upload clothing photos, categorize pieces, arrange and resize them on the outfit board, and save combinations.

## Publish with GitHub Pages

In this repository, open Settings → Pages. Under Build and deployment, choose Deploy from a branch. Select main and / (root), then Save. GitHub will display the live site URL after publishing.

Expected URL: https://benczerwin.github.io/cruise-outfits/

## Storage and privacy

Photos are resized locally and stored with outfits in IndexedDB in your browser. They are never uploaded to this repository. Data stays on the current browser/device and does not sync. Clearing site data removes it. Use Back up closet & outfits to download a JSON backup and Restore backup to transfer or recover it. Restore replaces the existing closet.

The site code is public. No account, server, external dependencies, or build step is required.

## Use

1. Add photos of individual clothes.
2. Rename and categorize pieces.
3. Click Add to place a piece in the studio.
4. Drag pieces to arrange them. Select a piece and use the size buttons; arrow keys also move it.
5. Name and save an outfit. Open saved looks to make new combinations.

JavaScript syntax was checked. Full interactive browser verification is pending.

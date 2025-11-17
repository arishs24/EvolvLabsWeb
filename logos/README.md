# Logos Folder

Place institution logos in this folder.

## Recommended Logo Files:

- `harvard.png` - Harvard University logo
- `hopkins.png` - Johns Hopkins University logo
- `uoft.png` - University of Toronto logo
- `mcmaster.png` - McMaster University logo

## Logo Requirements:

- **Format**: PNG or SVG (transparent background preferred)
- **Size**: Recommended 200x120px or similar aspect ratio
- **Style**: White or light-colored logos work best on dark backgrounds
- **File Size**: Keep under 500KB for optimal performance

## How to Add Logos:

1. Place your logo files in this `logos/` folder
2. Open `index.html`
3. Find the institution logo section
4. Replace the placeholder div with an `<img>` tag:
   ```html
   <!-- Before -->
   <div class="logo-placeholder">
       <span>Harvard</span>
       <small>Add logo: logos/harvard.png</small>
   </div>
   
   <!-- After -->
   <img src="logos/harvard.png" alt="Harvard">
   ```
5. Make sure to update both the original and duplicate logo entries for seamless scrolling

## Adding More Institutions:

To add more institutions:
1. Add a new logo file to this folder
2. Add a new `<div class="institution-logo">` entry in `index.html`
3. Duplicate it for the seamless loop effect
4. Update the animation speed in `styles.css` if needed (currently 30s)


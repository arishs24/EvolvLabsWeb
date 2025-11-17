# Headshots Folder

Place team member headshot photos in this folder.

## Recommended Headshot Files:

- `arish.jpg` - Arish Shahab headshot
- `aaron.jpg` - Aaron Yu headshot
- `ramin.jpg` - Ramin Syed headshot

## Headshot Requirements:

- **Format**: JPG, PNG, or WebP
- **Size**: Recommended 400x400px or larger (square aspect ratio)
- **Style**: Professional headshot, centered face, good lighting
- **File Size**: Keep under 500KB for optimal performance
- **Aspect Ratio**: Square (1:1) works best for circular avatars

## How to Add Headshots:

1. Place your headshot files in this `headshots/` folder
2. Open `index.html`
3. Find the team member's card section
4. Uncomment the `<img>` tag and comment out or remove the placeholder:
   ```html
   <!-- Before -->
   <div class="avatar-circle">
       <div class="avatar-placeholder">
           <span>Arish</span>
           <small>Add headshot: headshots/arish.jpg</small>
       </div>
       <!-- <img src="headshots/arish.jpg" alt="Arish Shahab" class="headshot-img"> -->
   </div>
   
   <!-- After -->
   <div class="avatar-circle">
       <!-- <div class="avatar-placeholder">...</div> -->
       <img src="headshots/arish.jpg" alt="Arish Shahab" class="headshot-img">
   </div>
   ```

## Tips:

- Use high-quality, well-lit photos
- Ensure faces are centered in the frame
- Square photos work best for the circular avatar display
- Consider using a consistent style/background for all team photos
- The images will automatically be cropped to a circle


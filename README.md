# A/B Audio Player for WordPress

A simple, beautiful A/B audio player that can be embedded in WordPress using a Custom HTML block. Perfect for comparing two audio files side by side.

## Features

- Clean, modern neumorphic design
- Easy to use A/B comparison
- Progress bar with seek functionality
- Play/Pause and Stop controls
- Mobile-friendly
- Self-contained code (no external dependencies except Font Awesome)

## Installation

1. Open `wordpress-player.html` in your browser to preview how the player looks and works
2. In the source code, locate the section between the comments that indicate what to copy
3. Create a new Custom HTML block in your WordPress post/page
4. Copy and paste the code from step 2 into the Custom HTML block
5. Replace the audio file paths in the code:
   ```html
   data-audio-a="PATH_TO_YOUR_FIRST_AUDIO.mp3"
   data-audio-b="PATH_TO_YOUR_SECOND_AUDIO.mp3"
   ```
   with your actual audio file URLs
6. Update the block

## Requirements

- WordPress 5.0 or higher
- Font Awesome 6.1.1 or higher (usually included in most WordPress themes)
- If your theme doesn't include Font Awesome, you'll need to add it to your site

## Adding Font Awesome to WordPress

If your theme doesn't include Font Awesome, you can add it in one of these ways:

1. Install a Font Awesome WordPress plugin, or
2. Add this line to your theme's header:
   ```html
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css">
   ```

## Multiple Players

You can add multiple players to the same page by copying the player HTML structure multiple times within the same Custom HTML block. The CSS and JavaScript will work for all instances automatically.

## Customization

The player uses a neumorphic design with a light gray color scheme. You can customize the appearance by modifying the CSS variables in the style section of the code.

## Support

For support, please open an issue in this repository.


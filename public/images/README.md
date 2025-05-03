# Images Directory

This directory contains all images used in the website.

## Directory Structure

- `/images/` - Root images directory (favicon, profile picture, etc.)
- `/images/projects/` - Project-related images
- `/images/blog/` - Blog post images
- `/images/gallery/` - Photography portfolio images
- `/images/interests/` - Images for the interest pages

## Image Requirements

When adding images to the website, please follow these guidelines:

1. Use descriptive filenames (e.g., `smart-home-project.jpg` instead of `img001.jpg`)
2. Compress images to reduce file size (recommended tools: ImageOptim, TinyPNG)
3. Use appropriate image dimensions:
   - Blog post images: 1200x630px
   - Project thumbnails: 800x600px
   - Gallery photos: 1200x800px
   - Profile photo: 500x500px (square)

## Placeholder Images

The site is currently using placeholder images. Replace them with actual images when available.

- For actual deployment, you would need to replace these with your own images
- You can use services like Unsplash (https://unsplash.com/) for free stock photos
- Always ensure you have the rights to use any images on your website

## Image Optimization

Before adding images to the site, optimize them for web:

```bash
# Example optimization command using ImageMagick
convert original.jpg -resize 1200x630 -quality 85 optimized.jpg
``` 
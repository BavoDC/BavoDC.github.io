# Jekyll Theme Migration to Forty

Your website has been successfully migrated from the Cayman theme to the **Forty Jekyll Theme**.

## What Changed

### Configuration
- **Theme**: Updated from `pages-themes/cayman` to `andrewbanchich/forty-jekyll-theme`
- **_config.yml**: Completely restructured to match Forty theme requirements
- **Plugins**: Added `jekyll-seo-tag` for better SEO support

### Layout Changes
- **Homepage**: Now uses the `home` layout with tile display
- **Pages**: About, Blog, and Publications now use the `page` layout
- **Layouts**: Updated `_layouts/default.html` to Forty's structure

### Page Structure
All your content has been preserved and reorganized:
- **index.md**: Landing page with brief introduction and tiles
- **about.md**: Full about page with education and background
- **Blog.md**: Blog listing with all your posts
- **Publications.md**: Research publications and software packages

## Required Next Steps

### 1. Add Placeholder Images
The Forty theme uses tile images on the homepage. You should add images for each page:

- `assets/images/pic09.jpg` - About page image
- `assets/images/pic10.jpg` - Blog page image  
- `assets/images/pic11.jpg` - Publications page image

You can:
- Create the `assets/images/` directory if it doesn't exist
- Add your own images (recommended size: 645×680px for tiles)
- Or download placeholder images and customize them

### 2. Update Social Links
Your social media links are already configured in `_config.yml`:
```yaml
socials:
  GitHub: https://github.com/BavoDC
  LinkedIn: https://linkedin.com/in/bavodccampo
  envelope: mailto:bavo.campo@kuleuven.be
```

These will appear in the footer and can be customized with appropriate icons from Font Awesome.

### 3. Build and Test Locally
To test the migration locally:
```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000` to see your site.

### 4. Verify Navigation
The Forty theme automatically generates navigation from pages with `nav-menu: true`. Your pages are already configured:
- About
- Blog
- Publications

### 5. Blog Posts
Your blog posts remain in `_posts/` and will automatically appear on the Blog page.

## Important Notes

- **Tiles**: The homepage displays your About, Blog, and Publications pages as tiles. Each tile shows the page title and description.
- **Images**: Without the image files, tiles will still display but without the visual element.
- **CSS**: The Forty theme handles all styling. Remove the old `main.css` if not needed.
- **CV**: Your CV link is available directly from the code; consider adding a dedicated CV page if desired.

## Theme Customization

If you need to customize colors, fonts, or other styling:
1. Customize SCSS files in `assets/css/` (if copied from theme repo)
2. Or override styles in your main CSS file

## Support

For more information about the Forty theme:
- GitHub: [andrewbanchich/forty-jekyll-theme](https://github.com/andrewbanchich/forty-jekyll-theme)
- Theme Features: Includes contact form integration, customizable tiles, and Font Awesome icons

## Reverting Changes

All original files have been modified but not deleted. You can retrieve them from your Git history if needed.

---

**Migration completed!** Your site now uses the modern Forty Jekyll theme while preserving all your content.

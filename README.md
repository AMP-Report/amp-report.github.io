# AMP Report - Jekyll GitHub Pages Site

This repository contains the Jekyll-powered GitHub Pages site for AMP Report, a comprehensive property cost analysis platform.

## 🏗️ Site Structure

This site has been converted from static HTML to Jekyll to enable:
- **Markdown content management** - Write content in Markdown instead of HTML
- **Blog functionality** - Automatic blog post generation and listing
- **Template reuse** - Consistent layouts across all pages
- **GitHub Pages native support** - Automatic building and deployment

## 📁 Directory Structure

```
├── _config.yml              # Jekyll configuration
├── _layouts/                # Page templates
│   └── default.html         # Main layout template
├── _includes/               # Reusable components
├── _pages/                  # Static pages
│   ├── about.md
│   ├── blog.md
│   └── schemas.md
├── _posts/                  # Blog posts
│   └── 2024-12-26-welcome-to-amp-report.md
├── index.md                 # Homepage (Jekyll format)
├── index.html               # Original homepage (preserved)
├── database-schema-*.html   # Schema documentation (preserved)
├── Gemfile                  # Ruby dependencies
└── README.md               # This file
```

## 🚀 Getting Started

### For GitHub Pages (Automatic)
1. Push changes to the `main` branch
2. GitHub Pages will automatically build and deploy the site
3. Visit your site at `https://amp-report.github.io`

### For Local Development
1. Install Ruby and Bundler
2. Run `bundle install` to install dependencies
3. Run `bundle exec jekyll serve` to start local server
4. Visit `http://localhost:4000` to view the site

## ✍️ Content Management

### Adding Blog Posts
1. Create a new file in `_posts/` with format: `YYYY-MM-DD-title.md`
2. Add front matter:
   ```yaml
   ---
   layout: default
   title: "Your Post Title"
   date: 2024-12-26 10:00:00 -0500
   categories: [category1, category2]
   tags: [tag1, tag2]
   excerpt: "Brief description of the post"
   ---
   ```
3. Write content in Markdown below the front matter

### Adding Pages
1. Create a new file in `_pages/` with `.md` extension
2. Add front matter with `permalink` field:
   ```yaml
   ---
   layout: default
   title: "Page Title"
   permalink: /page-url/
   ---
   ```
3. Write content in Markdown

### Editing Existing Content
- **Homepage**: Edit `index.md`
- **About**: Edit `_pages/about.md`
- **Schemas**: Edit `_pages/schemas.md`
- **Blog**: Edit `_pages/blog.md`

## 🎨 Customization

### Styling
- Main styles are in `_layouts/default.html`
- Page-specific styles can be added via `custom_css` front matter variable
- Global styles can be added to the layout template

### Navigation
- Navigation links are defined in `_layouts/default.html`
- Update the navigation section to add/remove menu items

### Site Configuration
- Edit `_config.yml` to change site title, description, and other settings
- Add new plugins to the `plugins` section

## 🔄 Migration Notes

### Preserved Files
- All original HTML schema files are preserved and functional
- Original `index.html` is kept as backup
- All existing functionality remains intact

### New Features
- Jekyll-powered blog at `/blog/`
- Markdown-based content management
- SEO optimization with jekyll-seo-tag
- Automatic sitemap generation
- RSS feed generation

### URL Structure
- Homepage: `/` (now served by `index.md`)
- About: `/about/`
- Schemas: `/schemas/`
- Blog: `/blog/`
- Blog posts: `/YYYY/MM/DD/post-title/`
- Schema pages: `/database-schema-diagram-option-*.html` (unchanged)

## 🛠️ Technical Details

### Jekyll Plugins
- `jekyll-feed`: Generates RSS feed
- `jekyll-sitemap`: Generates sitemap.xml
- `jekyll-seo-tag`: Adds SEO meta tags

### GitHub Pages Compatibility
- Uses `github-pages` gem for full compatibility
- All plugins are GitHub Pages approved
- Automatic building and deployment

## 📝 Content Guidelines

### Front Matter Variables
- `layout`: Template to use (usually "default")
- `title`: Page/post title
- `description`: Meta description for SEO
- `permalink`: Custom URL (for pages)
- `date`: Publication date (for posts)
- `categories`: Post categories (for posts)
- `tags`: Post tags (for posts)
- `excerpt`: Brief description (for posts)
- `custom_css`: Additional CSS for the page

### Markdown Features
- Standard Markdown syntax
- HTML can be mixed with Markdown
- Liquid templating for dynamic content
- Front matter for metadata

## 🔗 Links and References

- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/)
- [Liquid Template Language](https://shopify.github.io/liquid/)

---

**AMP Report** - Transforming property investment intelligence through data-driven insights. 
---
title: "Internal: Logo Setup"
hidden: true
robots: "noindex, nofollow"
---

# Flyweel Logo Setup Complete ✅

## Logos Successfully Copied and Configured

### ✅ **Source Files Copied:**
- **From**: `/home/rs/code/astro-flyweel/public/`
- **To**: `/home/rs/code/docs/logo/`

### ✅ **Files Available:**
- `light.svg` (8.9K) - White Flyweel logo for light backgrounds  
- `dark.svg` (17K) - Full-color Flyweel logo for dark backgrounds
- `logo.webp` (1.6K) - Compressed web format logo
- `favicon.svg` - Favicon copied from main site

### ✅ **Mintlify Configuration Updated:**
```json
{
  "logo": {
    "light": "/logo/light.svg",
    "dark": "/logo/dark.svg", 
    "href": "https://flyweel.co"
  }
}
```

### ✅ **Logo Features:**
- **Brand Consistency**: Actual Flyweel logos with proper colors (#90DAB8)
- **Responsive**: Automatic light/dark theme switching
- **Clickable**: Logo links back to main Flyweel site (flyweel.co)
- **High Quality**: Vector SVG format for crisp display at all sizes
- **Proper Sizing**: Optimized for Mintlify header display

### ✅ **Visual Elements:**
- **Brandmark**: Distinctive three-part geometric icon
- **Wordmark**: "flyweel" text in brand font
- **Colors**: Matches exact brand colors from main site
- **Positioning**: Top-left corner of documentation site

## Result
The Flyweel logo now appears properly in the top-left corner of the Mintlify documentation site at:
- **Live URL**: https://flyweel.mintlify.app/
- **Local Preview**: `mintlify dev` 

Users can click the logo to navigate back to the main Flyweel website, maintaining brand consistency and navigation flow between the product and documentation sites.

## Files Structure
```
/home/rs/code/docs/
├── logo/
│   ├── light.svg      (Flyweel logo - light theme)
│   ├── dark.svg       (Flyweel logo - dark theme) 
│   ├── logo.webp      (Backup web format)
│   └── ...
├── favicon.svg        (Flyweel favicon)
├── docs.json         (Updated with logo config)
└── ...
```

The logo setup is now complete and ready for deployment! 🚀

---
title: "Internal: Theme Logos Setup"
hidden: true
robots: "noindex, nofollow"
---

# ✅ Theme-Specific Flyweel Logo Setup Complete

## Logo Configuration Summary

### **Light Theme Logo:**
- **File**: `flyweel-light-theme.webp` (142K)
- **Description**: Dark green text with gradient icon on transparent background
- **Usage**: Shows on light backgrounds/themes
- **Visual**: Green gradient icon + dark green "flyweel" text

### **Dark Theme Logo:**  
- **File**: `flyweel-dark-theme.webp` (138K)
- **Description**: Light text with gradient icon on transparent background
- **Usage**: Shows on dark backgrounds/themes  
- **Visual**: Green gradient icon + light "flyweel" text

## Mintlify Configuration
```json
{
  "logo": {
    "light": "/logo/flyweel-light-theme.webp",
    "dark": "/logo/flyweel-dark-theme.webp", 
    "href": "https://flyweel.co"
  }
}
```

## Theme Behavior
- **Light Mode**: Users see the dark text version (better contrast on light backgrounds)
- **Dark Mode**: Users see the light text version (better contrast on dark backgrounds)  
- **Auto-Switch**: Mintlify automatically switches based on user's theme preference
- **Clickable**: Both logos link back to main Flyweel site

## File Structure
```
/home/rs/code/docs/logo/
├── flyweel-light-theme.webp    (142K - Dark text for light backgrounds)
├── flyweel-dark-theme.webp     (138K - Light text for dark backgrounds)
├── favicon.svg                 (Flyweel favicon)
└── ...
```

## Visual Result
- **Perfect Contrast**: Each logo version provides optimal readability on its respective background
- **Brand Consistency**: Same gradient icon and typography across both themes
- **Professional**: High-quality WebP format for crisp display
- **Responsive**: Works across all device sizes

## Live Site
Your theme-specific logos are now configured at:
- **URL**: https://flyweel.mintlify.app/
- **Local Preview**: `mintlify dev`

Users will see the appropriate logo version based on their theme preference, ensuring perfect contrast and readability in both light and dark modes! 🚀
